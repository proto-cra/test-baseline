# test-baseline COP

*description of the COP*

**COP timeframe** 2026-02-10 - 2026-05-19

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://proto-cra.github.io/test-baseline](https://proto-cra.github.io/test-baseline)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-02-24

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Sign in to your CRA account)
    node1 --x node2
    node2 --> node3
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node3 inscope
```
