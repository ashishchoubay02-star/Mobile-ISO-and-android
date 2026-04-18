# Mobile-ISO-and-android

Local development repository for mobile automation work, based on the Appium XCUITest driver codebase.

## Overview

This project includes:

- iOS automation driver implementation (XCUITest/Appium based)
- driver commands and utilities under `lib/`
- unit and functional test suites under `test/`
- helper scripts under `scripts/`

> [!IMPORTANT]
> iOS/XCUITest execution requires macOS with Xcode and Apple developer tooling.

## Tech Stack

- Node.js (recommended version range from this repo: `^20.19.0 || ^22.12.0 || >=24.0.0`)
- npm `>=10`
- TypeScript
- Appium 3 compatible codebase

## Getting Started

```bash
npm install
npm run build
```

## Useful Commands

```bash
npm run build           # compile TypeScript
npm run dev             # watch mode build
npm run lint            # run eslint
npm test                # unit tests
npm run e2e-test        # functional tests
```

## Project Structure

```text
lib/        Source code (driver, commands, device helpers)
test/       Unit and functional tests
scripts/    Utility scripts for WDA/device workflows
docs/       Documentation site content
```

## Notes

- This repository is maintained for personal/team mobile automation workflows.
- Upstream Appium XCUITest docs are available at:
  https://appium.github.io/appium-xcuitest-driver

## License

Apache-2.0
