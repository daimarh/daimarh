<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=190&section=header&text=Daimar%20Hernandez&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=System%20Verification%20%E2%86%92%20SDET%20%E2%86%92%20AI%20Practitioner&descSize=18&descAlignY=58" alt="Daimar Hernandez banner" />
</p>

<p align="center">
  <a href="https://github.com/daimarh">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1200&color=36BCF7&center=true&vCenter=true&width=680&lines=15%2B+years+making+enterprise+software+trustworthy;From+testing+systems+to+building+AI+agents;LangGraph+%E2%80%A2+Claude+API+%E2%80%A2+MCP+%E2%80%A2+Playwright+%E2%80%A2+CI%2FCD" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/daimar-hernandez-se/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:d.hernandez.job@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Location-Research%20Triangle%2C%20NC-2c5364?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Open%20to-Remote%20%7C%20Hybrid-2ea44f?style=for-the-badge" alt="Open to remote or hybrid" />
</p>

---

## 👋 About me

I've spent 15+ years making commercial enterprise software trustworthy, first as a System Verification Tester at IBM, then as a Senior Software Engineer at HCLTech building test frameworks, and release quality for commercially shipped enterprise products.

Now I bring that same discipline to AI systems: agents that call real tools, follow business rules and are tested like production software, not demos.

* 🔭 Building agentic AI apps with LangGraph, Claude API and MCP
* 🧪 Testing LLM output the way I test APIs: assertions, edge cases, zero-escape goals
* 🌱 Learning: RAG patterns, LLM evaluation, cloud-native deployment
* 💬 Ask me about: test strategy, CI/CD speed-ups, root-causing hard defects

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🤖 Support Agent: LangGraph + MCP
**Multi-agent ticket resolution**

A 5-node LangGraph `StateGraph` (triage → context → resolver → escalation → finalizer) that resolves support tickets end to end. Business rules live in the graph's topology, not just the prompt.

- ✅ **60%** auto-resolved at a 0.7 confidence threshold
- 🛡️ Capped at 8 node-visits to guarantee termination
- 🧪 **16 passing tests**

<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" /> <img src="https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white" /> <img src="https://img.shields.io/badge/MCP-000000?style=flat-square" /> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />

</td>
<td width="50%" valign="top">

### 🎫 support-agent-mcp
**AI "Resolve with AI" for support desks**

Agents click **Resolve with AI** and Claude calls 4 MCP tools (`get_ticket`, `lookup_customer`, `check_inventory`, `update_ticket_status`). It returns a drafted customer reply plus a step-by-step reasoning trace in one round trip.

- 🌐 Next.js 14 on Vercel → FastAPI on Railway
- 🔐 Supabase Auth (JWT) + Postgres with RLS
- 🧰 TypeScript MCP server over stdio JSON-RPC

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" /> <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" />

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💬 Natural-Language-to-SQL
**Ask your database in plain English**

A full-stack app that turns plain English into executable SQL via the Claude API, with generated SQL checked for correctness and result accuracy.

- 🧩 4 integrated services: Next.js, FastAPI, Supabase Postgres, Supabase Auth
- 🧪 Playwright end-to-end + pytest API suites
- 🎯 **Zero defect escapes** across 12 build iterations

<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" /> <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" /> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />

</td>
<td width="50%" valign="top">

### 🔁 cicd-flask-lab
**Spec-driven CI/CD, end to end**

Every pipeline stage is owned by a declarative spec file. The code must conform to the spec, not the other way around.

- 🧱 lint → test (**≥80% coverage gate**) → SAST → build → **Trivy CVE gate** → deploy → verify
- 🔒 Security: bandit, pip-audit, gitleaks
- ☸️ Terraform, Helm, Minikube, Prometheus

<img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white" /> <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" /> <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" /> <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />

</td>
</tr>
</table>

<details>
<summary><b>🧰 More: MCP Document Tools server</b></summary>
<br/>

A Python package that exposes document conversion and processing tools through an **MCP server**, so AI assistants can call them directly. Tools are typed Python functions with Pydantic `Field` descriptions for clean tool schemas.

</details>

---

## 🛠️ Skills dashboard

<table>
<tr><td><b>🤖 AI / LLM</b></td><td>
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
<img src="https://img.shields.io/badge/Claude%20API-D97757?style=flat-square&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/MCP-000000?style=flat-square" />
<img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Copilot-000000?style=flat-square&logo=githubcopilot&logoColor=white" />
</td></tr>
<tr><td><b>💻 Languages</b></td><td>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
</td></tr>
<tr><td><b>🧪 Testing</b></td><td>
<img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" />
<img src="https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white" />
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
<img src="https://img.shields.io/badge/Cucumber-23D96C?style=flat-square&logo=cucumber&logoColor=white" />
<img src="https://img.shields.io/badge/RestAssured-6DB33F?style=flat-square" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
<img src="https://img.shields.io/badge/TestNG-CD4436?style=flat-square" />
</td></tr>
<tr><td><b>🔁 CI/CD & DevOps</b></td><td>
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
<img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
<img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
</td></tr>
<tr><td><b>🌐 APIs & Web</b></td><td>
<img src="https://img.shields.io/badge/REST-005571?style=flat-square" />
<img src="https://img.shields.io/badge/gRPC-244C5A?style=flat-square" />
<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" />
<img src="https://img.shields.io/badge/JEE-007396?style=flat-square&logo=openjdk&logoColor=white" />
</td></tr>
<tr><td><b>🗄️ Data</b></td><td>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/SQL%20Server-CC2927?style=flat-square" />
</td></tr>
<tr><td><b>🤝 Practice</b></td><td>
<img src="https://img.shields.io/badge/Agile%20%2F%20Scrum-0052CC?style=flat-square&logo=jira&logoColor=white" />
<img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" />
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Mentoring-6f42c1?style=flat-square" />
</td></tr>
</table>

---

## 💡 How I work

> **"If it isn't tested, it isn't done, and that includes the AI."**

| Principle | In practice |
|---|---|
| 🎯 **Rules in structure, not hope** | Agent guardrails enforced by graph topology and hard caps, not only by prompts |
| 🧪 **Test the output, not just the code** | Assert generated SQL and LLM answers for correctness, like API contracts |
| ⚡ **Fast feedback wins** | Parallel pipelines and auto-ticketing so defects surface in minutes, not days |
| 🔍 **Find the real root cause** | Binary-search isolation + log correlation before any fix ships |

---

<p align="center">
  <b>Let's build AI that people can trust.</b><br/>
  <a href="https://www.linkedin.com/in/daimar-hernandez-se/">LinkedIn</a> · <a href="mailto:d.hernandez.job@gmail.com">Email</a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=110&section=footer" alt="footer" />
</p>

