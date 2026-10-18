![Records Intelligence: supplied PDFs become a source-linked review pack.](assets/records-banner.svg)

# Records Intelligence

I build **Records Intelligence**, a local-first tool that turns a small set of supplied PDFs into a **draft review pack**: every finding is linked to the passage and page it rests on, the original files and each revision are kept, unresolved gaps are listed, and the human review decision stays visible.

**[Project overview](https://claudedclaude2-byte.github.io/)** · **[What exists today](https://claudedclaude2-byte.github.io/platform.html)** · **[Public roadmap](https://github.com/claudedclaude2-byte/claudedclaude2-byte.github.io/blob/main/ROADMAP.md)** · **[Scope and limits](https://claudedclaude2-byte.github.io/trust.html)** · **[Contact](mailto:kimivacko@yahoo.com)**

## A small evaluation, on fictional documents first

| | Private Windows business-evaluation scope |
| --- | --- |
| **You supply** | One factual question, the statements to check and up to 25 born-digital PDFs (250 pages in total, at most 100 per PDF; 10 MiB per file and 64 MiB in total) |
| **You get** | A draft review pack: exact and possible passage matches, missing records, differing values, a chronology of recognised dates, and links back to the source pages |
| **Corrections** | One correction round. It produces revision 2 with a reason; revision 1 stays available for comparison |
| **Review** | A reviewer records a decision and its basis. Changing the content makes that approval stale |
| **Scans** | Optional, and only with individually reviewed transcripts |

These bounds were measured with generated fictional inputs on the development machine; they do not establish customer accuracy, operator time, acceptance or release. The smaller demonstration profile remains 6 PDFs, 20 pages in total and 10 pages per PDF.

The first conversation needs no client documents: ask to see the **fictional sample**, or describe **one preparation or checking step** you would like to make easier.

## Where it stands · October 2026

- **Built:** local components for records requests, evidence search, source provenance, reviewed redaction, and versioned dossiers with an independent offline verifier.
- **Pilot:** the private Windows build has a bundled-runtime installer, a fictional demonstration and measured business-evaluation capacity. Final verification remains open.
- **Sample:** a fictional walkthrough kit is frozen, and its backup copy has been checked against the same checksums.
- **Still open:** final Windows and Linux verification, acceptance, first use on a separate clean machine, distribution conditions and a public runnable release. There is no hosted app, upload portal or public download, and no production use is offered.

A passing check confirms only what that check covers. It does not establish that a source is true, authentic or complete, and nothing here is legal advice.

**Stack:** Python · SQLite/FTS5 · local Flask/Jinja interfaces · Windows-first, offline. The implementation repository is private.

## Where the project is going

The ambition is a complete investigation workbench: records requests, documents, source-linked findings, corrections and follow-up questions in one inspectable trail.

| Stage | Direction |
| --- | --- |
| **Built** | Records workflows, evidence search, provenance, reviewed redaction and versioned dossiers |
| **Now** | Finish verification of the private Windows installer and its evaluation package |
| **Next** | Clean-machine installation, clearer first use and guided fictional partner evaluations |
| **Planned** | Richer revision comparison, request-gap integration and source-change context |
| **Longer term** | Partner integrations, shared review, an optional hosted workspace and deeper discovery |

Later stages are intended or exploratory work, with no announced release dates. See the [full public roadmap](https://github.com/claudedclaude2-byte/claudedclaude2-byte.github.io/blob/main/ROADMAP.md) for the stages and milestones.

## Contact

**Records Intelligence** · [kimivacko@yahoo.com](mailto:kimivacko@yahoo.com)

Please do not send client documents or personal data in a first message.


