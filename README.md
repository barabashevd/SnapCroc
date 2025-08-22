# Croc Android GUI
Android app (Jetpack Compose) that wraps the `croc` CLI as a subprocess.
- Approach: bundle per-ABI `croc` binary, run via ProcessBuilder.
- Min SDK 24, target latest.
## Modules
- app — UI + foreground service + SAF
- (later) crocbridge — process manager + parsing
## Dev quick start
See /docs/dev-setup.md
