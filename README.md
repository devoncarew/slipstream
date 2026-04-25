# Slipstream Marketplace

This repo contains the marketplace metadata for
[Flutter Slipstream](https://github.com/devoncarew/flutter_slipstream) — a
plugin that makes AI coding agents more effective on Dart and Flutter projects.

Flutter Slipstream is available as a
[Claude Code](https://claude.ai/code) plugin and a
[GitHub Copilot](https://github.com/features/copilot) plugin.

## What is Flutter Slipstream?

Slipstream addresses two structural problems AI agents face with Flutter
development:

- **Stale package knowledge** — agents rely on training data with a cutoff
  date; Slipstream retrieves accurate, version-matched API signatures directly
  from the local pub cache.
- **No runtime visibility** — agents can't see what's on screen; Slipstream
  lets agents launch the app, take screenshots, inspect the widget tree,
  evaluate Dart expressions, and interact with the UI.

## Installation

**Claude Code:**

```sh
claude plugin install flutter-slipstream
```

**GitHub Copilot:**

```sh
copilot plugin install devoncarew/flutter-slipstream
```

## Links

- Plugin source: [devoncarew/flutter_slipstream](https://github.com/devoncarew/flutter_slipstream)
- `package:slipstream_agent` on [pub.dev](https://pub.dev/packages/slipstream_agent)
# slipstream
