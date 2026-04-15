# AGENTS.md

## Cursor Cloud specific instructions

This is a minimal test/scaffold repository containing only a `ReadMe.MD`. There is no application source code, build system, package manager config, or test framework.

### Available tools
- **Python 3** and **Node.js** are available in the environment and can be used for ad-hoc verification (e.g. `python3 -m http.server 19999`).
- **Git** is configured and ready.

### Running a verification server
To confirm the environment is functional, start a simple HTTP server:
```
python3 -m http.server 19999
```
Then verify with `curl http://localhost:19999/ReadMe.MD`.

### Notes
- No dependencies to install — the update script is a no-op (`echo 'No dependencies to install'`).
- No lint, test, or build commands exist in this repository.
