---
name: serenity-chokepoint-investing
description: "Use when analyzing stocks through @aleabitoreddit/Serenity-style supply-chain chokepoint thinking: AI/semi photonics, scarce physical bottlenecks, small-cap monopoly or duopoly nodes, catalyst timing, valuation mismatch, and risk controls. This skill supports investment research and stock analysis; it does not provide personalized financial advice."
---

# Serenity Chokepoint Investing

Use this skill to turn an investment idea into a structured chokepoint thesis. The goal is not to copy any public trader's positions. The goal is to test whether a company controls a scarce, hard-to-substitute physical layer that captures value as downstream demand expands.

Respond in the user's language. If the request is in Chinese, keep the research output in Chinese while preserving ticker symbols, filings, and source titles as written.

## Reference Material

Read only what the task needs:

- `references/source_notes.md`: corpus coverage, source tiers, and reliability limits.
- `references/achievements_and_sources.md`: Serenity/@aleabitoreddit public achievements, follower growth, performance claims, and verification status.
- `references/serenity_framework.md`: distilled investment philosophy and reusable research moves.
- `references/case_patterns.md`: recurring case archetypes such as AXTI, SIVE, SOI, AAOI/LITE/COHR, European photonics names, and NBIS.
- `references/maintenance.md`: rules for updating this skill from new posts or outside research without turning it into a noisy transcript.

## Guardrails

- Treat all social-media posts as leads, not proof.
- Do not issue buy/sell instructions. Produce research, scenarios, risks, and invalidation points.
- Check current prices, filings, company releases, transcripts, dilution, and short interest before making conclusions.
- Separate primary evidence from third-party summaries and self-reported performance.
- For microcaps, explicitly discuss liquidity, float, dilution, hype reflexivity, and exit risk.
- Never present Serenity's self-reported returns or follower growth as audited evidence. Label them as self-reported, mirror-observed, or media-reported.
- Treat options, margin, short-squeeze setups, and IV/vega trades as advanced risk overlays. Do not convert them into trade instructions or position-size prescriptions.

For source context and known evidence limits, read `references/source_notes.md` when the user asks about Serenity, @aleabitoreddit, AXTI, SIVE, AAOI, SOI/SLOIF, IQE, XFAB, or the origin of this framework.

## Core Philosophy

Look beneath obvious AI winners and ask which obscure physical inputs can stop the whole buildout. The strongest candidates are small or ignored suppliers whose materials, tools, qualification status, or installed capacity are needed by much larger downstream customers.

Key ideas:

- Scarce inputs beat popular narratives: find the supplier without which the headline company cannot ship.
- A tiny upstream node can capture nonlinear attention when downstream capex becomes urgent.
- The edge comes from technical and supply-chain depth, not from copying 13F filings after institutions arrive.
- "Monopoly" or "chokepoint" claims must be proven by market share, qualification barriers, customer dependency, and lack of substitutes.
- Catalyst timing matters: product ramps, customer qualification, government funding, index inclusion, exchange listings, and earnings transcripts can reveal whether the thesis is moving from story to revenue.
- Distribution matters, but only as reflexivity: a large audience can accelerate repricing and crowding, so it changes liquidity, timing, and exit risk without validating fundamentals.

## Workflow

1. Define the candidate and downstream demand driver.
   - Ticker, exchange, market cap, liquidity, core product.
   - Which secular spend pool pulls demand through it: AI capex, CPO, memory, power, data centers, defense, energy, or another physical constraint.
   - Why now: what changed in architecture, regulation, customer behavior, or capex timing.

2. Map the supply chain.
   - Build a table with `Layer`, `Physical constraint`, `Known suppliers`, `Candidate role`, `Market share`, `Switching cost`, `Substitutes`, `Evidence`, and `Open questions`.
   - For AI photonics, start with these layers: raw materials, pBN crucibles/growth equipment, InP or SOI substrates, epiwafers, CW lasers, optical transceivers/assembly, testing/qualification, fiber/cabling.
   - Do not assume the visible product assembler owns the profit pool; test upstream and midstream nodes separately.
   - Enforce chain fluency: do not conflate substrate, epiwafer, foundry, laser, transceiver, module, package, or system-integrator roles.

