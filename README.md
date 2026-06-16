# ON-FTHB-GST

*description of the project*

**Timeframe** 2026-06-02 - 2026-09-08

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/fthb-gst](https://cra-test-arc.canada.ca/fthb-gst)

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

**Updated:**  2026-06-16

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Taxes)
    node3(GST/HST for businesses)
    node4(Claim a GST/HST rebate)
    node5(First-time home buyers’ #40;FTHB#41; GST/HST rebate)
    node6(GST/HST new housing rebate)
    node7(Excise and specialty taxes)
    node8(Underused Housing Tax)
    node9(Underused Housing Tax #40;UHT#41; multimedia toolkit)
    node10(Factsheet: The Underused Housing Tax #40;UHT#41; - What is it?)
    node1 --> node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node4 --> node6
    node2 --> node7
    node7 --> node8
    node8 --> node9
    node9 --> node10
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/services/taxes.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses/gst-hst-rebates.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses/gst-hst-rebates/first-time-home-buyers-gst-hst-rebate.html" _blank
    click node6 "https://www.canada.ca/en/revenue-agency/services/tax/businesses/topics/gst-hst-businesses/gst-hst-rebates/new-housing-rebate.html" _blank
    click node7 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies.html" _blank
    click node8 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/underused-housing-tax.html" _blank
    click node9 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/underused-housing-tax/underused-housing-tax-multimedia-toolkit.html" _blank
    click node10 "https://www.canada.ca/en/services/taxes/excise-taxes-duties-and-levies/underused-housing-tax/underused-housing-tax-multimedia-toolkit/factsheet-uht-what-is-it.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node5,node6,node10 inscope
```
