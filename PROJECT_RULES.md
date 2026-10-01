# PROJECT_RULES.md

## 1. Authority and scope

These rules govern all research, drafting, verification, and repository updates for the **Al-Adab wa al-Adhkar Companion**.

GitHub is the permanent source of truth. Working notes outside the repository are provisional until they are checked and committed here.

Accuracy, traceability, fidelity to sources, and preservation of context take priority over completeness or speed.

## 1.1 Future-chat startup protocol

Every future chat or research session must begin by reading, in order:

1. `START_HERE.md`
2. `PROJECT_RULES.md`
3. `verification/WORKFLOW.md`
4. `index/book-structure.md`
5. `CURRENT_STATUS.md`
6. the current `hadith/` research file
7. the corresponding `publication/` file, if one exists
8. `sources/source-register.md`

Do not rely on conversational memory when the repository can establish the rule, evidence state, or current stopping point.

Any new permanent research rule or workflow change must be written into the repository before the project proceeds beyond that change.

At the end of each substantial work session, update `CURRENT_STATUS.md`.

## 2. Publication language

The final companion is an **Arabic-only book**.

All publication-facing content must therefore be written in Arabic, including:

- section and subsection headings;
- explanatory prose;
- labels and captions;
- verification notes visible in the book;
- status language;
- vocabulary explanations;
- contextual notes;
- commentary organization;
- benefit and application wording;
- source and verification summaries.

English may be used only in private/internal working notes when useful for research. Such notes must not enter publication text.

Technical evidence IDs and source IDs such as `SRC-0001`, `CMT01`, `B01`, and `A01` may remain alphanumeric for repository management, but they must not force English wording into the published book.

Canonical Arabic verification labels are:

- **موثَّق** — VERIFIED
- **موثَّق جزئيًا** — PARTIALLY VERIFIED
- **غير موثَّق** — UNVERIFIED

Canonical Arabic incompleteness language includes:

- **البحث غير مكتمل.**
- **البحث عن الرواية الأطول غير مكتمل.**
- **لم يُعثر على رواية أطول موثقة.**
- **لم يُعثر على معلومات موثقة عن الزمان أو المكان أو ملابسات الحديث.**
- **البحث في الشروح غير مكتمل.**
- **لم يُعثر على فائدة موثقة عن أهل العلم.**
- **لم يُعثر على تطبيق موثق ذكره أهل العلم.**
- **لم يُراجع المصدر الأصلي بعد.**
- **وُجد العزو، والتوثيق قيد المراجعة.**

## 3. Standard hadith structure

Every hadith entry must contain, in this order:

1. **نص الحديث**
2. **المصدر والحكم**
3. **المفردات**
4. **شرح الحديث**
5. **الفوائد**
6. **تطبيقات ذكرها أهل العلم**
7. **المصادر وحالة التوثيق**

Use the controlled template in `templates/hadith-entry-template.md`.

### Numbering and base-text locator

The bracketed numbers **[1]–[142] in the base book are topic numbers, not global hadith numbers**. Individual narration numbering restarts within each topic.

Every entry must therefore record:

- the internal project ID, e.g. `H0001`;
- the topic number and topic title;
- the narration number within that topic;
- the printed page number;
- the PDF page number;
- a stable filename based on topic and local narration number, e.g. `001-01.md`.

Do not describe topic **[1]** as “Hadith 1” in the base book. See `index/book-structure.md`.

Within **شرح الحديث**, every entry must explicitly investigate:

- whether the selected text is a complete standalone narration, an excerpt, an abridgment, or a wording that belongs to a longer narration;
- the verified longer version or versions when they exist;
- time, place, event, audience, question, incident, or other circumstances of the narration when reliable evidence exists;
- substantial/full sourced commentary from recognized scholarly works.

## 4. نص الحديث

- Preserve the hadith text exactly as found in the selected source.
- Do not silently rewrite, normalize, shorten, combine, or harmonize narrations.
- Record the exact source and locator used for the preserved text.
- If variants are relevant, keep them distinct and identify their sources separately.
- Any normalization made solely for search or indexing must never replace the preserved source text.
- The wording used by *Al-Adab wa al-Adhkar* must be preserved as the project's base-text wording even when a longer or different wording exists elsewhere.
- Preserve all base-book footnotes attached to the narration exactly as printed.
- Keep the author's brief takhrīj notes, lexical glosses, and other footnotes visibly distinct from later project research.
- A brief source note in the base book, such as “رواه مسلم” or “متفق عليه”, is part of the base-book apparatus and must still be independently checked against the original hadith source during verification.

