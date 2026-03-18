# Dan Novak — Provider of Clarity

I specialize in **eLearning systems architecture** and **legacy system rescue** — the projects where documentation is incomplete, vendors have departed, and the system is critical but fragile. Over 28 years, I've built SCORM/xAPI platforms, debugged multi-vendor integration nightmares, and applied NTSB investigative methodology to software forensics.

When conventional debugging fails, I bring the unconventional: Swiss cheese model failure analysis, SCORM API emulation for testing, and cross-domain middleware that shipped 5 years before commercial alternatives.

> "If you want to cheat, cheat fair."
> — Moe Howard, *Healthy, Wealthy and Dumb* (1938)

**Core technologies:** JavaScript (Vue.js, React), HTML5/CSS3, WCAG 2.1 AA accessibility, cross-platform integration, forensic debugging, SCORM 1.2/2004, xAPI (Tin Can API), AICC, cmi5.

**Approach:** NTSB-style root cause analysis applied to software. When a system fails, I don't just fix the symptom — I map the contributing factors, analyze the Swiss cheese alignment, and recommend systemic improvements.

---

## Featured Work

### SCORM Debugger — TASBot for eLearning

Vue.js wrapper with SCORM API emulation providing emulator save-state functionality for eLearning QA — save course state at any point, restore instantly, edit SCORM values directly, jump to any section. Reduced testing cycles from hours to minutes for gated content. Addresses a gap in commercial SCORM tools: reproducible debug states and session state inspection aren't first-class features anywhere else.

→ [Read the full case study](https://pattern158.solutions/exhibits/exhibit-m.html)

### Cross-Domain SCORM Framework (CSBB Dispatch)

Cross-domain content delivery architecture built in 2011 — five years before Rustici released Content Controller to solve the same problem. Lightweight stub packages deployed to client LMS platforms; actual content served from central servers. Transparent SCORM/AICC protocol translation layer. Served ~20 energy utility clients drawing from a ~2,000 course library, 10+ years in production.

→ [Read the full case study](https://pattern158.solutions/exhibits/exhibit-e.html)

### General Motors Investigation — NTSB Forensics for Software

Investigated a 19% course incompletion rate (4x baseline) initially framed as a tracking bug. Multi-angle investigation revealed five concurrent systemic failures: memory cache vulnerability with no auto-save, a "Congratulations You Failed" UX pattern, confusing navigation, mobile workforce on poor WiFi, and short-burst usage conflicting with hour-long desktop design. Platform was eventually abandoned — indirect validation of findings.

→ [Read the full case study](https://pattern158.solutions/exhibits/exhibit-j.html)

### BP Learning Platform — Reverse-Engineering Undocumented Systems

Contributed to an existing React/GraphQL platform acting as a federated facade over Rustici Content Controller, PeopleFluent LMS, Watershed LRS, and Amazon Cognito. Primary work: large-scale multi-tenant rebranding navigating an undocumented Material UI theming system — scoped as one week, expanded to months as interrelated style dependencies emerged. Also: bug fixes, Cognito troubleshooting via log analysis, reverse-engineering Watershed LRS queries.

→ [Read the full case study](https://pattern158.solutions/exhibits/exhibit-n.html)

---

## Currently

**Open to opportunities** in eLearning systems architecture, legacy platform rescue, or technical investigation roles. Especially interested in projects where the documentation is missing and the stakes are high.

**Website:** [pattern158.solutions](https://pattern158.solutions)
**LinkedIn:** [linkedin.com/in/pattern158](https://linkedin.com/in/pattern158)

---

*Built with AI-assisted development (Claude Code) — tools that make complex work precise. If you want to cheat, cheat fair.*
