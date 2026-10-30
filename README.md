# delu-host-refreeze

Private scratch repository for CP-17c of the DE-LU day-ahead forecasting project: A1 re-frozen under the issuing
host that r19 §24.13 pins (Pyodide 0.28.0 in the official Node.js v26.7.0 darwin-arm64 binary), shown on GitHub-hosted
`macos-26` runners.

It holds only what the runs need: the candidate's code and the files its freeze manifest verifies, the harness
(`src/cp17c/`), the workflow, the pinned Pyodide files, A1's search state, the freeze-origin states, the canary's
payload, and development payloads and states for delivery days through 2026-09-06. `inputs-files.json` lists every
file's SHA-256, and each job checks them before it runs.

It creates no secret and no variable, and is never made public. Deleting it is the Owner's decision.