## 5. المصدر والحكم

- Every grading must be attributed to a named scholar or a recognized hadith source.
- Never present an unattributed grading as a project conclusion.
- Distinguish between the source of the narration and the source of the grading.
- Record the relevant hadith number, book/chapter, volume/page, edition, database locator, or other stable locator where available.
- If multiple gradings are recorded, attribute each one separately.

## 6. المفردات

- Keep this section primarily linguistic.
- Prefer reliable Arabic dictionaries, classical lexicons, hadith commentaries, and recognized scholarly explanations.
- Record the source for meanings that are not obvious or that carry interpretive significance.
- Do not turn vocabulary notes into unsourced religious benefits or rulings.

## 7. شرح الحديث

The explanation section is intended to preserve the narration's **full scholarly and historical context**, not merely provide a short paraphrase.

### 7.1 Relationship to a longer narration

For every hadith, explicitly investigate whether the wording in *Al-Adab wa al-Adhkar* is:

- a complete standalone narration;
- an excerpt from a longer narration;
- an abridged form of a longer narration;
- one wording among materially different variants;
- or presently unclear.

Do not infer that a narration is complete merely because a database page displays only that wording.

If a longer version exists:

1. identify the primary source containing it;
2. preserve the longer text exactly as found in the selected verified source;
3. record its chain/source locator as appropriate;
4. explain, descriptively, how the companion's shorter wording relates to the longer version;
5. keep variant narrations separate rather than silently combining them;
6. record verification status.

If no verified longer version is located, publication text must use:

**لم يُعثر على رواية أطول موثقة.**

If research is unfinished:

**البحث عن الرواية الأطول غير مكتمل.**

### 7.2 Time, place, and circumstances

For every hadith, investigate whether reliable sources identify any of the following:

- time or approximate period;
- place;
- journey, battle, pilgrimage, visit, illness, meal, gathering, sermon, or other event;
- question or incident that prompted the statement;
- person or group addressed;
- action taking place when the words were spoken;
- other relevant circumstances of transmission.

Every contextual statement must be sourced and traceable.

Distinguish clearly between:

- explicitly stated context in a primary narration;
- scholarly identification of context in a recognized commentary or historical work;
- unsupported reconstruction or inference.

Unsupported historical reconstruction must not enter the companion as fact.

If no verified contextual information is located, publication text must use:

**لم يُعثر على معلومات موثقة عن الزمان أو المكان أو ملابسات الحديث.**

### 7.3 Full scholarly commentary

The project should seek substantial commentary rather than reducing explanation to a few unsourced summary sentences.

For each commentary source used, record:

- scholar;
- work;
- original Arabic text or the relevant substantial passage where appropriate;
- edition;
- volume/page, hadith/chapter/section, or other locator;
- direct/stable link when available;
- verification status.

Prefer original commentary works over quotations of those works in secondary sources.

When several major commentaries materially illuminate different parts of the narration, preserve those strands separately rather than collapsing them into an unattributed synthesis.

A project summary may organize verified commentary, but it must not introduce new religious conclusions or present AI-generated synthesis as a scholar's wording.

### 7.4 Dorar al-Sunniyyah workflow

When Dorar al-Sunniyyah is used:

1. Locate the correct hadith page.
2. Record the direct link.
3. Ask the user to copy and paste the relevant substantial **شرح الحديث** text into the research conversation.
4. Preserve the supplied Dorar explanation exactly as provided.
5. Do not rewrite, shorten, merge, or paraphrase the supplied Dorar text unless the user explicitly requests a separate adaptation.
6. Clearly distinguish preserved Dorar text from notes taken from other commentaries.

Dorar may be used as a research gateway, but attributed scholarly material should be traced to the original work whenever possible.

## 8. الفوائد

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

## 9. تطبيقات ذكرها أهل العلم

The project must not independently invent practical applications, scenarios, spiritual exercises, or behavioral prescriptions for publication.

Only include an application, example, or situation when it can be traced to:

- a named scholar; and
- an identifiable source containing the supporting text or clearly documented application.

