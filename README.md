# Frontier AI Risk Prioritization — Board Briefing

An interactive, single-file dashboard examining how frontier AI is accelerating cyber risk, and what that means for remediation strategy, control priorities, and board oversight.

It is built as one self-contained `index.html` (React via CDN) — no build step. Open the file in any modern browser, or view it live via GitHub Pages if enabled for this repository.

## Contents

The briefing is organised as a framing section plus five parts:

- **The Challenge** — as attacks accelerate, does patching faster still reduce risk?
- **Part I · The Current Threat Landscape** — the rise in disclosed vulnerabilities, and how remediation pace compares with standards (Standard / PCI DSS / CISA BOD 26-04).
- **Part II · AI Acceleration of Cyber Threats** — the frontier models driving it (cyber-relevant capability over time, and why pre-release gating has limited reach when competitive models are open-weight and low-cost), threat-actor speed, the disclosure-to-patch exposure window, and the rise of zero-days.
- **Part III · Risk Management Implications** — shifting control priorities, the change-freeze trade-off, and a zero-vulnerability gate.
- **Part IV · Governing Internal AI** — the institution's own AI use as a control domain: model risk management, AI governance frameworks, and controls over internally-deployed models, agents, and data pipelines.
- **Part V · Questions to Drive Risk Reduction** — open questions to assess readiness with evidence.

## Data & sources

Figures are based on **publicly available information and industry estimates — not internal data from any single institution.** Charts draw on the public NVD / CVE Program record, Mandiant / Google Threat Intelligence (M-Trends), Google GTIG zero-day reporting, and published standards and guidance — PCI DSS, FFIEC, CISA Binding Operational Directives (19-02, 22-01, 26-04), and AI-governance frameworks (NIST AI RMF, ISO/IEC 42001, the EU AI Act, model-risk-management guidance Fed SR 11-7 / SR 26-2, and the OWASP Top 10 for LLM Applications). Projected years are labelled as such and represent trend extrapolation, not forecasts. The frontier-model capability/availability chart draws on public reporting on GLM-5.2 (Z.ai / Zhipu AI), Anthropic's Mythos, and OpenAI's GPT-5.6; capability is a directional estimate, not a benchmark score.

This is an illustrative, directional briefing intended to support discussion. It is not security advice for any specific organisation.

## Usage

Open `index.html` in a browser. To print or save as PDF, use the **Download PDF** button (or your browser's print dialog) — the print stylesheet paginates each part and includes all content.
