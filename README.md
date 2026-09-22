# AI Agent Landscape 2026

**A verified, independently researched census of named AI agent products** across major technology vendors — what exists, who built it, and who can actually use it.

🔗 **Live report:** [cypqa.github.io/ai-agent-landscape-2026](https://cypqa.github.io/ai-agent-landscape-2026/)

---

## What This Is

This report maps every named, deployable AI agent product from major vendors as of **September 2026** — drawing a clear line between:

- ✅ **Counted**: Named agent products end-users or enterprises can actually deploy (e.g., *Microsoft Copilot Researcher*, *Salesforce Piper*, *Google Jules*)
- ❌ **Excluded**: Agent-building platforms (Copilot Studio, Bedrock Agents, Agentforce Builder), unnamed "custom agents," raw API capabilities, and deprecated products

> **Definition used**: An AI agent independently or semi-independently performs multi-step tasks using tools, browsing, code execution, or cross-application action — beyond single-turn chat or document Q&A.

---

## Key Findings (v2.0 — September 22, 2026)

| Company | Public Agents | Enterprise/Preview Agents | Total Named |
|---|---|---|---|
| **Microsoft** | 8 | 7 | **15** |
| **Google** | 5 | 4 | **9** |
| **Salesforce** | 6 | 1 (pilot) | **7** |
| **OpenAI** | 3 | 2 | **5** |
| **ServiceNow** | 1 | 4 | **5** |
| **SAP** | 0 | 4 | **4** |
| **IBM** | 1 | 3 | **4** |
| **Anthropic** | 1 suite (SMB) | 2 | **3+** |
| **Workday** | 0 | 3 | **3** |
| **Oracle** | 0 | 3 | **3** |
| **Others** | varies | varies | ~7 |
| **TOTAL** | **~14 public** | **~47 enterprise** | **~61–85** |

- 📦 **~14** publicly available named agent products
- 🏢 **~47** enterprise / preview deployments
- ⚠️ **3** deprecated products tracked separately
- 🧱 **12+** major agent-building frameworks (excluded from count)

---

## What's New in v3.0 (Final Run)

**v2.0 corrections** (five material fixes from v1):
1. OpenAI: *ChatGPT Agent Mode* deprecated; *ChatGPT Work* + *Workspace Agents* added
2. Anthropic: *Claude for Small Business* added (May 2026)
3. Salesforce: Corrected 11 → 7 named Agentforce 360 agents
4. Microsoft: *Copilot Tasks* + *Copilot Cowork* added — total 15
5. Google: *NotebookLM* renamed to *Gemini Notebook* (Jul 16, 2026)

**v3.0 corrections** (four additional findings from final verification run):
1. **Google AlphaEvolve added** — GA on Google Cloud July 2026; evolutionary code optimization agent (previously omitted)
2. **OpenAI ChatGPT for Financial Services added** — launched Sep 10, 2026; enterprise agent for Wall Street analysts (previously omitted)
3. **ServiceNow expanded** — 3 additional named AI Specialists confirmed at Knowledge 2026: AIOps Specialist, SRE Specialist, L1 IT Service Desk Specialist (previously undercounted)
4. **Gemini Spark** upgraded from Preview → Public (expanded to AI Pro in 160+ countries Jul 30, 2026)

---

## Methodology

**What qualifies as an agent:**
- Independently performs multi-step tasks (not just Q&A)
- Has a distinct product name (not "custom agent" or unnamed)
- Is actually deployable — not a framework, API, or prototype
- Active as of research cutoff (deprecated products tracked separately)

**Sources used**: Official product pages, vendor press releases, enterprise documentation, and verified news coverage. All 29 sources linked in the report.

**Research cutoff**: September 22, 2026  
**Report version**: 3.0 (Final)

---

## File Structure

```
/
├── index.html      ← Full interactive report (self-contained, no dependencies)
└── README.md       ← This file
```

The HTML report is fully self-contained — all fonts, styles, and data are inline. No build step or server required.

---

## Limitations & Honest Caveats

- Enterprise agent counts rely on vendor documentation which can be inconsistent
- "Named" agents are counted conservatively — ambiguous cases excluded
- The landscape changes weekly; some figures may already be outdated
- Agent-building platforms (which can create unlimited custom agents) are explicitly excluded
- Anthropic's financial services agents (Bridgewater, Deloitte implementations) are third-party; excluded

---

## License

Research and report content: **CC BY 4.0** — free to share and adapt with attribution.

**Citation:**
> *AI Agent Landscape 2026, v3.0* — CY (cypqa0@gmail.com), September 2026.  
> Live at: https://cypqa.github.io/ai-agent-landscape-2026/

---

*Feedback, corrections, or additions welcome — open an issue or reach out directly.*
