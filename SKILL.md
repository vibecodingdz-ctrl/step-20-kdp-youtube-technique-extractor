---
name: step-20-kdp-youtube-technique-extractor
description: Public YouTube technique indexing for KDP knowledge maintenance. Use when refreshing a bounded video date range or channel research set.
license: Complete terms in LICENSE.txt
---

# Sys 01 Kdp Youtube Technique Extractor

Capture public video metadata and technique claims without pretending a transcript exists.

## Non-negotiable project rules

- Keep Samir in control: never publish, upload, pay, change an account, or submit a form. Prepare files and instructions only.
- Use free methods first. Before any tool or provider that may cost money, ask exactly: **Free tool or paid tool?** If free is insufficient, explain why, list paid options from highest to lowest price, and wait for written approval.
- Work only in the active browser and project files. Do not use a VPS, proxy, CAPTCHA bypass, private login, or hidden scraping.
- Never invent Amazon search counts, BSRs, ratings, prices, quotes, sales, reviews, or search volume. Missing data is `no data`, `UNKNOWN`, or `INCOMPLETE`.
- Attach an evidence tag to every number: `[VERIFIED: URL, YYYY-MM-DD]`, `[COURSE]`, `[ESTIMATE]`, `[ASSUMPTION]`, or `[RECOMMENDATION]`.
- Use dated lowercase filenames such as `output_<topic>_<yyyymmdd>.md`. Never overwrite a dated file; create a new dated file with a `Supersedes:` header.
- If work cannot be completed, mark it `BLOCKED` and record exactly: `Error / Tried / Next`.
- Do not claim completion without a real file path, read-back, command result, or visited URL.

## Inputs

Public video URLs or channel/date range, allowed source scope, and current project research question.

## Procedure

1. Record video ID, title, channel, upload date, URL, description status, and transcript status.
2. Use public metadata only; do not log in or bypass restrictions.
3. Separate verbatim description text from synthesized technique notes.
4. Probe at least one control video to test retrieval reliability.
5. Mark unavailable transcripts as UNKNOWN.

## Required outputs

`02_Knowledge_Base/YOUTUBE_RESEARCH/video_index_<yyyymmdd>.csv` and `transcript_status_<yyyymmdd>.csv`.

## Quality gate

Do not claim all videos or a complete transcript set unless coverage was verified.
## Workflow position

**Step 20** — this card is part of the numbered KDP workflow. Use the previous step outputs before starting it and pass its required outputs to the next step.

