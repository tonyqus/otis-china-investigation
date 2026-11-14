# Evidence and Translation Method

## Source classification

- Official judicial/regulatory original: a record at the issuing body's source. A regulatory order is not a criminal judgment.
- Official/company contextual material: policy catalogues, inspection notices and corporate biographies; use only for the facts they support.
- Secondary report or judgment reproduction: a journalist's account or third-party copy. Record whether the original is missing.
- Firm disclosure: self-reported legal work, not independent performance evidence.
- Search lead: snippet, unavailable page or unverified reference, not an established fact.

The [main evidence index](../evidence/index.csv) contains six selected entries with roles, supported propositions, limitations and related-source groups. The [supplementary register](../evidence/supplementary-register.csv) classifies the other 74 identifiers, including outstanding records and the owner's project statement E080. E001–E018 are historical identifiers, not a declaration that all 18 are core evidence. [Source notes](../evidence/source-notes/README.md) retain only the six selected entries. Other identifiers and access limitations remain in the supplementary register; its `record_location` column points to the relevant research or project file. The November 14 migration did not freshly authenticate external links or all court records.

## Translation rules

English documents are unofficial translations or organized renderings of repository research notes. They are not certified/legal translations of the cited primary records. Chinese notes are preserved at [docs/zh-CN](../docs/zh-CN/README.md); the corruption snapshot is also in [archive](../archive/README.md).

Preserve figures, currencies, Chinese names, case numbers, dates, source links and uncertainty. Keep conduct, publication, decision and access dates distinct. Do not infer criminal terms from money amounts. Translate English “bribery” in SEC reporting without asserting an exact unverified Chinese statutory offense. Mark descriptive English company names and keep Chinese identity anchors.

The English report may reorganize repeated search logs for readability; the complete Chinese text remains available. Source quotations have generally been paraphrased. No unavailable primary document is claimed to have been translated.

## Evidence boundaries

Separate allegation, arrest, prosecution, conviction and sentence; first instance versus appeal and known finality; party assertion versus court finding; administrative classification versus criminal offense; company versus branch/distributor; product sale versus participation in a gift or scheme.

Do not sum global settlement amounts as China-only amounts, count multiple stories as separate cases, count later publication as later conduct, or infer bribery from maintenance breaches.

## Reproducibility

The [migration manifest](migration-manifest.csv) records original paths, source blob identifiers, preserved Chinese files and English counterparts. The [source checksum manifest](source-checksums.csv) covers preserved Chinese files. Git history records the prior root versions.

Automated validation checks local Markdown links, migration coverage and preservation hashes. It does not certify translation accuracy, prove remote source accessibility or authenticate court records. The underlying facts require the verification stated in each report.
