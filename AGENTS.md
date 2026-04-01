# AGENTS.md

## Cursor Cloud specific instructions

This is a minimal test/scaffold repository containing only a `ReadMe.MD`. There is no application source code, build system, linter, test framework, or package manager configuration.

### Running the application

The repository's "application" is a Python 3 static file server used for development verification:

```
python3 -m http.server 19999
```

This serves files from the workspace root on port 19999. Verify with `curl http://localhost:19999/`.

### Key notes

- **No dependencies to install**: There is no `package.json`, `requirements.txt`, or other dependency manifest on the `main` branch.
- **No lint/test/build commands**: The repository has no linter, test runner, or build step.
- **Python 3 and Node.js** are available in the environment but are not project dependencies.
