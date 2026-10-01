# Verification and Citation Workflow

This workflow is the required path from research lead to final companion material.

## 1. Open the entry

- Confirm the topic number and title from `index/book-structure.md`.
- Confirm the narration's local number within that topic.
- Assign the next internal project ID, e.g. `H0001`.
- Name the file by topic and local narration number, e.g. `001-01.md`.
- Create the hadith file from `templates/hadith-entry-template.md`.
- Record both the printed page and PDF page.
- Mark the entry **Research incomplete**.
- Add it to `index/hadith-index.md`.
- Do not begin with a target number of benefits or applications. Completeness must not drive invention.

## 2. Establish the base wording and primary source

1. Locate the hadith in the project's base text, *Al-Adab wa al-Adhkar*.
2. Preserve that wording exactly.
3. Preserve all base-book footnotes attached to that narration exactly as printed.
4. Classify those footnotes descriptively (for example: brief takhrīj, lexical gloss, or other note) without altering their wording.
5. Record both the printed page and PDF page.
6. Identify the underlying hadith collection or collections.
7. Inspect the selected primary source directly.
8. Record the collection, locator, edition/database, and direct link.
9. Keep materially different variants separate.

A text is VERIFIED only after the relevant source itself has been inspected.

## 3. Determine whether a longer narration exists

Every hadith must be checked for a longer form.

1. Compare the base wording against primary-source narrations.
2. Determine whether it is standalone, excerpted, abridged, or one variant among others.
3. Search for a longer narration containing the same passage when evidence points to one.
4. Inspect the primary source containing the longer wording.
5. Preserve the longer wording exactly in the explanation section.
6. Record its source and locator.
7. Describe only the demonstrable relationship between the shorter and longer versions.
8. Do not merge separate variants into a synthetic narration.

If no longer form is verified, record:

**No verified longer version located.**

If unresolved, record:

**Longer-version research incomplete.**

## 4. Verify source and grading

For every grading:

1. Record the exact grading.
2. Name the scholar or recognized source responsible for it.
3. Inspect the source containing that grading whenever possible.
4. Record a re-checkable locator.
5. Assign VERIFIED, PARTIALLY VERIFIED, or UNVERIFIED.

Do not convert a database label into an unattributed project judgment.

## 5. Record vocabulary

- Prefer linguistic sources and recognized scholarly explanations.
- Cite interpretively significant meanings.
- Keep vocabulary separate from benefits, rulings, and applications.

## 6. Investigate time, place, and circumstances

Search the primary narration, its longer forms, related narrations, and recognized commentary/historical works for documented contextual information.

Check specifically for:

- time or period;
- location;
- journey, battle, pilgrimage, visit, illness, meal, gathering, sermon, or other event;
- person or group addressed;
- question or incident that prompted the statement;
- action occurring when the words were spoken;
- other circumstances material to understanding the narration.

For each contextual claim:

1. capture the exact supporting evidence or sufficiently precise source note;
2. identify whether the context is explicit in the narration or supplied by a named scholar;
3. record the source and locator;
4. assign a verification status.

Do not reconstruct context from plausibility, general chronology, or biography and present it as fact.

If no verified context is found, record:

**No verified information on time, place, or circumstances located.**

## 7. Build the full commentary record

### Dorar

When Dorar is used:

1. Locate the correct hadith page.
2. Record the direct URL.
3. Have the user paste the relevant substantial **شرح الحديث** into the working conversation.
4. Preserve the supplied text exactly in the entry.
5. Do not silently edit, condense, or merge it.
6. If an attributed statement inside Dorar is needed as independent evidence for a benefit or application, trace that attribution to the original work before finalizing it.

### Original scholarly commentaries

Research substantial commentary rather than relying on a single short explanation.

For each important commentary:

1. identify the scholar and work;
2. inspect the original work where reasonably possible;
3. capture the relevant Arabic passage or sufficiently precise research record;
4. record edition and locator;
5. keep separate scholars' explanations distinguishable;
6. note which portion of the hadith or longer narration the commentary addresses;
7. assign verification status.

Do not collapse multiple scholars into an unattributed "scholars say" synthesis.

## 8. Research benefits

For each possible benefit:

