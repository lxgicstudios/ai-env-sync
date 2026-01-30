# ai-env-sync

[![npm version](https://img.shields.io/npm/v/ai-env-sync.svg)](https://www.npmjs.com/package/ai-env-sync)
[![npm downloads](https://img.shields.io/npm/dm/ai-env-sync.svg)](https://www.npmjs.com/package/ai-env-sync)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-env-sync)](https://github.com/lxgic-studios/ai-env-sync/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate .env.example from your .env files. Strips secrets, adds helpful comments.

## Install

```bash
npm install -g ai-env-sync
```

## Usage

```bash
npx ai-env-sync
# Reads .env, .env.local, etc. and generates .env.example

npx ai-env-sync ./my-project
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```
