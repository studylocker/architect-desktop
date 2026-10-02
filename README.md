# Architect desktop, early build

This repository hosts installers for an early, primitive build of the Architect desktop app. It is a standalone preview for trying the workbench, not the system we run inside Lectern. The source code is not published here.

## Download

Get the latest installer from [Releases](../../releases/latest):

- macOS, Apple silicon: `Architect-<version>-arm64.dmg`
- macOS, Intel: `Architect-<version>-x64.dmg`
- Windows: `Architect-Setup-<version>.exe`

The Mac builds are signed with a Developer ID and notarized by Apple. The Windows installer is not code signed yet, so SmartScreen may ask you to confirm before it runs.

## Requirements

- macOS 12 or later, or Windows 10 or later
- Python 3.12 and [uv](https://docs.astral.sh/uv/) on your PATH
- A model provider: a Claude or ChatGPT subscription, an API key, or a local model server

## Feedback

Open an issue in this repository.
