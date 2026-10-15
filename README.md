# Awesome-Web-Frameworks

## Top Workflow Orchestration Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Data Pipelines, Durable Execution, DAG Scheduling, ML Workflows & Business Process Orchestration*  

**Last updated: October 2026**



This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Workflow Orchestration**. These systems define, schedule, retry, and observe multi-step jobs—ETL/ELT, ML training, microservice sagas, and long-running business processes.



**Examples** include Apache Airflow, Astronomer, Prefect, Dagster Cloud, AWS Step Functions, Temporal Cloud, Flyte, Kubeflow, Google Cloud Composer, Azure Data Factory, and **Dagster** (`dagster-io/dagster`)—an orchestration platform for data assets.



**Open-source emphasis**: Workflow orchestration is strongly open source. **Airflow**, **Dagster**, **Prefect**, **Temporal**, **Flyte**, and **Argo Workflows** power production data and application pipelines worldwide. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Astronomer, Google Cloud Composer, Amazon MWAA](https://www.astronomer.io/)**  

  Managed Apache Airflow offerings—hosted control planes, scaling, and cloud integrations for data teams.



- **[Prefect Cloud, Dagster+](https://www.prefect.io/)**  

  Managed platforms around modern Python-native orchestrators with hybrid execution and observability.



- **[Temporal Cloud, AWS Step Functions, Azure Data Factory](https://temporal.io/)**  

  Durable execution and cloud-native workflow services for application and integration orchestration.



- **[Flyte (Union.ai), Kubeflow-oriented managed offerings](https://flyte.org/)**  

  Hosted ML and data workflow platforms built on open orchestrators.



- **[Other managed workflow platforms](https://aws.amazon.com/step-functions/)**  

  Additional serverless and enterprise orchestration services.



## Open-Source GitHub Projects



- **[Apache Airflow](https://github.com/apache/airflow)**  

  Leading open-source platform to programmatically author, schedule, and monitor workflows as DAGs—industry standard for data engineering.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Open orchestration platform centered on data assets—software-defined assets, strong typing, and development-oriented tooling.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Open Python-native workflow orchestration—dynamic flows, hybrid execution, and a modern developer experience.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Open durable execution engine—workflows as code with automatic retries, timers, and versioning for reliable distributed processes.



- **[Flyte](https://github.com/flyteorg/flyte)**  

  Open Kubernetes-native workflow orchestrator optimized for data and ML pipelines with strong reproducibility.



- **[Argo Workflows](https://github.com/argoproj/argo-workflows)**  

  Open container-native workflow engine for Kubernetes—DAGs and steps as CRDs.



- **[Kubeflow Pipelines](https://github.com/kubeflow/pipelines)**  

  Open ML workflow platform on Kubernetes—pipeline authoring, experiment tracking, and recurring runs.



- **[Luigi](https://github.com/spotify/luigi)**  

  Open Python pipeline framework from Spotify—dependency-aware batch workflows, still widely used.



- **[Tekton](https://github.com/tektoncd/pipeline)**  

  Open Kubernetes-native CI/CD and pipeline primitives often reused for general workflow steps.



- **[Cadence](https://github.com/cadence-workflow/cadence)**  

  Open workflow orchestration engine (Uber origin) related in design lineage to Temporal.



- **[Mage / Kestra / Windmill](https://github.com/mage-ai/mage-ai)**  

  Emerging open orchestrators focused on developer UX, hybrid pipelines, and automation.



### Additional Strong Open-Source Options



- **Data engineering DAGs**: Apache Airflow or Dagster.

- **Python-first dynamic flows**: Prefect.

- **Durable application workflows**: Temporal.

- **K8s-native / ML**: Flyte, Argo Workflows, Kubeflow Pipelines.

- **Composable stacks**: Orchestrator → object storage → warehouse/lake → observability (OpenTelemetry).

- Managed clouds reduce ops for the control plane; execution often still runs in your VPC with open workers.



**Frameworks for building custom systems**:  

**Airflow** or **Dagster** for data asset pipelines; **Prefect** for flexible Python flows; **Temporal** for long-running business logic; **Flyte** / **Argo** on Kubernetes for ML and container steps.  

Fully open workflow orchestration is production-standard across startups and large enterprises.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Workflow engines often hold credentials and can mutate production data. Apply least-privilege connections, secret management, and audit logging. Design tasks to be idempotent—retries will happen.

- Open-source orchestrators offer control and portability but require you to operate databases, queues, and workers. Managed platforms shift control-plane operations to the vendor. Neither replaces careful data contracts and failure handling.



---



**Made for data engineers, platform teams, and builders of reliable multi-step systems.**  

Let's expand open workflow orchestration while recognizing the managed convenience that hosted Airflow, Prefect, Dagster, and Temporal clouds deliver.
# Awesome-Web-Frameworks

# Top Web Frameworks Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Modern Full-Stack & Frontend Meta-Frameworks, Static Site Generation, SSR/SSG & Edge-Ready Web Apps*  
**Last updated: October 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Web Frameworks**. These tools help teams build and ship websites and apps—SSG, SSR, islands architecture, and full-stack React/Vue/Svelte/other stacks—with strong developer experience.

**Examples** include Gatsby, Netlify, Vercel, Next.js, Cloudflare Pages, AWS Amplify, Render, Supabase, Sanity, Contentful, and **Astro** (`withastro/astro`)—build fast websites, faster.

**Open-source emphasis**: Application frameworks themselves are open source. **Next.js**, **Astro**, **Nuxt**, **SvelteKit**, **Remix**, **Gatsby**, and **Eleventy** lead the modern web. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Vercel, Netlify, Cloudflare Pages](https://vercel.com/)**  
  Leading deployment platforms optimized for modern web frameworks—preview deploys, edge functions, and global CDN delivery.

- **[AWS Amplify, Render, Railway](https://aws.amazon.com/amplify/)**  
  Cloud and PaaS hosts commonly used for Next.js, Astro, and full-stack web apps.

- **[Contentful, Sanity, Supabase (as backend companions)](https://www.contentful.com/)**  
  Headless CMS and backend services frequently paired with open web frameworks for content and data.

- **[Other JAMstack / web app hosts](https://www.netlify.com/)**  
  Additional managed platforms for static and hybrid web applications.

## Open-Source GitHub Projects

### Meta-Frameworks & Full-Stack

- **[Next.js](https://github.com/vercel/next.js)**  
  Leading open React framework—SSR, SSG, App Router, Server Components, and a massive production ecosystem.

- **[Astro](https://github.com/withastro/astro)**  
  Open web framework for content-focused sites—islands architecture, multi-UI-framework support, and excellent performance defaults.

- **[Nuxt](https://github.com/nuxt/nuxt)**  
  Open Vue.js meta-framework—SSR, SSG, file-based routing, and a strong module ecosystem.

- **[SvelteKit](https://github.com/sveltejs/kit)**  
  Open full-stack framework for Svelte—adapters for many hosts, excellent DX, and small client bundles.

- **[Remix](https://github.com/remix-run/remix)**  
  Open full-stack web framework focused on web standards, nested routing, and progressive enhancement (React).

- **[Gatsby](https://github.com/gatsbyjs/gatsby)**  
  Open React-based SSG/framework with a rich plugin system for content sites and data from many sources.

- **[SolidStart](https://github.com/solidjs/solid-start)**  
  Open full-stack framework for SolidJS—fine-grained reactivity and modern routing.

- **[Qwik City](https://github.com/QwikDev/qwik)**  
  Open resumable framework aimed at instant-on performance and edge deployment.

### Static Site Generators & Lighter Stacks

- **[Eleventy (11ty)](https://github.com/11ty/eleventy)**  
  Flexible open static site generator—simple, fast, and framework-agnostic.

- **[Hugo](https://github.com/gohugoio/hugo)**  
  Extremely fast open static site generator written in Go—ideal for large content sites.

- **[Jekyll](https://github.com/jekyll/jekyll)**  
  Classic open SSG in Ruby—still widely used for blogs and documentation.

- **[VitePress / Docusaurus](https://github.com/vuejs/vitepress)**  
  Open documentation-oriented static site tools built on Vite and React respectively.

- **[Fresh (Deno)](https://github.com/denoland/fresh)**  
  Open edge-oriented web framework for Deno with islands and zero-config deploys.

### UI Libraries Often Used With Frameworks

- **[React, Vue, Svelte, Solid](https://github.com/facebook/react)**  
  Open UI libraries that underpin the meta-frameworks above.

- **[Vite](https://github.com/vitejs/vite)**  
  Open next-generation frontend tooling—dev server and build engine used by many modern frameworks.

### Additional Strong Open-Source Options

- **React full-stack**: Next.js or Remix.
- **Content sites / multi-framework**: Astro.
- **Vue**: Nuxt.
- **Svelte**: SvelteKit.
- **Pure SSG**: Eleventy or Hugo.
- **Composable stacks**: Framework → headless CMS (open or SaaS) → deploy to Vercel/Netlify/Cloudflare Pages or self-hosted Node.
- Hosted platforms still lead for zero-config previews, edge networks, and team workflow integrations.

**Frameworks for building custom systems**:  
**Next.js** for React apps; **Astro** for content-heavy and multi-framework sites; **Nuxt** / **SvelteKit** for Vue/Svelte; **Eleventy** / **Hugo** for pure static.  
Deploy with open Node hosts or SaaS platforms.  
Fully open web framework stacks are the default for modern web development.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Web frameworks evolve quickly—pin versions, follow security advisories, and test upgrades. Server-side rendering increases attack surface; validate input and protect secrets in environment configuration.
- Open-source frameworks offer control and no framework license fees. Hosted platforms shift build, CDN, and preview infrastructure to the vendor. Neither replaces performance budgets, accessibility, and solid content modeling.

---

**Made for frontend engineers, content teams, and builders of the modern web.**  
Let's expand open web frameworks while recognizing the deployment DX that leading hosting platforms deliver.
