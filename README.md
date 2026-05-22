# QA Debug Companion — Released VSIX

VS Code extension that holds Mocha on test failure with the browser alive so a QA can investigate live page state through GitHub Copilot, then decide **retry / mark-passed / give-up** — without re-running the suite from scratch.

Releases are published as `.vsix` assets on the [Releases page](https://github.com/korakiad/extension-selfhealing/releases).

## Install

1. Download `qa-debug-companion-<version>.vsix` from the latest release.
2. In VS Code: `Extensions` → `…` menu → **Install from VSIX…** → pick the file.

Or from the CLI:

```bash
code --install-extension qa-debug-companion-0.0.1.vsix
```

## Requirements

- VS Code `^1.120.0`
- Node `>= 18`
- GitHub Copilot Chat
- `@playwright/mcp` on PATH
