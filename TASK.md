# Fork Strategy Architectural Analysis

We have forked 16+ major open-source projects (totaling ~1.1M stars) under SuperInstance on GitHub, each enhanced with mathematical tools from our arsenal:

**Our math crates:**
- conservation-checker: one-sided conservation laws, phase detection
- cathedral-probe: spectral graph analysis (Fiedler, Cheeger, communities, resistance)
- crackle-runtime: information theory (KL, JSD, transfer entropy, mutual information)
- negative-space-testing: topological test coverage (Betti numbers, simplicial complexes)
- cocapn-core: device tiers, deadband, escalation, handoff

**Our forks (parent → stars):**
- ollama/ollama → 172K — intelligence monitor (JSD redundancy, Pareto frontier)
- langgenius/dify → 143K — budget watchdog (per-workflow budgets, auto-downgrade)
- tauri-apps/tauri → 107K — offline guardian (deadband, tier escalation, handoff)
- open-webui/open-webui → 100K+ — budget guardian (per-user budgets, admin dashboard)
- denoland/deno → 103K — resource guardian (CPU/memory/network/file budgets)
- openai/codex → 87K — budget guard (token conservation)
- astral-sh/uv → 85K — cache guardian (KL eviction, CI optimization)
- foundry-rs/foundry → 85K — gas guardian (Ethereum gas budgets)
- Aider-AI/aider → 45K — budget enforcer (model downgrade suggestions)
- zed-industries/zed → 57K — spectral analysis (code dependency graphs)
- lapce/lapce → 35K — coverage gap finder (Betti numbers on test coverage)
- meilisearch/meilisearch → 57K — relevance intelligence (query graph spectral analysis)
- tokio-rs/tokio → 29K — task intelligence (JSD, transfer entropy on async tasks)
- typst/typst → 38K — resource guardian (compilation budgets)
- ratatui/ratatui → 20K — spectral widgets (terminal graph visualization)
- surrealdb/surrealdb → 32K — queued

Write a 4000+ word architectural analysis document called ARCHITECTURE.md analyzing:
1. The PATTERN across all forks — what's the common thread? (conservation + phase detection is the universal solvent)
2. Which integrations are GENUINELY novel vs which are "nice to have"?
3. The adoption strategy: what makes a fork actually get used vs ignored?
4. Technical depth: which forks have the deepest integration (touching core code) vs shallowest (bolt-on)?
5. The mathematical backbone: why spectral methods + information theory + conservation laws are the RIGHT math for this moment in software
6. Risks: what could go wrong? (maintenance burden, upstream sync, credibility)
7. Next wave recommendations: which repos should we target next and why?

Be honest. Be technical. No fluff. This is for internal strategy, not marketing.
