# Jonathan Bérubé

**Full-stack developer & AI integration — available for contract work.**
Remote since 2020 · US Eastern · Bilingual FR/EN

Eight years building enterprise software, most of it consulting for Quebec government
clients: a SharePoint 2013 → SharePoint Online migration with PowerShell tooling, a
contract-management portal with a complex permission model, C#/.NET backends on SQL Server,
and TypeScript/React front ends.

**Now working on AI integration** — agent plumbing, MCP servers, and models running on my
own hardware (AMD/ROCm) for clients who can't send data to a hosted API: local inference,
transcription and summarization pipelines, and an image-generation setup I wrapped so
prompts can be composed programmatically instead of typed one at a time. I script and
orchestrate these models — I don't train or fine-tune them. Most of this lives in private
repos.

**An in-app AI help assistant, built for production** — shipped into a weekly timesheet
platform (Next.js, Prisma, role-based approvals, bilingual FR/EN). It is **data-blind by
design**: the model receives a static application guide, a catalog of highlightable UI
targets, the chat text, and the user's role — nothing else from the session, and a test
keeps the endpoint free of any database access. On top of that, global and per-user caps on
queries, tokens and cost, priced per model, where only successful calls count against a
quota. Factored out as a reusable package with **76 passing tests**. Private repos for now.

Also self-hosted: 7 Linux machines provisioned with Ansible (38 roles), with
Prometheus/Grafana monitoring, VLAN segmentation and a site-to-site VPN. And I build my own
hardware — ESP32-C6 sensor nodes on ESPHome/Zigbee, parametric CAD in build123d.

👉 **Start with [sharepoint-devtools](https://github.com/DeepReef11/sharepoint-devtools)** —
TypeScript, Manifest V3, read-only, 133 tests. It's the clearest sample of how I work.
The rest is pinned below.

**Stack** · Python · TypeScript/React · C#/.NET · Go · SharePoint/M365 · Azure · Ansible ·
Docker · ESPHome

📫 **jonathan.berube.ti@pm.me** · [LinkedIn](https://www.linkedin.com/in/jonathan-berube)

*Disponible pour des mandats à distance, en français comme en anglais.*
