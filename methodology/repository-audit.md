# Repository structure audit

> Historical audit: the counts and all-80-source-note check below describe the pre-cleanup revision. The subsequent source-note cleanup removed 74 non-core standalone pages, retained six selected source notes, and moved E080 to [project materials](../projects/owner-statement.md). Current source classifications and document locations are in the [evidence guide](../evidence/README.md) and supplementary register. Preserved Chinese originals remain unchanged.

Reviewed November 14, 2026 against commit `5af09889357a3cd93084e685cc586e3e3e8f6c3d`, followed by the repairs described below. This is a structure, provenance and consistency review, not a new verification of external allegations or a certification of translation accuracy.

## Findings and repairs

| Finding | Repair / disposition |
| --- | --- |
| Translation method and consolidated English review still said E001–E018 were in the main index | Updated both to explain the six-entry main index and 74-entry supplementary register; historical identifiers retained |
| Main reading routes did not clearly surface supplementary classifications | Added evidence-guide and supplementary-register links to English/Chinese READMEs and review navigation |
| No compact map connecting each matter to selected sources, related citations and missing documents | Added [matter-to-source map](../evidence/matter-source-map.csv) for six historical matters and the separate project group |
| Residential-project records were missing from the central outstanding list | Added combined project totals, contracts, equipment allocation, amount/currency basis, entities and payment records to [outstanding records](../research/outstanding-records.en.md) |
| Submission directory had no reading guide | Added [submission guide](../submission/README.md), including evidence classifications and project materials |
| Originals page used “source register” ambiguously after the split | Clarified that neither CSV is an inventory of downloaded exhibits |
| Archived English README has 10 old-root relative link occurrences | Retained byte-for-byte as a historical snapshot; [archive guide](../archive/README.md) identifies its obsolete link context. It is excluded from current-navigation checks |

## Verification

- All 149 tracked files at the reviewed commit were fetched at that pinned revision; no truncated tree was used.
- Nine migration entries each have a Chinese preserved file and English counterpart. All nine preserved contents match the recorded Git blob identifiers and SHA-256 checksums.
- The archived consolidated Chinese corruption snapshot matches its preserved Chinese counterpart.
- Six historical matters each have English and Chinese summary files. Both residential-project language versions are present.
- The two source registers contain 6 + 74 unique entries, covering E001–E080 without overlap; all 80 corresponding source notes exist and resolve.
- Seven rows in the new matter map cover all six historical matters and the separate two-project group. Referenced source IDs, selected-source membership and summary paths were checked.
- Current internal Markdown file and section links were checked, excluding the explicitly historical README snapshot. External URL availability and source authenticity were not checked by this audit.
- After repairs, the repository contains 152 tracked files. No source notes or preserved originals were deleted.

## Subsequent project clarification

The owner supplied the project allocation and unit price after this audit: Zizhu Huating 13 elevators and Changli Huayuan 54, at RMB 180,000 each. Calculated subtotals are RMB 2,340,000 and RMB 9,720,000, totaling RMB 12,060,000. The owner also clarified that the amounts cover elevator equipment and installation fees, including removal of the existing elevators. The allocation and fee-scope gaps recorded below are superseded by these statements; underlying transaction records remain outstanding. See [current project note](../projects/shanghai-zizhu-changli.en.md).

## Material gaps recorded at the audit

| Priority | Gap | Where tracked / implication |
| --- | --- | --- |
| High | Wuhan Chinese judgment, identity, case number, statutory offense, sentence and finality | [Outstanding records](../research/outstanding-records.en.md); SEC's recorded conviction does not supply the missing Chinese judgment |
| High | Yiwu complete appellate/trial judgments; Hunan official notice and full attachment; Jin Yun charging/final disposition | Same list; media reports and missing-record identifiers are not authenticated originals |
| High — project substantiation | Zizhu Huating / Changli Huayuan supporting files, per-project allocation, amount type/currency, dates and legal entities | [Project note](../projects/shanghai-zizhu-changli.en.md); 67 elevators and reported RMB 12,060,000 are combined owner-supplied figures, not independently verified transaction findings |
| High — source preservation | No external judicial/regulatory artifacts are bundled | [Originals status](../evidence/originals/README.md); future stored files need source URL, acquisition date, filename and hash |
| Medium | E019–E079 still use generic inherited titles and largely unnormalized publication metadata | [Supplementary register](../evidence/supplementary-register.csv); specific titles, relevant pages and factual links must be established before promoting any entry into the main index. E033 is excluded as irrelevant |
| Medium | Some lead pages are inaccessible, snippet-based or entity-unmatched; copied reports may share one origin | Individual source notes and [unverified leads](../research/unverified-leads.en.md); no independent corroboration is inferred |
| Medium | Chinese primary-document translations and independent translation checking | [Translation status](../evidence/translations/README.md); English research renderings are available, but no translation of an unavailable original is claimed |
| Background | Civil originals/appeals/recoveries, maintenance decisions and regional-leadership screenshot | [Outstanding records](../research/outstanding-records.en.md); inferred contacts and organizational context do not establish involvement |

The archived Chinese research deliberately retains its original scope statement excluding current residential projects from historical bribery research. The current package includes those projects separately; this is not a lost translation or a seventh historical bribery case.

A submission receipt, regulator correspondence or completed SEC filing is not present because no submission was made through this work. Repository access for an external reviewer must be arranged separately; no visibility change was made.
