# Slipstream Marketplace

This repo contains the marketplace metadata for
[Flutter Slipstream](https://github.com/devoncarew/flutter-slipstream) — a
plugin that makes AI coding agents more effective for Dart and Flutter projects.

Flutter Slipstream is available as:

- a [Claude Code](https://claude.ai/code) plugin
- a [GitHub Copilot](https://github.com/features/copilot) plugin
- a [Gemini CLI](https://geminicli.com/) extension

## What is Flutter Slipstream?

Slipstream addresses two structural problems AI agents face with Flutter
development:

- **No runtime visibility** — agents can't see what's on screen; Slipstream lets
  agents launch the app, take screenshots, inspect the widget tree, evaluate
  Dart expressions, and interact with the UI.
- **Stale package knowledge** — agents rely on training data with a cutoff date;
  Slipstream retrieves accurate, version-matched API signatures directly from
  the local pub cache.

## Installation

**Claude Code:**

```sh
claude plugin marketplace add devoncarew/slipstream
claude plugin install flutter-slipstream@slipstream
```

**GitHub Copilot:**

```sh
copilot plugin install devoncarew/flutter-slipstream
```

**Gemini CLI:**

```sh
gemini extensions install https://github.com/devoncarew/flutter-slipstream
```

## Links

- Plugin source:
  [devoncarew/flutter-slipstream](https://github.com/devoncarew/flutter-slipstream)
- `package:slipstream_agent` on
  [pub.dev](https://pub.dev/packages/slipstream_agent)
