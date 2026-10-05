# Meghana Sai Vattikuti

Cloud infrastructure and solutions engineer with 4.5 years of experience designing, provisioning, and operating infrastructure, and increasingly building the applications that run on top of it.

Currently at the U.S. Center for SafeSport.

## About

Most of my career has been spent on the infrastructure side: Terraform modules, AWS architecture, Kubernetes deployments, CI/CD pipelines, and the unglamorous work of making environments reproducible. Solutions engineering is where that background gets put to use in front of people, translating what a platform actually does into an architecture a team can commit to.

I've found the most convincing way to answer an architecture question is to build the thing and show the result. So alongside the infrastructure work, I build small, complete applications that take an idea end to end on real infrastructure, under real constraints. Each one is deployed, and each one documents the controls it actually applies rather than the ones it would like to claim.

## What I focus on

**Infrastructure as code.** Terraform for AWS and multi-environment setups, reusable modules, remote state, and deployments that can be torn down and rebuilt without ceremony.

**Cloud architecture.** Serverless and container workloads on AWS, along with the IAM, networking, and CI/CD wiring that makes them deployable by someone other than the author.

**Solutions and migration work.** Assessing an existing deployment, mapping what moves and what stays, and producing a phased plan with compliance and risk answered concretely instead of in marketing language.

**Applied AI.** Structured model output, agent tooling, and the execution and validation layers around generated code, treating model output as untrusted input that has to be reviewed, constrained, and contained.

**Platform engineering.** Developer-facing tooling, deployment platforms, and reducing the distance between a developer's intent and a running environment.

## Selected work

### [SandboxScope](https://github.com/meghanasaivattikuti/SandboxScope)

Ask a plain-language question about a CSV, review the Python the model writes, then run it in an isolated Vercel Sandbox with outbound network access denied. Generated programs are signed server-side, so only code the application produced can execute. Every run returns a receipt showing runtime, network policy, exit status, duration, and cleanup. The static code check is documented as a quality gate, not a security boundary. Isolation is what contains the code.

`Next.js` · `TypeScript` · `AI SDK` · `AI Gateway` · `Vercel Sandbox` · `Zod`

### [Migration Readiness Advisor](https://github.com/meghanasaivattikuti/migration-advisor)

Assesses an enterprise's current AWS deployment and generates a phased migration architecture: migration complexity, precisely what moves and what stays, the target hybrid architecture, IaC guidance, a SOC 2 / PCI DSS / HIPAA compliance mapping, and a rollout plan. Built around the observation that teams evaluating a platform need the boundary drawn before they'll commit.

`Next.js` · `AI SDK` · `Terraform` · [Live](https://migration-advisor.vercel.app)

### [PDD Modernization Demo](https://github.com/meghanasaivattikuti/tech-demo)

A modernized architecture for a public disciplinary database lookup tool, inspired by real sports-safety databases. All data in the project is fictional and it is not affiliated with any real organization.

`Next.js` · `SQL Server` · `AI Gateway` · [Live](https://tech-demo-inky.vercel.app)

### [CrawlSpace](https://github.com/meghanasaivattikuti/eve)

Audits a site across three areas: whether it is actually readable by AI agents and crawlers (`llms.txt`, `AGENTS.md`, and robots rules for GPTBot, ClaudeBot, Google-Extended, PerplexityBot, CCBot), SEO fundamentals including structured data and server-rendered content, and HTTP security headers such as HSTS, CSP, and Permissions-Policy.

`Agents` · `SEO` · `Web security` · [Live](https://eve-virid-eight.vercel.app)

## Infrastructure work

### [wb-server](https://github.com/meghanasaivattikuti/wb-server)

A Weights & Biases server deployment done two ways for comparison: once with the official W&B Terraform module, and once with the Kubernetes operator, each on its own branch with separate documentation.

`Terraform` · `Kubernetes` · `AWS`

### [cloud-api](https://github.com/meghanasaivattikuti/cloud-api)

A serverless resume API backed by DynamoDB, with infrastructure managed in Terraform and continuous deployment through GitHub Actions.

`Terraform` · `AWS` · `DynamoDB` · `GitHub Actions`

### [GradVault](https://github.com/meghanasaivattikuti/grad-vault)

A document management system for academic material, supporting upload and categorization of documents by semester and type, on AWS S3.

`Terraform` · `AWS S3` · `React`

## Toolbox

**Infrastructure** Terraform, Terraform Cloud, AWS, Kubernetes, Docker

**CI/CD** GitHub Actions, automated deployment pipelines, multi-environment promotion

**Application** TypeScript, Next.js, React, Node.js, Python, SQL Server

**AI** Vercel AI SDK, AI Gateway, structured output, agent tooling, sandboxed code execution

**Practices** Infrastructure as code, least-privilege IAM, reproducible environments, documented trade-offs

## Elsewhere

[LinkedIn](https://www.linkedin.com/in/meghanasai/)
