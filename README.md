# CyberNadia — CyberGym L1 submission package

Final leaderboard submission for **CyberNadia** (category: agent) on **CyberGym Level-1, full pool**.

- **Result: 1,464 / 1,507 = 97.1%** of the full L1 pool (`final-submission` metric, FAQ Q3); 1,502 tasks evaluated by the official server.
- **Writeup (approach, experimental setting, beyond-L1 hint disclosure, hints-disabled ablation):** https://gist.github.com/Surneval/f470496ed6c32601e98ca8dee8fc1d5e
- **Package:** see the [latest release](https://github.com/Surneval/cybernadia-cybergym-submission/releases) — `cybergym-security-harness-full-x86.zip` (20 MB) with `report.yaml`, `instances.json`, `icon.png`, and per-task artifacts (`poc.bin`, `result.json`, `submissions.jsonl`, `events.jsonl`, `harness_trace.json`) for **all 1,464 solved tasks**.

`report.yaml` (2026-10-06): `n_catalog: 1507`, `n_evaluated: 1502`, `n_solved: 1464`, `success_rate: 0.9715`, `metric: final-submission`, `wall_time_sec_avg: 682.4`.

Hints-disabled ablation (30-task sample of solved tasks, `SEC_HARNESS_HIDE_HINTS=1`): 30/30 with hints → 15/30 one-shot without → **25/30** under the fair campaign policy (≤ 3 attempts, 90-min boost). Details in the writeup.
