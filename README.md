![Records Intelligence — From records to a reviewable case.](assets/records-banner.svg)

# Building tools that make information reviewable.

I'm building **Records Intelligence**, a local-first investigation and evidence platform. My focus is on connecting supplied records to source-linked findings, preserving revisions, and keeping human review decisions visible.

**[Explore the project](https://claudedclaude2-byte.github.io/)** · **[Platform guide](https://claudedclaude2-byte.github.io/platform.html)** · **[Product roadmap](https://claudedclaude2-byte.github.io/roadmap.html)** · **[Trust & scope](https://claudedclaude2-byte.github.io/trust.html)**

## Flagship project: Records Intelligence

**From records to a reviewable case.**

Records work can span requests, responses, missing attachments, competing statements and corrected versions. The platform connects that work so a reviewer can inspect what was supplied, where a passage appears, and what remains unresolved.

| Area | What it supports |
| --- | --- |
| Records requests | Request history, canonical drafting, deadline helpers, expected-record comparisons, response gaps and follow-up recommendations. Live sending requires human authorization. |
| Evidence & search | Supported package indexing, fingerprints, extraction outcomes, full-text search and structured/entity-aware filters. |
| Provenance & claims | On-demand source snapshots, evidence-anchored claims, conservative identity review and attributable contradiction flags. |
| Redaction & dossiers | Individually reviewed redaction derivatives, preserved originals, versioned dossiers, exact-passage citations and independent offline package verification. |
| Local interfaces | A read-only investigation Workspace plus a separate bounded PDF pilot for intake, preparation, one correction round and review. |

```text
Records → requests → responses → evidence → gaps → follow-up
                                      ↓
                      source-linked findings → human review
```

### Current focus

- Complete the private pilot's final integration and installed acceptance.
- Finish a fictional investigation walkthrough with a frozen package and independent verification/backup.
- Make the platform scope, onboarding and product direction clear to new reviewers.

**Status: private development and bounded pilot validation.** The implementation repository and investigation records remain private. The public website is a project explanation, not a hosted app or a public product download. The final pilot and new demo are not yet declared ready.

### The pilot, in practical terms

One factual question; up to 6 born-digital PDFs, 20 pages total and 10 pages per document; revision 1 plus one correction round. The operator supplies statements and expected passages. The review pack distinguishes exact matches, possible matches, missing records and unread files. Optional scans need individually reviewed transcripts.

### How I build

- **Preserve originals and revisions.** Keep changes and reasons inspectable.
- **Attach claims to sources.** Show the passage and its location.
- **Make unknowns visible.** Missing, unread and not-reviewed states are useful information.
- **Test the actual candidate.** A result belongs to the version and environment that produced it.
- **Keep judgment human.** Mechanical verification does not establish truth, authenticity, legal admissibility or genuine human approval.

The core direction uses **Python, SQLite/FTS5 and local Flask/Jinja interfaces**, with optional OCR and media tools for the paths that need them. Semantic/vector search, multi-user operation and hosted product access remain outside the current offered scope.

## Other work

I also explore video editing and creator automation:

- [MixCut-Skill](https://github.com/claudedclaude2-byte/MixCut-Skill)
- [yt-heatmap-clipper](https://github.com/claudedclaude2-byte/yt-heatmap-clipper)

## Connect

Interested in source-linked investigation workflows, synthetic evaluation, accessibility or clearer onboarding? Start with the [platform guide](https://claudedclaude2-byte.github.io/platform.html) and discuss a bounded, fictional use case through GitHub.

Please keep private records, client information, credentials and operational databases out of public discussions.

<sub>Project overview updated October 2026. Future roadmap stages are proposals, without release dates or service commitments.</sub>
