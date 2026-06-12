# Source Notes

Evidence snapshot date: 2026-06-12.

## Corpus Snapshot

This skill was originally distilled from a local research corpus. Preserve raw post text in private research artifacts and keep the public skill package focused on reusable workflow, evidence rules, and case patterns.

- Unique records recovered: 1,965.
- Official X `statuses_count` observed in captured profile state: 6,916.
- Approximate recovered share: 28.4%.
- Newest recovered post: 2026-05-31T10:23:02.194Z.
- Oldest recovered post: 2025-07-02T10:48:09.000Z.
- Reply-like records: 951.
- Records with cashtags/symbols: 1,332.

Original internal outputs:

- `tweets.master.json`: structured corpus with source trace per tweet.
- `tweets.master.jsonl`: one JSON record per line for embedding/RAG.
- `tweets.master.csv`: compact spreadsheet-friendly view.
- `corpus_report.md`: source coverage and monthly distribution.

Input source summary:

| Source | Unique ids | Newest | Oldest | Quality |
| --- | ---: | --- | --- | --- |
| `x_status_pages` | 83 | 2026-05-30 | 2025-07-02 | Official status pages discovered from URLs. |
| `x_highlights` | 99 | 2026-05-30 | 2025-09-12 | Official logged-out highlight timeline. |
| `instalker` | 1,813 | 2026-05-31 | 2025-11-17 | Structured mirror JSON, widest coverage. |
| `twiscan` | 40 | 2026-05-29 | 2025-12-26 | HTML mirror with inferred date strings. |

The denominator is X's profile-level statuses count rather than a clean public-post count. It can include replies and other activity, so use it as profile-activity context.

## June 2026 Incremental Snapshot

After the original corpus snapshot, an incremental pass was performed on 2026-06-12 for posts after 2026-05-30.

- The incremental table combines local recovered full-text records through 2026-05-31 with public search-index snippets and mirror-feed snippets for 2026-06-01 to 2026-06-12.
- A local staging table captured 77 investment- or skill-relevant rows from 2026-05-30 to 2026-06-12.
- Use this increment for updating recurring framework moves and source-routing.
- Durable themes extracted from the increment: AAOI standalone optics case, SIVE multi-hop proof chain, reference-design/foundry-platform evidence tier, CPO/LPO/LRO vocabulary, constructive versus toxic dilution, listing venue and investor-base migration, volatility versus invalidation, policy-backed sovereignty nodes, information-cycle compression, A-share market adaptation, and 800V DC/power-delivery adjacency.

## Source Tiers

- Tier 1: Original public posts or direct mirrors of @aleabitoreddit's X timeline. X is the primary venue; timestamp mirrors and cross-check important claims.
- Tier 2: Company filings, releases, reports, and transcripts used to validate or falsify claims from the posts.
- Tier 3: Third-party trackers and media articles. Useful for synthesis, but not proof of performance or current holdings.

## Key Sources Reviewed

- TwiScan profile mirror: `https://twiscan.com/en/x/aleabitoreddit`
  - Shows the account profile as Serenity, @aleabitoreddit, with a self-description as an AI/semi supply-chain analyst and former Reddit WSB trader.
  - Recent posts emphasize SIVE's pipeline growth, AI photonics/CPO ramps, free research for retail, European equity track record, and government/index/listing catalysts.
  - Treat follower counts, subscriber counts, and performance claims as self-reported or mirror-reported metadata. Search/opened snapshots varied materially over time.

- TwiScan AXTI thread mirror: `https://twiscan.com/en/x/aleabitoreddit/2056157639760126294`
  - Captures a May 17, 2026 follow-up on AXTI and a December 26, 2025 thesis arguing that InP substrates could bottleneck AI photonics supply chains.
  - Useful for extracting the original "AI supply-chain vulnerability" and InP substrate chokepoint logic.
  - Do not assume market-share estimates are correct without checking industry reports and company disclosures.

- TwStalker profile mirror: `https://mobile.twstalker.com/aleabitoreddit`
  - Opened on 2026-05-31 and showed 525k followers and 7k tweets.
  - Useful as a current approximate profile mirror, but not as final truth because third-party counters refresh differently.

- Mixerno profile counter: `https://mixerno.space/twitter-user-counter/aleabitoreddit`
  - Opened on 2026-05-31 and showed 342,489 followers and 6,717 tweets, much lower than TwStalker and Serenity's later self-reported milestones.
  - Use this discrepancy to remind outputs that profile metadata is time-sensitive and mirror-dependent.

- Serenity Tracker / SemiconStocks: `https://semiconstocks.com/`
  - Third-party tracker that organizes the framework into AI photonics chokepoint layers and lists public theses.
  - Useful for a starting taxonomy: raw materials, pBN crucibles/growth equipment, InP substrate processing, CW lasers, optical transceivers, testing/qualification, and fiber/cabling.
  - The site itself warns that holdings, position sizes, and complete win/loss data are not auditable.