1. Treat it as a research lead, not a project conclusion.
2. Identify the named scholar.
3. Locate the original work.
4. Inspect the original passage.
5. Preserve the relevant Arabic wording.
6. Record book, edition, volume/page or equivalent locator, and link.
7. Confirm that the proposed companion wording does not add a stronger claim.
8. Mark VERIFIED only after those checks succeed.

If only a secondary attribution is found, use PARTIALLY VERIFIED or UNVERIFIED as appropriate.

If nothing meets the standard, write:

**No verified scholarly benefit located.**

## 9. Research scholarly applications

Apply the same evidence standard used for benefits.

An application must be something traceable to a named scholar and an identifiable supporting source. Do not create modern scenarios and present them as scholarly applications unless the source itself supports that use.

If nothing meets the standard, write:

**No verified scholarly application located.**

## 10. Citation record

For each publication-relevant item, capture enough metadata to re-open the evidence:

- evidence ID;
- scholar/author;
- work title;
- edition/editor when needed;
- publisher/year when useful;
- volume/page;
- hadith/chapter/section or other locator;
- direct or stable URL;
- access date for online material;
- original-language supporting text for benefits and applications;
- exact supporting evidence for historical/contextual claims;
- verification status;
- concise verification notes.

Use `templates/evidence-record-template.md` when a fuller standalone record is helpful.

## 11. Status transition rules

### UNVERIFIED → PARTIALLY VERIFIED

Use when a credible attribution or secondary source has been found but the original source has not yet been inspected.

### PARTIALLY VERIFIED → VERIFIED

Move only after inspecting the original source and confirming the attribution, supporting passage, and locator.

### VERIFIED → lower status

Downgrade immediately if later checking reveals an attribution problem, mismatched edition, missing passage, inaccurate transcription, contextual overstatement, or wording that overstates the source.

Verification is reversible.

## 12. Publication gate

Before an item is included in final companion text, confirm:

- its verification status is visible;
- the evidence supports the exact claim being made;
- the original source was inspected where required;
- the locator can be followed by another researcher;
- no AI-derived religious benefit, ruling, spiritual conclusion, application, consensus claim, or invented historical context has been inserted.

Before an entry is marked publication-ready, confirm:

- the longer-narration investigation is complete or transparently marked incomplete;
- any longer version included has been source-checked;
- historical/contextual claims are individually sourced;
- substantial commentary research has been completed or transparently marked incomplete;
- all substantive material in sections 2–6 has been reviewed;
- the project index has been updated.

## 13.1 Prepare the publication file

After the research dossier has completed the major-source pass:

1. Create or update the matching file in `publication/`.
2. Include only VERIFIED material.
3. Exclude every PARTIALLY VERIFIED or UNVERIFIED claim, grading, benefit, application, or contextual assertion.
4. Keep the base hadith text unchanged.
5. Keep longer narrations and variants separate.
6. Preserve user-supplied Dorar commentary exactly when included.
7. Attribute scholarly commentary, benefits, and applications by name.
8. Audit the publication file against the research dossier.
9. Mark it **مسودة تحريرية**, **جاهز للمراجعة النهائية**, or **معتمد للنشر**.
10. Update `CURRENT_STATUS.md`.

A research dossier may remain technically incomplete because of an optional unresolved lead while the publication file advances, provided that lead is not used in publication.

## 13. Citation discipline

- Prefer the original source over a quotation of that source in a secondary work.
- Never cite a search-result snippet as evidence.
- Never fabricate page numbers, hadith numbers, quotations, editions, dates, places, occasions, or URLs.
- Do not treat an inaccessible citation as VERIFIED merely because it looks precise.
- When page numbering differs by edition, record the edition.
- For scans, distinguish printed page number from viewer/PDF page when necessary.
- For web sources, use the direct content page rather than a homepage or search page.

## 14. Research stop rule

Stop and record uncertainty when the evidence does not support promotion to VERIFIED.

Acceptable outcomes include:

- **Research incomplete**
- **Longer-version research incomplete**
- **No verified longer version located**
- **No verified information on time, place, or circumstances located**
- **Commentary research incomplete**
- **Original source not yet inspected**
- **Attribution found; verification pending**
- **No verified scholarly benefit located**
- **No verified scholarly application located**
