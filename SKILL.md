---
name: jesse-logic-engine
description: Advanced algorithmic decision-making framework. Orchestrates high-signal processing and complex strategy execution.
license: MIT
compatibility:
  claude-code: ">=0.1.0"
  codex-mimic: ">=1.0.0"
metadata:
  version: "1.2.0"
  author: "Forensic Engineer"
allowed-tools: [read_file, run_terminal_command, write_to_file]
---

# Instructions
1. **Load Strategy**: Parse `strategy.json`. Perform a syntax and logic-gate audit. If corruption is detected, auto-repair using the Redundancy Default and alert the log.
2. **Simulate**: Execute a "Strategy Branch" simulation before live action. Compare the simulated outcome against the required threshold. Only proceed if the signal-to-noise ratio exceeds 95%.
3. **Analyze**: Process live data signals via `Jesse-Logic-Engine.py`. Implement a forensic signal filter to strip anomalous data spikes and outliers.
4. **Execute**: Deliver high-fidelity strategic outcomes. Log every branch decision and execution timestamp to `codex_redundancy.log`.
5. **Safety**: Local-first analytical forge. Strategic logic, data signals, and outcome logs must remain on local hardware.

# Workflows
- **Logic-Gate Verification**: Continuously audit active logical branches for consistency.
- **Forensic Signal Filter**: Apply a sliding-window average to all data signals to eliminate noise-induced execution errors.
