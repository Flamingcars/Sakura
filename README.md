# Sakura

Loader with triggerbot, silent aim and macro. Distributed here as `x.exe`.

## Auto-update

Whoever runs the exe is kept up to date automatically: at startup it pulls
`x.exe` from this repo and, when its bytes differ from the running copy,
swaps itself over to it and restarts. No manual downloading.

## Publishing an update

Build Release / x64 locally, copy the built exe to this repo root as
`x.exe`, commit and push. Running copies fetch it on their next start.
