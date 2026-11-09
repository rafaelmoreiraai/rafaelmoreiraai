<div align="center">

<img src="./assets/banner.svg" alt="Rafael Moreira Lima — AI Systems & Autonomous Agents Engineer" width="100%"/>

<br/>

### I build the infrastructure and intelligence that make autonomous agents reliable, observable, and cost-aware.
<sub>🇧🇷 Engenheiro de Sistemas de IA · Agentes Autônomos · Gateways & Observabilidade de LLMs · Planejamento Complexo</sub>

<br/><br/>

[![Website](https://img.shields.io/badge/Website-rafaelmoreira.com.br-0B0F14?style=flat-square&logo=google-chrome&logoColor=4FD1C5&labelColor=0B0F14)](https://rafaelmoreira.com.br)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rafael_Moreira_Lima-0B0F14?style=flat-square&logo=linkedin&logoColor=4FD1C5&labelColor=0B0F14)](https://www.linkedin.com/in/rrmlima)
[![GitHub](https://img.shields.io/badge/GitHub-rafaelmoreiraai-0B0F14?style=flat-square&logo=github&logoColor=4FD1C5&labelColor=0B0F14)](https://github.com/rafaelmoreiraai)
[![Email](https://img.shields.io/badge/Email-contato-0B0F14?style=flat-square&logo=gmail&logoColor=4FD1C5&labelColor=0B0F14)](mailto:contato@rafaelmoreira.com.br)

</div>

---

## ⚡ Core Focus & Architecture

| Area | What I Build & Research |
| :--- | :--- |
| **Autonomous Agent Systems** | Multi-agent coordination, deterministic execution harnesses, tool-calling routing, and self-healing loops (Hermes Agent, OpenCodex, Claude Code). |
| **LLM Gateways & Quota Control** | Multi-provider unified proxies, local credential bridging, fallbacks, token budgeting, and aggressive caching. |
| **LLM Observabilidade & Telemetry** | Real-time token telemetry, cache hit ratios, spend ledgers, and quota savings analytics across agent workloads. |
| **Planning & Industrial Systems** | Schedule analysis for capital projects: Primavera P6 (`.xer`), Earned Value Management (EVM), and DCMA 14-point health metrics. |

---

## 🛠️ Featured Open-Source Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>📊 <a href="https://github.com/rafaelmoreiraai/hermes-dag-monitor">hermes-dag-monitor</a></h3>
      <p><em>Visual token telemetry, cache hit rates, and quota savings dashboard for Hermes Agent & DAG-ULW pipelines.</em></p>
      <p>
        <img src="https://img.shields.io/badge/stack-Python_·_FastAPI_·_Telemetry-0B0F14?style=flat-square&color=4FD1C5" alt="stack"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🏗️ <a href="https://github.com/rafaelmoreiraai/PlanSight">PlanSight</a></h3>
      <p><em>Local analysis engine for Primavera P6 <code>.xer</code> enterprise schedules, heuristic container, and EVM/DCMA compliance reporting.</em></p>
      <p>
        <img src="https://img.shields.io/badge/stack-Python_·_Primavera_P6_·_EVM-0B0F14?style=flat-square&color=4FD1C5" alt="stack"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/rafaelmoreiraai/opencodex">opencodex</a></h3>
      <p><em>Universal provider proxy for OpenAI Codex & Claude Code — multi-model routing, prompt caching, and quota guard.</em></p>
      <p>
        <img src="https://img.shields.io/badge/stack-TypeScript_·_LLM_Proxy_·_Node-0B0F14?style=flat-square&color=4FD1C5" alt="stack"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🧠 <a href="https://github.com/rafaelmoreiraai/deepclaude-installer">deepclaude-installer</a></h3>
      <p><em>Claude Code harness backed by DeepSeek V4 Pro with CLI fallback, DuckDuckGo MCP tooling, and low-cost reasoning orchestration.</em></p>
      <p>
        <img src="https://img.shields.io/badge/stack-Shell_·_MCP_·_Claude_Code-0B0F14?style=flat-square&color=4FD1C5" alt="stack"/>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔌 <a href="https://github.com/rafaelmoreiraai/hermes-commandcode">hermes-commandcode</a></h3>
      <p><em>Command Code provider plugin for Hermes Agent — credential import, catalog discovery, and token-managed transport.</em></p>
      <p>
        <img src="https://img.shields.io/badge/stack-Python_·_Hermes_Plugin-0B0F14?style=flat-square&color=4FD1C5" alt="stack"/>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🤖 <a href="https://github.com/rafaelmoreiraai/customer-agent-installer">customer-agent-installer</a></h3>
      <p><em>Guided bootstrap for deploying and onboarding autonomous customer-service agents into production environments.</em></p>
      <p>
        <img src="https://img.shields.io/badge/stack-Automation_·_Deploy_·_Agents-0B0F14?style=flat-square&color=4FD1C5" alt="stack"/>
      </p>
    </td>
  </tr>
</table>

---

## 📐 How I Design Agent Infrastructure

```mermaid
flowchart LR
    Task["🎯 Task Definition"] --> Planner["🧠 DAG Planner & State"]
    Planner --> Agent["🤖 Autonomous Agent"]
    Agent --> Tools["🔧 MCP & Tool Registry"]
    Agent --> Gateway["⚡ LLM Proxy & Router"]
    Gateway --> Frontier["🌐 Frontier Models"]
    Gateway --> Local["💻 Local / Compact Models"]
    Gateway -. "metrics & trace" .-> Telemetry["📈 Telemetry & Cache Hit"]
    Telemetry -. "feedback" .-> Planner
```

> *"Every agent call must be traceable, every token accounted for, and every plan inspectable."*

---

## 💻 Tech Stack & Tooling

```
Languages       Python · TypeScript · SQL · Shell / Bash · Go
AI & Agents     Hermes Agent · OpenCodex · Claude Code · MCP (Model Context Protocol) · Function Calling
Architecture    DAG Orchestration · Prompt Caching · LLM Gateways · Token Economics · Telemetry
Infra & Ops     Docker · Linux (Debian/Ubuntu) · Cloudflare · HestiaCP · Tailscale Mesh
Domain Eng      Primavera P6 (.xer parser) · Earned Value Management (EVM) · DCMA 14-Point
```

---

<div align="center">
<sub>Built with precision · <a href="https://rafaelmoreira.com.br">Rafael Moreira Lima</a> · São Paulo, Brasil</sub>
</div>
