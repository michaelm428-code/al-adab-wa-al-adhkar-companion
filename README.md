# Al-Adab wa al-Adhkar Companion

A research repository for a carefully sourced companion to *Al-Adab wa al-Adhkar*.

GitHub is the permanent source of truth for verified research, source records, entry status, and publication-ready material. ChatGPT and other research tools are working environments only.

## Governing rules

All work in this repository must follow [PROJECT_RULES.md](PROJECT_RULES.md). Accuracy and traceability take priority over completeness.

The central rule is simple:

> No religious benefit or practical application enters the companion unless it is attributed to a named scholarly source and traceable to an identifiable original text or book.

Historical/contextual claims are held to the same traceability standard.

## Standard hadith entry

Every hadith entry uses these seven sections:

1. **نص الحديث — Hadith Text**
2. **المصدر والحكم — Source and Grading**
3. **المفردات — Key Vocabulary**
4. **شرح الحديث — Explanation**
5. **الفوائد — Sourced Benefits**
6. **تطبيقات ذكرها أهل العلم — Scholarly Applications**
7. **Sources and Verification Status**

The explanation section also records:

- whether the hadith is standalone, excerpted, abridged, or part of a longer narration;
- the verified longer version when one exists;
- sourced information about time, place, occasion, audience, and circumstances;
- the Dorar explanation when used;
- substantial/full sourced commentary from recognized scholarly works.

Use [templates/hadith-entry-template.md](templates/hadith-entry-template.md) for every new entry.

## Base text

The project base text is:

**عبد المحسن بن محمد القاسم، متون طالب العلم — المستوى الأول: الأذكار والآداب، الطبعة الأولى، 1445هـ / 2024م.**

See `sources/source-register.md` for the source record.

The wording printed in this base text determines the companion's sequence and the text being investigated. Longer narrations and variants are preserved separately rather than silently substituted for it.

## Repository structure

- `hadith/` — individual hadith research entries; one file per hadith.
- `templates/` — controlled templates for hadith entries and evidence records.
- `sources/` — source policy and the project-wide source register.
- `verification/` — verification definitions, workflow, and publication gates.
- `index/` — project-wide hadith index and research status.
- `PROJECT_RULES.md` — binding research and publication rules.

## Verification levels

- **VERIFIED** — the original source has been inspected and the cited material has been checked against it.
- **PARTIALLY VERIFIED** — a reliable secondary source or gateway has been found, but the original source has not yet been inspected.
- **UNVERIFIED** — an attribution or claim has been found but has not been confirmed.

Only **VERIFIED** material should normally enter the final companion.

## Working sequence

1. Locate the hadith in the base text and preserve its wording exactly.
2. Verify its underlying primary source.
3. Determine whether it is part of a longer narration and preserve the verified longer version when applicable.
4. Verify grading with explicit attribution.
5. Research vocabulary from reliable linguistic and scholarly sources.
6. Investigate sourced time, place, occasion, audience, and circumstances.
7. Locate the correct Dorar al-Sunniyyah page when Dorar is used.
8. Obtain substantial Dorar explanation text from the user and preserve that supplied text exactly.
9. Research substantial/full commentary in original scholarly works.
10. Locate explicitly stated scholarly benefits.
11. Locate documented scholarly applications.
12. Trace attributed benefits and applications to original works.
13. Record verification status and evidence.
14. Update the project index.
15. Treat the entry as publication-ready only after the verification gate is satisfied.

It is acceptable—and preferable—to leave an area explicitly incomplete rather than fill a gap with unsupported material.
