<div align="center">
  <img src="assets/header.svg" alt="Peter Yousefi, Applied AI engineer" width="100%">
</div>

<div align="center">

[![Azure Fundamentals](https://img.shields.io/badge/Microsoft_Certified-Azure_Fundamentals_(AZ--900)-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)](https://www.linkedin.com/in/peteryo)
[![Website](https://img.shields.io/badge/petery.org-24292f?style=flat-square&logo=safari&logoColor=white)](https://petery.org)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-24292f?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/peteryo)
[![Email](https://img.shields.io/badge/peter@petery.org-24292f?style=flat-square&logo=gmail&logoColor=white)](mailto:peter@petery.org)

</div>

## About

I build applied AI systems where output is verified rather than assumed: schema contracts, evidence-grounded assessments, audit trails, and human approval before anything consequential happens. My recent work centers on AI agent execution, evaluation, and observability.

Computer Science graduate (Trent University, 2026), based in Toronto and open to Applied AI and Generative AI engineering roles.

## Certification

**Microsoft Certified: Azure Fundamentals (AZ-900)**, September 2026

## Stack

| | |
|---|---|
| **AI and LLM** | OpenAI API, IBM watsonx.ai, Firecrawl, prompt design, structured output validation, LLM output evaluation |
| **Backend** | Python, FastAPI, TypeScript, Fastify, C# / .NET, Java, REST APIs |
| **Frontend** | React, Next.js |
| **Data** | PostgreSQL, Prisma, SQLAlchemy, SQLite |
| **Cloud and DevOps** | Azure (Container Apps, Service Bus, Blob Storage, PostgreSQL), Docker, GitHub Actions, OpenTelemetry |

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### [Agent Flight Recorder](https://github.com/PeterYousefi/Agent-Flight-Recorder)
Local-first execution control plane for AI agent workloads. Records attempts, retries, costs, and artifacts, with replay, cancellation, dead-letter handling, and distributed tracing.

`TypeScript` `Fastify` `PostgreSQL` `Azure Service Bus` `OpenTelemetry`

</td>
<td width="50%" valign="top">

### [CrawlOps](https://github.com/PeterYousefi/CrawlOps)
Evaluation and observability for Firecrawl-powered research workflows. Grades each run against JSON Schema contracts, tracks provenance, and reports reliability across repeated runs.

`TypeScript` `Fastify` `PostgreSQL` `Azure Container Apps`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AegisOps](https://github.com/PeterYousefi/AegisOps)
Human-governed incident response. Combines alerts, metrics, logs, and runbooks into evidence-grounded assessments, with explicit approval and an append-only audit trail. Synthetic incidents, simulated remediation.

`Python` `FastAPI` `PostgreSQL` `Next.js`

</td>
<td width="50%" valign="top">

### [AgentDrift](https://github.com/PeterYousefi/AgentDrift)
Investigation tool for unusual AI-agent metadata movement. Behavioral rules, historical baselines, and temporal correlation feed an evidence graph and citation-validated reports. Responses require human approval.

`Python` `FastAPI` `React` `SQLite`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>

<br>

| Project | Description | Stack |
|---|---|---|
| [Continuity](https://github.com/PeterYousefi/Continuity) | Turns a story, style guide, and character sheet into scene-by-scene images, with editable prompts and with/without character guidance comparison. Live demo on Vercel. | TypeScript, Next.js, OpenAI |
| [Lumina](https://github.com/PeterYousefi/Lumina) | Five-step AI marketing campaign workflow for small businesses, with review before publishing, mock fallbacks, and a dry-run mode. | Flask, IBM watsonx.ai, image providers |
| [Falsifier](https://github.com/PeterYousefi/Falsifier) | Pipeline that challenges apparent exoplanet transit signals with astrophysical false-positive checks. Vets candidates; does not confirm biosignatures. | Python, automated tests, evaluation tooling |
| [Sharp](https://github.com/PeterYousefi/Sharp) | NFL odds dashboard with bet slips, P&L and ROI tracking, deterministic payout math, and optional AI-written analysis. | React, Vite, Express, SQLite |
| [GeoShield](https://github.com/PeterYousefi/GeoShield) | Prescribed-burn planning tool that finds intersecting jurisdictions from a drawn boundary and drafts notification emails for review. | C#, .NET 8, Blazor, watsonx.ai |

</details>

## Approach

- **Verify AI output.** Contracts, evidence IDs, and citation checks instead of trusting the model.
- **Keep a human in the loop.** Approval gates on consequential actions, with audit trails.
- **Measure reliability.** Repeated runs, recorded failures, retries, and cost tracking across every workflow.
