# Antigrav Tools — Claude plugin marketplace

Free tools from [Antigravity Analytics](https://antigrav.si), packaged as a Claude plugin marketplace.

## Install

In Claude Code or Cowork:

```text
/plugin marketplace add Antigravity-Analytics/antigrav-tools
/plugin install mise-tools@antigrav-tools
```

## What's inside

**mise-tools** — free Mise kitchen back-office checks:

- **Invoice check** — work through a supplier invoice line by line against what was ordered and delivered
- **Panic-spend estimate** — estimate what emergency top-up buying is costing
- **Pack unit cost** — calculate the unit cost of an ingredient from its pack price and size

Mise is Product 01 from Antigravity Analytics, the back office for restaurant kitchens: https://antigrav.si/mise

Honest stage note: the Mise MCP server is not yet hosted on a public endpoint, so this plugin currently ships the skill (the workflows, the inputs to gather, and how to read the results). The live MCP connection is added here the day the server is hosted. Mise pricing is discussed on a call only; nothing is sold through this plugin.

Privacy: https://antigrav.si/mise-plugin-privacy.html
Terms: https://antigrav.si/mise-plugin-terms.html
Contact: hello@antigrav.si
