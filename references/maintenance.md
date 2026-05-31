# Maintenance Rules

Use this file when updating the skill from new @aleabitoreddit posts, new mirror captures, or outside research such as WOOK98/serenity-aleabitoreddit.

The goal is to keep the skill current and compact. Do not turn it into a transcript.

## Update Standard

Promote a new item into the skill only if it adds at least one durable element:

- A repeated research move or decision rule.
- A changed stance, explicit invalidation, or reversal.
- A supply-chain link, customer path, foundry, contract, financing term, or catalyst date.
- A track-record or calibration update that changes how much to weight the lens.
- A risk pattern, anti-pattern, or evidence-quality rule likely to recur.

Skip:

- Jokes, memes, casual replies, duplicate victory laps, and low-evidence opinions.
- Full X Article text or long quoted passages.
- Ticker notes with no durable thesis change.

## Source Priority

1. Originating/private corpus records and official X status URLs.
2. Company filings, releases, transcripts, technical papers, and official customer/vendor disclosures.
3. Structured mirrors used only to recover missing public posts or metadata.
4. Third-party trackers, articles, and GitHub distillations used as synthesis and lead generation.

When WOOK98 or another repository adds an idea, classify it as `third-party distillation` until independently checked.

## File Routing

- Update `source_notes.md` for corpus size, source reliability, and outside-source caveats.
- Update `achievements_and_sources.md` for performance, follower, calibration, or public-reception claims.
- Update `serenity_framework.md` only for reusable principles and checklists.
- Update `case_patterns.md` for archetypes and ticker-family templates.
- Update `SKILL.md` only when the entry workflow, guardrails, or output template needs to change.

## Minimal Provenance Format

Use compact provenance:

- Date or snapshot date.
- Source class: primary/self-reported, mirror-observed, media-reported, third-party distillation, independently verified.
- URL or private corpus id.
- One-sentence durable implication.

Avoid long direct quotes. Preserve full post text only in the corpus files.

## Verification Checklist

Before publishing an update:

1. Confirm the skill frontmatter is valid YAML.
2. Make sure every new performance or follower claim has a reliability label.
3. Make sure every ticker thesis separates inference from primary evidence.
4. Check that options, margin, short-squeeze, and IV content is framed as risk analysis, not trade instruction.
5. Run the skill validator:

```bash
python3 /path/to/skill-creator/scripts/quick_validate.py .
```
