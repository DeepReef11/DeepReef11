# Jonathan Bérubé

**Full-stack developer & AI integration — available for contract work.**
Quebec, Canada · **US Eastern time zone** · Remote since 2020 · Bilingual FR/EN

Eight years building enterprise software, most of it as a consultant for Quebec
government clients: a SharePoint 2013 → SharePoint Online migration with PowerShell
tooling, a contract-management portal with a complex permission model, C#/.NET backends
on SQL Server, and TypeScript/React front ends. I also design, solder, flash and
commission my own hardware — from embedded firmware up to the infrastructure that
monitors it.

Currently focused on **AI integration**: agent plumbing, MCP servers, and running models
on my own hardware for clients who can't send data to a hosted API.

## Public work

- **[sharepoint-devtools](https://github.com/DeepReef11/sharepoint-devtools)** —
  Chrome/Edge extension for SharePoint Online: keyboard-driven navigation across a tenant
  plus inspectors that surface what the UI hides — internal column names, list GUIDs,
  content types, permission assignments — without a settings page or a PowerShell console.
  TypeScript, Manifest V3, read-only, multi-tenant (Commercial/GCC/GCC High/China).
  **133 tests.**
- **[ralph](https://github.com/DeepReef11/ralph)** — Stateless agent orchestrator in Bash
  that loops a coding agent against acceptance criteria, with cost caps, stuck detection
  and subagent delegation. **Finished experiment (Jan–Feb 2026), not maintained** — the
  useful part is why: a loop like this needs its acceptance criteria up front, which makes
  it good at rebuilding what already exists and the opposite of agile.
- **[esp32c6-fridge-monitor](https://github.com/DeepReef11/esp32c6-fridge-monitor)** —
  Fridge temperature + door monitoring on XIAO ESP32-C6 over Zigbee: ESPHome/ESP-IDF
  firmware, root-cause diagnosis of the FM8625H RF-switch issue, perfboard build guide and
  commissioning playbook.
- **[build123d-ocp-vscode-browser-extension](https://github.com/DeepReef11/build123d-ocp-vscode-browser-extension)** —
  Browser extension adding keyboard shortcuts to the OCP CAD viewer (build123d).
- **[pydiylc](https://github.com/DeepReef11/pydiylc)** — Python library to read, write and
  render DIYLC (`.diy`) circuit layout files.
- **[baby-sleep-tracker](https://github.com/DeepReef11/baby-sleep-tracker)** — Sleep
  tracking integrated into Home Assistant (standalone Python service).
- **[ptouch-label-cli](https://github.com/DeepReef11/ptouch-label-cli)** — ClojureScript
  CLI for Brother P-touch label printers.

## In the lab (private, self-hosted)

- **Local AI** — models running on my own hardware (AMD/ROCm): MCP servers, transcription
  and summarization pipelines, and an image-generation setup I wrapped so prompts can be
  composed programmatically rather than typed one at a time. I script and orchestrate these
  models; I don't train or fine-tune them.
- **Infrastructure as code** — 7 Linux machines fully provisioned with Ansible (38 roles):
  Prometheus/Grafana/Alertmanager monitoring, VLAN segmentation for the IoT network,
  site-to-site WireGuard VPN, encrypted backups.
- **Parametric CAD** — a build123d library (~8,000 lines: enclosures, gears, threads,
  dimensioned drawings) feeding a full modelling → slicing → 3D printing pipeline.
- **Home sensor network** — ESP32-C6 nodes (ESPHome, Zigbee) with documented sensor
  selection.

**Stack** · Python · TypeScript/React · C#/.NET · Go · SharePoint/M365 · Azure ·
ESPHome/ESP-IDF · Home Assistant · Ansible · Docker · build123d

📫 **jonathan.berube.ti@pm.me** · [LinkedIn](https://www.linkedin.com/in/jonathan-berube)

*Disponible pour des mandats à distance, en français comme en anglais.*
