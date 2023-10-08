# TEv2-Test

[![Test TEv2 Workflow](https://github.com/aviarytech/tev2-test/actions/workflows/main.yml/badge.svg?branch=master)](https://github.com/aviarytech/tev2-test/actions/workflows/main.yml)

This repository contains a test workflow for the Terminology Engine v2. It relies on the following tools:

* [@aviarytech/tev2-ingress](https://github.com/aviarytech/tev2-ingress)
* [@tno-terminology-design/mrg-import](https://github.com/tno-terminology-design/mrg-import)
* [@tno-terminology-design/mrgt](https://github.com/tno-terminology-design/mrgt)
* [@aviarytech/tev2-hrgt](https://github.com/aviarytech/tev2-hrgt)

It does not yet incorporate

* [@tno-terminology-design/trrt](https://github.com/tno-terminology-design/trrt)

The [Wiki](https://github.com/aviarytech/tev2-test/wiki) of this repository contains the glossary being used for testing.

[Create New Term] (https://github.com/aviarytech/tev2-test/wiki/new?template=new-term.md&title=%5BTERM%5D+%3Cword+or+phrase+you+are+adding%3E)


To install dependencies:

```bash
bun install
```

To run the TEv2 workflow:

```bash
bun run build
```

