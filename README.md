# Slipstream Marketplace

This repo contains the marketplace metadata for
[Flutter Slipstream](https://github.com/devoncarew/flutter-slipstream) — a
plugin that makes AI coding agents more effective for Dart and Flutter projects.

## Features

- **Live app inspection** — launch a Flutter app, take screenshots, inspect the
  widget tree, evaluate Dart expressions, and observe runtime errors, all from
  agent tool calls.
- **Tap, type, and scroll** — interact with the running app via semantics or
  widget finders; no test harness required.
- **Accurate package APIs** — retrieve any package's public API directly from
  the local pub cache as a compact Dart stub, version-matched and free of
  implementation noise.
- **Package validation hooks** — catch discontinued packages and outdated major
  versions before they land in `pubspec.yaml`.

## Installation

| Coding Agent   | Installing Slipstream                                                                                              |
| -------------- | ------------------------------------------------------------------------------------------------------------------ |
| Claude Code \* | `claude plugin marketplace add devoncarew/slipstream` <br> `claude plugin install flutter-slipstream@slipstream`   |
| GitHub Copilot | `copilot plugin marketplace add devoncarew/slipstream` <br> `copilot plugin install flutter-slipstream@slipstream` |
| Gemini CLI     | `gemini extensions install https://github.com/devoncarew/flutter-slipstream`                                       |

> [!NOTE]
> If you see a "Failed to install plugin ... No ED25519 host key is
> known for github.com ... Host key verification failed" error, see
> anthropics/claude-code/issues/26588 / anthropics/claude-code/issues/50725 for
> possible workarounds.
