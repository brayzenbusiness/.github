# Brayzen For Business

**Brayzen For Business** is the planned business product line under the Brayzen master
brand.

Brayzen helps people understand where their money goes. This org exists for the business
side of that promise — the product line being shaped for companies once discovery earns
it. It is **planned**, not launched: scope, order, and claims are set by discovery
(customer problems, decision-makers, permissions, proof), not by enthusiasm.

## What lives here

| Repo | Status |
| ---- | ------ |
| [`api`](https://github.com/brayzenbusiness/api) | v0 multi-tenant organizational foundation — organizations, members, RBAC, invitations, API keys, audit. Private; internal service boundary. |
| [`dev`](https://github.com/brayzenbusiness/dev) | Development sandbox — spikes and scratch, nothing production. |
| `.github` | This repo — org profile and future org-wide conventions. |

## Ground rules

- Private by default — this is a business product line under active discovery.
- No launch claims until discovery produces design partners and the roadmap gates pass.
- The consumer Brayzen platform lives in the separate `brayzenco` org; data, deploys,
  and blast radius do not cross the boundary.
- Money, when it arrives, is integer kobo/subunit; mutations are audit-logged; secrets
  are hashed at rest and shown exactly once.

## Status

Discovery-stage. See the consumer workspace (`ops/gtm/strategy.md`,
`ops/product/roadmap.md`) for the product-line plan.
