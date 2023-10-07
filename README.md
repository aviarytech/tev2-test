# tev2-test

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

This project was created using `bun init` in bun v1.0.2. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.
