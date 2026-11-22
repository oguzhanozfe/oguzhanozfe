# Oğuzhan Özdemir

I build mobile games and tools for the people who make them. As a technical product owner and AI engineer, I work across gameplay, player analytics, and AI-assisted production. **Ball Match** is available on the [App Store](https://apps.apple.com/app/id6760407545) and [Google Play](https://play.google.com/store/apps/details?id=com.woofygames.ballmatch).

[Portfolio](https://oguzhan-ozdemir.vercel.app/) · [Résumé](https://oguzhan-ozdemir.vercel.app/resume.html) · [LinkedIn](https://www.linkedin.com/in/oguzhanozfe/)

## Six projects to try

| Project | Give it | See what happens in the included example |
| --- | --- | --- |
| [Cutroom Coverage](https://github.com/oguzhanozfe/cutroom-coverage) | A shot list and tagged takes | Before the crew wraps, see which two of four product shots still need a pickup. |
| [Sprite Atlas Audit](https://github.com/oguzhanozfe/sprite-atlas-audit) | A texture size and sprite rectangles | See where two frames overlap and where an effect extends beyond the sheet. |
| [Jam Scope Solver](https://github.com/oguzhanozfe/jam-scope-solver) | Feature estimates, values, prerequisites and a time budget | Pick six features that fit a 22-hour game jam, including their dependencies. |
| [Vertical Frame Planner](https://github.com/oguzhanozfe/vertical-frame-planner) | Landscape shot dimensions and subject boxes | Preview a vertical crop and find the one shot out of three that needs reframing. |
| [Funnel Friction Map](https://github.com/oguzhanozfe/funnel-friction-map) | Player or customer counts at each step | Find the largest onboarding loss of 133 of 317 people between creating a workspace and inviting a teammate. |
| [Schema Change Lens](https://github.com/oguzhanozfe/schema-change-lens) | Two versions of a data contract | Spot three changes that could reject previously valid inputs, alongside three compatible changes. |

Each example runs with `python app.py`, without an account or API key. The app computes the result. A local chat model, Azure OpenAI, Amazon Bedrock or a compatible API can provide an optional second opinion. [Browse all 25 tools](https://github.com/search?q=user%3Aoguzhanozfe+topic%3Aai-demo-workbench&type=repositories)

<details>
<summary>More projects in AI, games and engineering</summary>

### AI work

**Evaluation and measurement**
- [agent-evals](https://github.com/oguzhanozfe/agent-evals): tool-calling agent evals with k runs, pass^k, flaky detection and CI regression diffs
- [cheapest-lane-bench](https://github.com/oguzhanozfe/cheapest-lane-bench): how cheap a model can be per chore before quality drops; local vs cloud cost/quality frontier
- [tr-extract-bench](https://github.com/oguzhanozfe/tr-extract-bench): Turkish business-document extraction benchmark (invoices, statements, disclosures) across local and cloud models
- [voice-latency-lab](https://github.com/oguzhanozfe/voice-latency-lab): where the time goes in a voice-agent turn (STT → LLM → TTS) and which streaming tricks help

**Agents**
- [voice-support-agent](https://github.com/oguzhanozfe/voice-support-agent): support agent you can type or talk to; framework-free tool loop, human handoff, measured on independent scenarios
- [customer-360-payments-lab](https://github.com/oguzhanozfe/customer-360-payments-lab): read-only SQL agent over a merged customer view, answers checked against fixed SQL
- [character-forge](https://github.com/oguzhanozfe/character-forge): agent-driven brief → game-ready 3D character pipeline with human approval gates

**Agent safety and infrastructure**
- [mcp-firewall](https://github.com/oguzhanozfe/mcp-firewall): MCP proxy with tool policy, secret redaction and measured prompt-injection detection
- [claude-code-guardrails](https://github.com/oguzhanozfe/claude-code-guardrails): Claude Code hooks that block credential writes and destructive commands, with a measured false-positive rate
- [llm-offload](https://github.com/oguzhanozfe/llm-offload): routes bounded LLM chores to the cheapest lane with a credential guard and quota-aware fallback
- [fm-career-mcp](https://github.com/oguzhanozfe/fm-career-mcp) · [evidence-rag](https://github.com/oguzhanozfe/evidence-rag): MCP servers; local search that preserves evidence and detects source changes
- [local-workbench](https://github.com/oguzhanozfe/local-workbench): resumable Ollama document workflows with evidence checks

**Grounded LLM products for games**
- [review-miner](https://github.com/oguzhanozfe/review-miner): Steam reviews → product themes before/after a patch, every quote verified
- [community-pulse](https://github.com/oguzhanozfe/community-pulse): community topics and sentiment aligned with patch dates
- [gdd-copilot](https://github.com/oguzhanozfe/gdd-copilot): game design docs where every market claim cites a quoted source
- [ad-creative-lens](https://github.com/oguzhanozfe/ad-creative-lens): tags mobile game ad creatives and surfaces UA creative trends
- [store-listing-watch](https://github.com/oguzhanozfe/store-listing-watch): tracks store listings and explains what competitors changed

**Other applied**
- [kap-watcher](https://github.com/oguzhanozfe/kap-watcher): classifies and summarises Turkish KAP disclosures; every number checked against the source
- [deal-hunter](https://github.com/oguzhanozfe/deal-hunter): real deal vs fake discount from price history, plus a Turkish recommendation bot
- [paper-radar](https://github.com/oguzhanozfe/paper-radar): weekly arXiv digest ranked against an interest profile, measured against baselines
- [ai-visibility-lab](https://github.com/oguzhanozfe/ai-visibility-lab): do AI answer engines find and cite your pages?
- [n8n-job-search-copilot](https://github.com/oguzhanozfe/n8n-job-search-copilot): n8n + LLM inbox triage, daily brief and fit check
- [visual-workbench](https://github.com/oguzhanozfe/visual-workbench): LoRA training and image-to-video experiments on licensed data

Systems: [paxos-arena](https://github.com/oguzhanozfe/paxos-arena) (Multi-Paxos settlement log in Go)

</details>
