# TEv2-Test

[![Test TEv2 Workflow](https://github.com/aviarytech/tev2-test/actions/workflows/main.yml/badge.svg?branch=master)](https://github.com/aviarytech/tev2-test/actions/workflows/main.yml)

This repository contains a test workflow for the Terminology Engine v2. It relies on the following tools:

* @aviarytech/tev2-ingress
* @tno-terminology-design/mrgt-import
* @tno-terminology-design/mrgt
* @aviarytech/tev2-hrgt

To install dependencies:

```bash
bun install
```

To run:

```bash
bun tev2-ingress -c config.yaml
bun mrgt -s . -v latest
bun tev2-hrgt glossaries/*
```

