# Changelog

Repository-level record of what was added, changed, or removed, and why.

The format follows [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

Two governance regimes share this repository, and they version differently:

- **The Ethical AI Constitution** follows semantic versioning: MAJOR.MINOR.PATCH.
  - **MAJOR**: A foundational commitment or prohibition is added, removed, or fundamentally reframed
  - **MINOR**: A new principle, pillar, or operating guideline is added
  - **PATCH**: Clarification, language correction, or editorial improvement with no change in meaning
- **ECPs are versioned individually**, in place, under the amendment process in [ECP-0](ECPs/ecp-0000.md). Each ECP carries its own version history in its Decision record. This file records when an ECP enters or changes status in the series; it is not the authoritative version history for any individual proposal.

---

## 2026-07-28

The repository broadens from a single constitutional document to the full public ethics programme.

### Added
- **Ethics Commons Proposal series** (`ECPs/`) — community-ratifiable standards, independent of any platform or organisation. All three are v0.1 and provisional, pending community ratification, with the founding author acting as provisional editor:
  - `ECP-0` — series purpose and guidelines: template, required sections, status lifecycle, editor role, AI Editor constraints, ratification at 60% supermajority of participating voters, and the amendment process. Type Meta, status Living.
  - `ECP-1` — adjudication governance: authority boundaries, categorisation, severity ladder, disclosure tiers, and the adjudication body. Type Standards Track, status Draft.
  - `ECP-2` — registry data specification: record schema, de-identification, publication rules, and AI agent constraints. Type Standards Track, status Draft.
- **The Nine Standards** (`repair-process/nine-standards.md`) — working framework defining what ethical repair means in practice and what a fair process requires. Predates the ECP series and informs ECP-1. Pre-ratification; expected to fold into the series.
- **ECP series index** (`registry/`) — machine-readable index of assigned ECP numbers with the status vocabulary from ECP-0. Maintaining it is an editor responsibility. Distinct from the Ethics Case Decision Registry, which is a separate dataset in a separate repository under CDLA-Permissive-2.0.
- **Constitution overview** (`constitution/README.md`) — principles at a glance, philosophical foundations, and an explicit statement of how the constitution changes, as distinct from the ECP series.
- **GitBook configuration** (`.gitbook.yaml`, `SUMMARY.md`) — table of contents for the published documentation site.

### Changed
- **Root `README.md` restructured** around the programme rather than the constitution alone. Adds a section naming the two governance regimes and which route a proposed change travels, and a section stating what is deliberately not in this repository: adjudicated case records, case studies and internal analysis, and working records from any adjudication.
- **Constitution moved** from the repository root to `constitution/`, and a License section added to the document itself, making CC BY 4.0 explicit in the text rather than only in the README. No change to any commitment, principle, or prohibition.
- **Licensing table added** to the root README, distinguishing documents (CC BY 4.0), code (Apache 2.0), the registry dataset (CDLA-Permissive-2.0), and the standard names and conformance marks (trademark, held by Mind Lumen).

### Notes
- The ECP series shares its document template and status vocabulary with the HUGG CIP series by convention, to allow shared tooling. This creates no dependency in either direction, and ECPs must not require HUGG membership or infrastructure.
- No case material appears in this repository in any form, however anonymised. This is a standing constraint, not a property of the current contents.

---

## [1.0.0] — 2026-03-30

### Added
- Initial publication of `constitution.md`: hierarchy of commitments, four philosophical pillars (psychology, philosophy, anthropology, applied ethics), core operating principles (cognitive liberty, source independence, language and framing, system limits, harm reduction), prohibited behaviors, and governance framework
- Initial publication of `narrative.md`: [*Why We Built It This Way*](https://mindlumen.substack.com/p/the-story-behind-mind-lumens-ethical) — plain-language explanation of the reasoning behind the constitution, published on Mind Lumen Substack
- `README.md` with principles at a glance and versioning policy

### Notes
- First public version, written before any AI application code exists
- The commitment to "thinking in the open" means this document predates the product it governs
- The hierarchy of commitments opens with risk reduction rather than harm elimination — a deliberate epistemological choice reflecting the harm reduction framework that grounds the entire constitution
