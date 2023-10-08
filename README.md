# TEv2-Test

[![Test TEv2 Workflow](https://github.com/aviarytech/tev2-test/actions/workflows/main.yml/badge.svg?branch=master)](https://github.com/aviarytech/tev2-test/actions/workflows/main.yml)

This repository contains a test workflow for the Terminology Engine v2. It relies on the following tools:

* [@aviarytech/tev2-ingress](https://github.com/aviarytech/tev2-ingress)
* [@tno-terminology-design/mrg-import](https://github.com/tno-terminology-design/mrg-import)
* [@tno-terminology-design/mrgt](https://github.com/tno-terminology-design/mrgt)
* [@aviarytech/tev2-hrgt](https://github.com/aviarytech/tev2-hrgt)

It does not yet incorporate

* [@tno-terminology-design/trrt](https://github.com/tno-terminology-design/trrt)


To install dependencies:

```bash
bun install
```

To run the TEv2 workflow:

```bash
bun run build
```