Use the heading **تطبيقات ذكرها أهل العلم**.

Record the original supporting text and source locator where possible.

If no verified application is located, publication text must use:

**لم يُعثر على تطبيق موثق ذكره أهل العلم.**

## 10. AI research boundary

AI may:

- search;
- organize;
- compare sources;
- translate research material when needed;
- index;
- summarize research notes;
- help locate original texts;
- compare short and long narrations descriptively;
- organize sourced historical context;
- format verified evidence.

AI may not independently create for publication:

- religious rulings;
- hadith benefits;
- spiritual conclusions;
- practical applications;
- claims of consensus;
- invented historical circumstances;
- speculative reasons for why a hadith was said.

Generated research notes must never be mistaken for sourced scholarly material.

## 11. Verification levels

Use these canonical Arabic publication labels:

### موثَّق

The original source was inspected and the relevant text, attribution, context, and locator were checked against it.

### موثَّق جزئيًا

A reliable secondary source, recognized research gateway, catalog record, quotation, or attribution was found, but the original source has not yet been inspected sufficiently to confirm the claim.

### غير موثَّق

An attribution or claim was found but has not been confirmed, or the evidence is presently too weak to rely on.

Only **موثَّق** material should normally enter the final companion.

## 12. Source priority

Prefer sources in this order:

1. Primary hadith collections.
2. Classical hadith commentaries.
3. Original books of recognized scholars.
4. Official scholarly sources.
5. Dorar al-Sunniyyah.
6. Reliable secondary research tools.

For historical circumstances, also use early biographical, sīrah, maghāzī, ṭabaqāt, and historical works when directly relevant, while recording their evidentiary status.

A lower-priority source may help locate material, but it does not replace original-source verification when the original is reasonably obtainable.

## 13. Evidence and citation requirements

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
- exact supporting evidence for claimed historical context;
- verification status.

Do not cite a search-result snippet as evidence.

Do not use an AI-generated quotation, reconstructed wording, or unverified transcription as original source text.

## 14. Verification gate for final material

Before an item is marked **موثَّق**, confirm:

- the original source itself was inspected;
- the attributed scholar or author matches the source;
- the quoted or summarized material is actually present;
- the locator is sufficient to find it again;
- the wording has not been strengthened beyond the source;
- any translation used in research is faithful to the source;
- the item belongs in the section where it is being used.

Before a hadith entry is treated as publication-ready, confirm additionally:

- the relationship to any longer narration has been investigated;
- any included longer narration was checked against its source;
- contextual claims about time, place, audience, event, or circumstance are individually sourced;
- substantial commentary research has been completed or explicitly marked incomplete;
- every substantive claim in sections 2–6 has visible evidence status;
- all publication-facing wording is Arabic.

## 14.1 Separation of research and publication

- `hadith/` contains the full research dossier, including PARTIALLY VERIFIED and UNVERIFIED leads.
- `publication/` contains only reader-facing Arabic material that has passed the verification gate.
- A partially verified research lead does not block publication if it is excluded from the publication file and all included material is VERIFIED.
- Do not silently promote an unresolved research lead into publication prose.
- Publication readiness is assessed against the material actually included in the publication file.

## 15. Honest incompleteness

Never fill a missing section merely to make an entry look complete.

Approved Arabic status language includes:

- **البحث غير مكتمل.**
- **لم يُعثر على رواية أطول موثقة.**
- **البحث عن الرواية الأطول غير مكتمل.**
- **لم يُعثر على معلومات موثقة عن الزمان أو المكان أو ملابسات الحديث.**
- **البحث في الشروح غير مكتمل.**
- **لم يُعثر على فائدة موثقة عن أهل العلم.**
- **لم يُعثر على تطبيق موثق ذكره أهل العلم.**
- **لم يُراجع المصدر الأصلي بعد.**
- **وُجد العزو، والتوثيق قيد المراجعة.**

## 16. Repository discipline

- Keep one hadith per entry file unless the project explicitly changes this convention.
- Use stable source IDs from `sources/source-register.md` when practical.
- Keep verification notes in the hadith entry or in an explicitly linked verification record.
- Update `index/hadith-index.md` when an entry is created or its research status materially changes.
- Do not erase uncertainty; resolve it or record it.
- If these rules conflict with a faster or more convenient research method, these rules prevail.
