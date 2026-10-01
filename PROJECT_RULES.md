# PROJECT_RULES.md

## 1. Authority and scope

These rules govern all research, drafting, verification, and repository updates for the **Al-Adab wa al-Adhkar Companion**.

GitHub is the permanent source of truth. Working notes outside the repository are provisional until they are checked and committed here.

Accuracy, traceability, and fidelity to sources take priority over completeness or speed.

## 2. Standard hadith structure

Every hadith entry must contain, in this order:

1. **نص الحديث — Hadith Text**
2. **المصدر والحكم — Source and Grading**
3. **المفردات — Key Vocabulary**
4. **شرح الحديث — Explanation**
5. **الفوائد — Sourced Benefits**
6. **تطبيقات ذكرها أهل العلم — Scholarly Applications**
7. **Sources and Verification Status**

Use the controlled template in `templates/hadith-entry-template.md`.

## 3. نص الحديث — Hadith Text

- Preserve the hadith text exactly as found in the selected source.
- Do not silently rewrite, normalize, shorten, combine, or harmonize narrations.
- Record the exact source and locator used for the preserved text.
- If variants are relevant, keep them distinct and identify their sources separately.
- Any normalization made solely for search or indexing must never replace the preserved source text.

## 4. المصدر والحكم — Source and Grading

- Every grading must be attributed to a named scholar or a recognized hadith source.
- Never present an unattributed grading as a project conclusion.
- Distinguish between the source of the narration and the source of the grading.
- Record the relevant hadith number, book/chapter, volume/page, edition, database locator, or other stable locator where available.
- If multiple gradings are recorded, attribute each one separately.

## 5. المفردات — Key Vocabulary

- Keep this section primarily linguistic.
- Prefer reliable Arabic dictionaries, classical lexicons, hadith commentaries, and recognized scholarly explanations.
- Record the source for meanings that are not obvious or that carry interpretive significance.
- Do not turn vocabulary notes into unsourced religious benefits or rulings.

## 6. شرح الحديث — Explanation

### Dorar al-Sunniyyah workflow

When Dorar al-Sunniyyah is used:

1. Locate the correct hadith page.
2. Record the direct link.
3. Ask the user to copy and paste the relevant substantial **شرح الحديث** text into the research conversation.
4. Preserve the supplied Dorar explanation exactly as provided.
5. Do not rewrite, shorten, merge, or paraphrase the supplied Dorar text unless the user explicitly requests a separate adaptation.
6. Clearly distinguish preserved Dorar text from notes taken from other commentaries.

Dorar may be used as a research gateway, but attributed scholarly material should be traced to the original work whenever possible.

## 7. الفوائد — Sourced Benefits

**No benefit may be included unless it is attributed to a named scholarly source and can be traced back to an identifiable original text or book.**

The project must not independently derive religious benefits for publication.

For every proposed benefit, record where possible:

- scholar;
- original Arabic text;
- book/source;
- edition or publication details when material;
- volume/page, hadith number, chapter, section, or other locator;
- direct link when available;
- verification status;
- verification notes.

If the original scholarly source cannot be inspected, the benefit must not be treated as VERIFIED or finalized.

A benefit found only in a secondary source may be retained as research material with the appropriate lower verification status, but must not be silently promoted to final companion text.

## 8. تطبيقات ذكرها أهل العلم — Scholarly Applications

The project must not independently invent practical applications, scenarios, spiritual exercises, or behavioral prescriptions for publication.

Only include an application, example, or situation when it can be traced to:

- a named scholar; and
- an identifiable source containing the supporting text or clearly documented application.

Use the heading **تطبيقات ذكرها أهل العلم**.

Record the original supporting text and source locator where possible.

If no verified application is located, state:

**No verified scholarly application located.**

## 9. AI research boundary

AI may:

- search;
- organize;
- compare sources;
- translate;
- index;
- summarize research notes;
- help locate original texts;
- format verified evidence.

AI may not independently create for publication:

- religious rulings;
- hadith benefits;
- spiritual conclusions;
- practical applications;
- claims of consensus.

Generated research notes must never be mistaken for sourced scholarly material.

## 10. Verification levels

Use only these labels:

### VERIFIED

The original source was inspected and the relevant text, attribution, and locator were checked against it.

### PARTIALLY VERIFIED

A reliable secondary source, recognized research gateway, catalog record, quotation, or attribution was found, but the original source has not yet been inspected sufficiently to confirm the claim.

### UNVERIFIED

An attribution or claim was found but has not been confirmed, or the evidence is presently too weak to rely on.

Only **VERIFIED** material should normally enter the final companion.

## 11. Source priority

Prefer sources in this order:

1. Primary hadith collections.
2. Classical hadith commentaries.
3. Original books of recognized scholars.
4. Official scholarly sources.
5. Dorar al-Sunniyyah.
6. Reliable secondary research tools.

A lower-priority source may help locate material, but it does not replace original-source verification when the original is reasonably obtainable.

## 12. Evidence and citation requirements

A citation is not merely a link. For any claim intended for publication, record enough information for another researcher to locate and inspect the supporting passage.

Where applicable, include:

- author/scholar;
- work title;
- editor or edition when needed to disambiguate;
- publisher and year when useful;
- volume/page;
- hadith/chapter/section number;
- stable URL;
- date accessed for online sources;
- exact original-language evidence for benefits and applications;
- verification status.

Do not cite a search-result snippet as evidence.

Do not use an AI-generated quotation, reconstructed wording, or unverified transcription as original source text.

## 13. Verification gate for final material

Before an item is marked VERIFIED, confirm:

- the original source itself was inspected;
- the attributed scholar or author matches the source;
- the quoted or summarized material is actually present;
- the locator is sufficient to find it again;
- the wording has not been strengthened beyond the source;
- any translation is faithful to the source;
- the item belongs in the section where it is being used.

Before a hadith entry is treated as publication-ready, review every substantive claim in sections 2–6 and ensure its evidence status is visible.

## 14. Honest incompleteness

Never fill a missing section merely to make an entry look complete.

Approved status language includes:

- **Research incomplete**
- **No verified scholarly benefit located.**
- **No verified scholarly application located.**
- **Original source not yet inspected.**
- **Attribution found; verification pending.**

## 15. Repository discipline

- Keep one hadith per entry file unless the project explicitly changes this convention.
- Use stable source IDs from `sources/source-register.md` when practical.
- Keep verification notes in the hadith entry or in an explicitly linked verification record.
- Update `index/hadith-index.md` when an entry is created or its research status materially changes.
- Do not erase uncertainty; resolve it or record it.
- If these rules conflict with a faster or more convenient research method, these rules prevail.
