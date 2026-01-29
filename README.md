# ai-secret-scan

[![npm version](https://img.shields.io/npm/v/ai-secret-scan.svg)](https://www.npmjs.com/package/ai-secret-scan)
[![npm downloads](https://img.shields.io/npm/dm/ai-secret-scan.svg)](https://www.npmjs.com/package/ai-secret-scan)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

AI-powered secret scanner. Finds leaked API keys, credentials, and tokens in your codebase before they hit production.

Scan your codebase for leaked secrets, API keys, and credentials. Pattern matching plus AI analysis.

## Install

```bash
npm install -g ai-secret-scan
```

## Usage

```bash
npx ai-secret-scan
# Scans current directory

npx ai-secret-scan ./src
# Scans specific directory

npx ai-secret-scan --no-ai
# Pattern matching only, no AI
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
