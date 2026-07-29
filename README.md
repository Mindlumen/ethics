# Mind Lumen Ethics Infrastructure Framework

**Open source ethics infrastructure for mental health and psychedelic communities**

**Author:** Neil Gehani, Founder, Mind Lumen

Mind Lumen is a 501(c)(3) nonprofit. We build systems of trust: ethical frameworks, certification, and the infrastructure that makes accountability observable rather than asserted. We publish those frameworks openly, before we build on them, because a framework nobody can inspect is not a framework — it is a claim.

This repository holds everything in that programme that is meant to be public.

## What's in here

### `/ECPs` — Ethics Commons Proposals

Community-ratifiable standards for handling ethics concerns and conflicts. The ECP series is independent of any platform or organisation, and any community may adopt it.

| Document | What it covers |
|---|---|
| [ECP-0](ECPs/ecp-0000.md) | Series purpose and guidelines — template, statuses, editor role, amendment process |
| [ECP-1](ECPs/ecp-0001.md) | Adjudication governance — authority boundaries, categorisation, severity ladder, disclosure tiers, the adjudication body |
| [ECP-2](ECPs/ecp-0002.md) | Registry data specification — record schema, de-identification, publication rules, AI agent constraints |

### `/repair-process` — The Nine Standards

A working framework defining what ethical repair means in practice and what a fair process requires. Predates the ECP series and informs ECP-1.

### `/constitution` — Ethical AI Constitution

The principles governing how Mind Lumen designs, builds, and evaluates AI applications. Written before the code, and published so others can use or adapt it. See [`constitution/README.md`](constitution/README.md).

### `/registry` — Series index

Machine-readable index of assigned ECP numbers, used by tooling.

## Two governance regimes, one repository

This matters before you open a pull request. The documents here are not all changed the same way.

| Documents | How they change | Who decides |
|---|---|---|
| ECPs | The ECP-0 amendment process: fourteen-day Last Call, then 60% supermajority of participating voters | The community that has adopted the series |
| Constitution | Layer 0 of the Architecture of Constraints. Changed only by the Somatic Compiler role, with documented rationale | Mind Lumen |
| Repair process | Working draft, currently pre-ratification. Expected to fold into the ECP series | Mind Lumen, provisionally |

A proposal to change an ECP is a community matter and follows ECP-0. A proposal to change the constitution is a suggestion to Mind Lumen, which we welcome but do not put to a vote. Both are worth making; they travel different routes.

## What is deliberately not here

**Adjudicated case records.** These live in a separate registry under a different license (CDLA-Permissive-2.0), because they accumulate without bound, require privacy review on every addition, and are intended to transfer to an independent steward.

**Case studies and internal analysis.** Case analysis is internal work. It informs the standards but is not published here, and no case material — however anonymised — belongs in this repository.

**Working records from any adjudication.** These are confidential by design and destroyed or sealed at closure under ECP-1.

The registry is a measurement instrument, not a screening instrument. It carries no identities and cannot tell anyone whether a specific person has a history. That is the intended tradeoff.

## Licensing

| Content | License |
|---|---|
| All documents in this repository | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Any code published here | Apache 2.0 |
| Registry dataset (separate repository) | CDLA-Permissive-2.0 |
| Standard names and conformance marks | Trademark, held by Mind Lumen |

Attribution is requested for adaptation and reuse, in the form used throughout the ECP series: **attribution: Mind Lumen, Author: Neil Gehani**. Claiming conformance to a Mind Lumen standard requires the mark; implementing or adapting the standard does not.

## Contributing

Scrutiny is the point. Disagreement, gaps, and unresolved questions are more useful to us than agreement.

Where an ECP has unresolved questions, it carries an open-questions section listing them. Those are the best places to start.

Open an issue to raise a concern or suggest a change. For ECPs, suggestions that identify a specific section and propose alternative language can move through the process; general objections belong in discussion first. Contributions are attributed by name — the framework is public intellectual work, and its authorship should be visible.

## Related reading

[Why We Built It This Way](https://mindlumen.substack.com/p/the-story-behind-mind-lumens-ethical) — the reasoning behind the constitution: the gatekeeping problem, the money problem, who holds knowledge, and the theory of healing these tools are built around.

*Mind Lumen — [mindlumen.org](https://mindlumen.org)*