3. Score the chokepoint.
   - Irreplaceability: Can customers qualify alternatives quickly?
   - Scarcity: Is capacity structurally constrained by equipment, process know-how, materials, geography, or regulation?
   - Demand leverage: Does downstream capex multiply demand for this input?
   - Customer validation: Are there named customers, design wins, purchase orders, qualification orders, grants, or transcript confirmations?
   - Economic capture: Can the company convert scarcity into revenue, margins, and cash flow?
   - Market neglect: Is the asset mispriced because it is small, foreign-listed, legacy-tainted, or misunderstood?

4. Build the evidence ladder.
   - Prefer primary sources: annual reports, 10-K/20-F/6-K/8-K, company presentations, earnings transcripts, customer press releases, and government awards.
   - Then use technical sources: papers, patents, bill-of-materials analysis, industry notes, standards, supplier lists, import/export data, and hiring/procurement signals.
   - Use social-media and third-party trackers only to generate hypotheses or locate source documents.
   - Require at least two independent confirmations before labeling a company a chokepoint.
   - When citing Serenity, include the post URL or local corpus id if available, plus a note on whether it came from official X, a mirror, or a media article.

5. Convert the thesis to financial scenarios.
   - Current revenue, gross margin, EBITDA, cash, debt, burn, share count, and recent financing.
   - Backlog or opportunity pipeline versus recognized revenue.
   - Signed contract ARR or take-or-pay commitments versus market cap, when applicable.
   - GAAP margin quality versus non-GAAP or cherry-picked segment margin claims.
   - Customer/counterparty quality: AAA hyperscaler, strategic investor, cash-burning startup, local government, or retail-only narrative.
   - Unit economics: how many units per downstream deployment, selling price, gross margin, and ramp timing.
   - Base, bull, and bear cases with explicit assumptions.
   - Dilution audit: ATM programs, converts, warrants, shelf registrations, private placements, and insider selling.

6. Track catalysts and invalidations.
   - Catalysts: earnings calls, customer qualification, volume production starts, government funding, export controls, index inclusion, uplisting, industry conferences, and supply warnings.
   - Invalidations: substitute qualification, customer loss, failure to ramp, margin collapse, excessive dilution, demand pull-in, inventory glut, or regulatory/geopolitical reversal.
   - Update the thesis when capital structure or evidence changes, even if the original product thesis remains intact.
   - Explicitly separate "price moved after a post" from "the company validated the thesis." The first is market reflexivity; the second needs primary evidence.
   - Treat macro shocks, short interest, passive/index flows, dark-pool/block flow, and options IV as timing or positioning overlays, not substitutes for the underlying thesis.

7. Produce a research output.
   - One-paragraph thesis.
   - Chokepoint map.
   - Evidence table with source quality.
   - Financial scenario table.
   - Catalyst calendar.
   - Risk and invalidation checklist.
   - Confidence rating and what data would change it.

## Distillation Pattern

When asked to distill Serenity's thinking into skills:

1. Start from the corpus, not from viral summaries.
2. Extract repeatable moves: supply-chain mapping, bottleneck scoring, catalyst timing, valuation mismatch, dilution audit, and anti-hype checks.
3. Convert each move into a checklist that can be applied to a new stock.
4. Attach examples as archetypes, not recommendations.
5. Keep achievements in a separate evidence table with reliability labels.

## Output Template

```markdown
## Thesis
[Company] may be a [layer] chokepoint for [downstream demand] because [scarcity mechanism].

## Chokepoint Map
| Layer | Constraint | Suppliers | Candidate role | Evidence | Open questions |
| --- | --- | --- | --- | --- | --- |

## Evidence Quality
| Claim | Source | Quality | Notes |
| --- | --- | --- | --- |

## Financial Translation
| Case | Revenue driver | Margin assumption | Dilution/cash assumption | Implied outcome |
| --- | --- | --- | --- | --- |

## Positioning Constraints
| Issue | Evidence | Implication |
| --- | --- | --- |
| Liquidity/float | | |
| Dilution/ATM | | |
| Customer concentration | | |
| Options/margin/IV risk | | |

## Catalysts
| Date/window | Event | What would confirm | What would weaken |
| --- | --- | --- | --- |

## Risks
- Liquidity/float:
- Dilution:
- Execution:
- Substitution:
- Valuation:
- Reflexive hype:

## Verdict
Confidence: Low/Medium/High.
Do not act until these missing items are checked: [list].
```
