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

[Create New Term](https://github.com/aviarytech/tev2-test/wiki/new) with the following template

```md
# Title
>_The title at the top of this page ^^^ should be the term you are defining. Avoid capitalization unless necessary. If the term has an acronym or short form, provide the full form first, followed by the short form in parentheses._

## Definition
>_Begin with a concise explanation of the term. The initial sentence will serve as hovertext for hyperlinks, so keep it succinct. Expand on the definition as needed, clarifying how to distinguish instances of the concept, addressing common misconceptions, and linking to other definitions in the glossary when a term is synonymous with an already defined term._

## Usage Examples
>_Though optional, it's recommended to include one or more brief excerpts or links illustrating how the term is employed within the relevant community. Sources could range from specifications, github issues, to whitepapers._

## Tags
>_Include any relevant hash tags in a single line that could help in categorizing or grouping_ 
```


To install dependencies:

```bash
bun install
```

To run the TEv2 workflow:

```bash
bun run build
```

