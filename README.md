# Sakura

Loader with triggerbot, silent aim and macro. Distributed here as `x.exe`.

## Auto-update

Whoever runs the exe is kept up to date automatically: at startup it checks
the `VERSION` file in this repo and, when it is newer than the running copy,
downloads `x.exe`, swaps itself over to it and restarts. No manual downloads.

## Publishing an update

Build Release / x64 locally, bump `kAppVersion`, copy the built exe to this
repo root as `x.exe`, set `VERSION` to the same string, commit and push.
