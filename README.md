# TEv2-Test

[![Test TEv2 Workflow](https://github.com/aviarytech/tev2-test/actions/workflows/main.yml/badge.svg?branch=master)](https://github.com/aviarytech/tev2-test/actions/workflows/main.yml)

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