- WOOK98/serenity-aleabitoreddit: `https://github.com/WOOK98/serenity-aleabitoreddit`
  - Supplemental GitHub distillation that describes itself as built from about 5,582 tweets and 4 X Articles covering 2025-07 to 2026-05.
  - Useful additions reviewed: methodology principles, per-ticker thesis organization, long-form article summaries, track-record calibration, and maintenance rules.
  - Treat as Tier 3 third-party synthesis. It can improve the checklist but should not override primary posts, filings, or current market data.

- ChainCatcher methodology article: `https://www.chaincatcher.com/en/article/2268235`
  - Secondary source that describes the bottleneck method as confirmed demand, limited supply, low attention, value capture, and catalysts.
  - Reports the 4502.45% YTD claim and public target-performance narrative as public context, not audited proof.

- PANews profile article: `https://www.panewslab.com/en/articles/019e69f3-28a3-72ca-9edc-409b4fbb4a50`
  - Secondary source describing the account's "perilla leaf" idea: the indispensable small input can matter more than the expensive headline item.
  - Useful for summarizing method: technical papers, physical laws, supply-chain mapping, and adversarial testing of drafts.
  - The same article highlights major risks: microcap liquidity, unverified identity/performance, technical-validation risk, and strict position management needs.

- PANews Chinese / BruceBlue article: `https://www.panewslab.com/zh/articles/019e674b-724f-736c-8077-b2221cf24e39`
  - Media synthesis presenting the "2-year 225x / 22,561.99%" narrative and the AI bottleneck investment frame.
  - It explicitly states that Serenity's background information is self-reported and unverified, and that historical performance does not represent future results.

- Sivers Semiconductors Q1 2026 report: `https://www.sivers-semiconductors.com/wp-content/uploads/2026/05/Sivers-Interim-report-Q126_FINAL_ENG.pdf`
  - Company source confirming Q1 2026 revenue of SEK 61.9m, revenue pressure from defense-budget timing and FX, and a stated opportunity-pipeline growth figure.
  - Use this as an example of validating a social thesis against company-reported operating data, including negative data.

- June 2026 incremental research file: `references/update_2026_06.md`
  - Staging notes from the post-2026-05-30 evidence snapshot.
  - Useful for new optics, SIVE, AAOI, policy, dilution, listing, reflexivity, and A-share extension logic.
  - Treat post-level snippets as leads unless the row points to a primary company, customer, filing, transcript, or policy source.

See `achievements_and_sources.md` for date-stamped achievement claims and reliability labels.

## Distilled Patterns

- Start with physical bottlenecks, not app-layer narratives.
- Identify monopoly/duopoly or hard-to-qualify nodes before they become consensus.
- Prefer obscure, small, or foreign-listed suppliers where institutions may be slow.
- Look for a technical architecture shift that changes the demand curve, such as CPO replacing or augmenting traditional interconnect.
- Track government funding, sovereignty language, export controls, and customer qualification as validation.
- Keep a dilution and capital-structure audit beside every growth thesis.
- Distinguish constructive financing from toxic dilution by checking use of proceeds, structure, timing, and shareholder leakage.
- Treat listing venue, investor-base migration, index eligibility, and ownership filings as valuation/timing variables, not product validation.
- Add reference-design, ecosystem, foundry-platform, and customer-evaluation signals as a middle evidence tier below recognized revenue.
- Keep photonics chain vocabulary precise: substrate, epi, foundry, laser, external light source, light engine, pluggable transceiver, LRO/LPO, CPO, package/test, and EMS are not interchangeable.
- Treat violent volatility as expected in microcaps, but not as proof that the thesis is intact.
- Conversely, do not treat volatility as thesis invalidation unless a specific invalidation test fails.
- Treat audience growth as a reflexivity variable: it affects price impact and crowding, but it is not fundamental validation.
- Recognize information-cycle compression: public research, AI tools, and retail distribution can move a thesis from obscure to crowded faster than older institutional cycles.
- Add financial-quality lenses from WOOK98's synthesis: signed ARR versus market cap, GAAP margins over non-GAAP claims, Mag7/customer concentration, financing quality, macro/flow/IV overlays, and conviction tiering.

## Evidence Limits

- Search-index snippets are routing evidence: use them to locate status URLs, themes, and primary documents.
- Track record claims are not audited and may suffer survivorship bias.
- Third-party trackers can paraphrase incorrectly or lag current position changes.
- Third-party GitHub distillations can be useful but may contain selection bias, stale thesis state, or unverified backtest/calibration claims.
- Public posts can move illiquid stocks; price action after a post is not evidence of fundamental validation.
- This framework should produce research checklists and scenarios, not trade instructions.
