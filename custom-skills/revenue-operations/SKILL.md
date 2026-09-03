---
name: revenue-operations
description: "Prioritize existing assets by shortest credible path to legitimate revenue, remove revenue blockers, verify execution, and measure actual economic outcomes."
auto-activate: true
---

# Revenue Operations

Use this skill when deciding what business work to perform, what to prioritize, or whether a technical task is worth doing.

## Objective

Convert existing assets into legitimate, measurable revenue while controlling cost and preserving operating runway.

## Required context

Before selecting a major revenue objective, read:

`/root/automaton-context/VPS_MASTER_REPORT.md`

If available, also read:

`/root/automaton-context/VPS_VERIFIED_STATE.md`

Prefer verified live state over stale historical claims.

## Core rule

Ask:

**What is preventing money from being received right now?**

Work on the highest-value constraint that can be removed safely with available resources.

## Revenue definition

Count as revenue only:

- money actually received
- a verified paid transaction
- a legitimate enforceable receivable from a real customer

Do not count as revenue:

- leads
- impressions
- clicks
- traffic
- code commits
- deployments
- plans
- proposals
- unfinished checkouts
- generated content

Those can be intermediate metrics only.

## Opportunity scoring

Before starting a substantial project, score candidate opportunities from 1–5 on:

1. readiness to sell now
2. speed to first cash
3. gross-margin potential
4. existing proof/assets
5. existing distribution
6. low technical blocker count
7. low creator-intervention requirement
8. recurring-revenue potential
9. low delivery cost
10. probability of closing a real buyer

Prefer the opportunity with the strongest near-term expected return unless the creator explicitly overrides the priority.

## Existing-assets-first order

1. Sell an existing ready asset.
2. Repair a blocker preventing an existing asset from being sold.
3. Combine existing assets into a sellable offer.
4. Improve an already revenue-producing system.
5. Build a new asset only when evidence justifies it.

## Work contract

For each substantial task record:

- revenue objective
- selected opportunity
- blocker being removed
- responsible worker/specialist
- expected evidence of completion
- expected cost
- actual cost when measurable
- result
- next decision

## Delegation

Delegate to specialized workers when useful.

Separate planning, execution, and evaluation for consequential work when practical.

Do not allow a worker to certify its own important output solely by assertion.

## Verification

Examples of acceptable evidence:

- successful test output
- live URL response
- API receipt
- published post ID
- provider job ID and completed artifact
- deployed service health check
- payment receipt
- customer confirmation
- analytics event tied to a real funnel step

If verification fails, route the defect back to the specialist responsible for that failure class.

## Stop conditions

Stop or deprioritize work when:

- it no longer has a credible path to revenue
- cost rises materially above expected value
- a higher-value opportunity becomes clearly available
- repeated verified failures show the current approach is unlikely to work
- the task is expanding into unrelated infrastructure work

Record why it was stopped.

## Cost discipline

Prefer the least expensive capable model/provider/tool for the task.

Do not spend scarce inference or infrastructure budget on speculative work while a direct revenue blocker remains unresolved.

When survival resources are low:

1. stop speculative work
2. defer long-horizon improvements
3. select the shortest credible path to cash
4. use cheaper capable inference
5. preserve minimum operational reserve

## First-run procedure

On first activation:

1. Read `VPS_MASTER_REPORT.md`.
2. Verify live infrastructure and product state.
3. Write `/root/automaton-context/VPS_VERIFIED_STATE.md`.
4. List near-ready revenue opportunities.
5. Score them.
6. Select exactly one primary revenue objective.
7. Identify the immediate revenue blocker.
8. Create the smallest plan that can remove that blocker.
9. Execute/delegate.
10. Verify externally.
11. Attempt the revenue-producing action.
12. Measure the result.
13. Learn and repeat.

## Reporting format

Keep the creator's executive update compact:

- Primary revenue objective
- Current blocker
- Action completed
- Evidence
- Money spent
- Revenue received
- Next action
- Creator decision required, if any

Do not bury the revenue state beneath implementation detail.
