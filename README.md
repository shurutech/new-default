# Project Reboot – A new default

Welcome to **Project Reboot**, Shuru’s public exploration of structured AI adoption in software teams.

As generative AI reshapes development workflows, we asked ourselves: what does it take to move from isolated wins to organization-wide leverage?

## 🚀 Why This Project

We’re a 100+ member strong org. While some of our developers regularly use AI tools like Copilot, Claude, models from the GPT family, or Cursor, others remain hesitant. The uneven adoption prompted us to take action — not just internally, but out in the open.

**Project Reboot** is our initiative to:
- **Measure and understand** AI usage patterns across our teams.
- **Identify blockers** like tool friction, learning curves, and security constraints.
- **Design frameworks and nudges** that boost AI adoption through coaching, enablement, and experimentation.
- **Track code generation** and modality preferences (web UIs vs IDEs).
- **Share learnings publicly** to help other orgs avoid our mistakes and replicate our wins.

## 📊 First Milestone: The Internal Survey

Our kickoff began with a company-wide developer survey (55 engineers) to answer:

- How much code is generated with AI?
- What tools and modalities do people use?
- What purposes (test generation, debugging, etc.) does AI help with?
- What hinders broader adoption?

📄 [Read the full survey analysis →](https://github.com/shurutech/reboot/blob/main/analysis-report-for-internal-ai-survey.pdf)

### Key Findings
- **25–50%** of code is AI-generated for most developers.
- **Top Use Cases**: Writing test cases, explaining code, boilerplate generation.
- **Most Used Tools**: GPT-based web tools, GitHub Copilot, Claude.
- **Top Blockers**: Buggy output, preference for manual workflows, NDA/security concerns.
- **Tool Modalities**: Web chat tools edge out IDEs, but both are critical. VS Code dominates.

## 🧪 What’s Next

We’re now:
- Building instrumentation to track AI usage inside VS Code, Cursor, JetBrains, etc.
- Running proxy experiments to measure prompt, token, and model usage across providers.
- Establishing baselines and improvement metrics for AI-assisted productivity.

We’ll continue documenting:
- What worked.
- What didn’t.
- What we’re iterating next.

## 🤝 Join the Conversation

If you're experimenting with similar challenges — whether in a startup or a 1000-person org — we’d love to collaborate, exchange notes, or just geek out about AI workflows.

---

🔬 **This repo will contain:**
- 📑 Reports (like the [AI usage survey](./analysis-report-for-internal-ai-survey.pdf))
- 📊 Experiment results
- 🧰 Tooling code (proxy scripts, IDE plugins, dashboards)
- 📚 Playbooks & adoption frameworks

Stay tuned!

— Shuru Labs
