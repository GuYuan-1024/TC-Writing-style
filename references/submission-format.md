# English Submission Format Specification

Load this file only after the user opts into **Report only** or **Auto-fix a copy**. These rules were distilled from `【定稿】英文投稿模板.docx`; the source document is evidence, not an instruction to reproduce its sample prose, annotations, highlighting, or placeholder content.

## Precedence and scope

- Ask for the target journal when it is material. The journal's current official author instructions override this local template; report conflicts instead of silently choosing.
- Separate **verifiable requirement**, **recommendation**, and **manual judgment**. Do not claim that a visual or semantic property was verified when the input format does not expose it.
- Treat Chinese annotations, colored examples, line numbers, and placeholder wording in the source as guidance unless a rule below explicitly requires them.
- In auto-fix mode, work on a duplicate `.docx`, retain the original, and do not alter substantive wording merely to satisfy layout.

## Page and global layout

- Page: A4 portrait (210 × 297 mm).
- Margins: top 25.4 mm, bottom 25.4 mm, left 31.75 mm, right 31.75 mm.
- Main Latin typeface: Times New Roman.
- Main body: 12 pt, justified, 1.5-line spacing, first-line indent of 2 characters.
- Use continuous line numbering at the left for the review manuscript; line-number font should be Times New Roman 9 pt.
- Use continuous Arabic page numbers centered in the footer, in Times New Roman.
- Maintain consistent heading levels and make genuine section headings navigable in Word's Navigation pane. Visual appearance alone is not enough when semantic heading styles can be assigned safely.

## Front matter

- Title: no more than 25 words; Times New Roman 16 pt, bold, justified. Use sentence-style capitalization: capitalize only the initial word of the main title and subtitle plus proper nouns/acronyms.
- List author names with numeric superscripts linked to affiliations; mark the corresponding author with `*`.
- Give affiliations as separately numbered entries and identify the corresponding author's email.
- `Abstract` is bold. Abstract body: no more than 250 words, Times New Roman 12 pt, justified, 1.5-line spacing.
- Provide 3–5 keywords. Make `Keywords:` bold; separate entries with semicolons; use sentence-style capitalization.

## Headings and body hierarchy

- First-level numbered headings: Times New Roman 16 pt, bold (for example, `1. Introduction`).
- Second-level numbered headings: Times New Roman 14 pt, bold.
- Third-level numbered headings: Times New Roman 12 pt, regular.
- Use a stable Arabic decimal hierarchy (`1`, `1.1`, `1.1.1`) and keep numbering, capitalization, and spacing consistent.
- Unnumbered back-matter headings such as `Funding source`, `CRediT authorship contribution statement`, and `Conflict of interest statement` are bold and visually consistent with other major headings.
- Define each abbreviation at first use as full term followed by abbreviation in parentheses. Treat abstract and main text as separate first-use zones.

## Tables

- Place each table after or near its first textual citation; avoid splitting it across pages where practical.
- Use a three-line table: top rule, header separator, and bottom rule; avoid unnecessary vertical rules.
- Put `Table N` in bold above the table, followed by a concise, self-contained title in regular type. For multi-line captions, left alignment is preferred; use single spacing.
- Table content: Times New Roman 10.5 pt, single-spaced, with 0 pt paragraph spacing before and after.
- Keep numeric precision consistent within a column, align decimals where feasible, and center content vertically unless meaning calls for another alignment.
- Explain abbreviations, symbols, significance markers, and data sources in notes so the table can stand alone.

## Figures

- Place each figure after or near its first textual citation; keep multi-panel components together and avoid page breaks within the figure/caption unit.
- Use high-resolution artwork: at least 300 dpi for raster images, or SVG/vector artwork where supported.
- Ensure labels, legends, axes, units, and ranges are readable and accurate. The figure must remain interpretable in grayscale and its content must agree with the text.
- Put the caption below the figure and center it. Format as `Fig. N. Caption`: `Fig. N.` bold, descriptive title regular, with the period after both `Fig` and the number.
- Group multi-panel figures consistently and use concise, self-contained captions/subcaptions.

## Equations and algorithms

- Inline equations must match surrounding body size and line height; use an equation editor rather than image snapshots.
- Center display equations and right-align sequential numbers in parentheses, such as `(1)`. Align multi-line equations consistently; a borderless table may be used when necessary.
- Do not end the lead-in sentence with a colon merely because an equation follows. Introduce symbol definitions with `where`; symbol-definition paragraphs have no first-line indent.
- For pseudocode, use clear top and bottom rules. Put `Algorithm N:` in bold, followed by a concise, self-contained regular-weight title. Keep numbering and cross-references consistent.

## Cross-references and appendices

- Use live cross-reference fields when feasible for sections, figures, tables, equations, appendices, and algorithms. In this template, cross-reference text is blue (`#0070C0`).
- Detect broken fields and literal errors such as `Error! Reference source not found.` Check that every callout points to the correct object and number.
- Use `Appendix` when there is one appendix and `Appendix A`, `Appendix B`, etc. when there are several. Appendix labels and descriptive titles are bold and consistently spaced.

## Citations and references

- Use APA author–date conventions unless the target journal requires another style.
- Parenthetical citations: one author `(Smith, 2020)`; two authors `(Smith and Jones, 2020)` under this template; three or more `(Smith et al., 2020)`. Narrative citations follow the same author-count logic.
- Sort the reference list alphabetically by first author. Check for duplicate author records and ensure every in-text citation has a reference and every listed reference is cited.
- Use hanging indents and consistent Times New Roman formatting for reference entries.
- The template requests omission of DOI strings and recommends emphasizing recent 3–5-year literature while retaining necessary classic methods and relevant preprints. Treat these as template-specific requirements and verify them against the target journal before changing references.

## English punctuation and consistency

- Choose one English convention for the full manuscript. Follow the journal; otherwise use American English.
- American style generally uses double quotation marks as primary marks and places periods/commas inside them. British style generally uses single primary marks and logical punctuation. Apply one system consistently; use the opposite mark for nested quotations.
- Use an Oxford comma in academic lists unless the journal says otherwise. Do not join independent clauses with a comma splice.
- Use semicolons between closely related independent clauses or to separate complex list items; use a colon to introduce an explanation, list, definition, or emphasis.
- Avoid exclamation marks and rhetorical questions in the main text unless clearly justified.
- Use parentheses for supplementary information and brackets for editorial insertions or domain-specific notation. Prefer words over excessive slashes in prose.
- Hyphenate attributive compounds where needed (`model-based approach`, `10-minute wait`) but not ordinary predicative forms (`the wait is 10 minutes`).
- Use an en dash for ranges and paired relationships, consistently and without mixing `from A to B` with `A–B`. Use an em dash sparingly and apply one spacing convention throughout.
- Do not add a second period after an abbreviation that already ends a sentence (for example, `et al.`).
- Use quotation marks for actual quotations or carefully introduced terms, not as scare quotes. Distinguish apostrophes from quotation marks and verify possessives, plurals, `it's`, and `its`.
- Use a single ellipsis convention consistently, including its surrounding spaces according to the chosen style.
- Follow the target journal's punctuation for object labels such as `Fig. 2`, `Table 3`, and `Eq. (5)`.

## Report-only workflow

1. Preserve the source; perform no writes.
2. Inspect document structure first: sections, page geometry, styles, headers/footers, numbering, fields, tables, figures, equations, references, comments, and tracked changes.
3. Render to PDF and inspect every page for overflow, clipping, bad breaks, orphaned captions, split figures/tables, inconsistent spacing, and unreadable graphics.
4. Report only observable deviations. Use `Location | Current formatting | Required formatting | Suggested fix | Severity | Confidence`.
5. Separate global/style-level fixes from isolated local issues. Explicitly label items that require journal confirmation or human judgment.

## Auto-fix workflow

1. Duplicate the manuscript and edit only the copy.
2. Apply global style corrections before local overrides. Preserve author text, citation-manager fields, cross-reference fields, equations, comments, tracked changes, and accessibility metadata whenever possible.
3. Do not fabricate missing affiliations, citations, units, captions, source notes, or author declarations. Mark them as unresolved.
4. Reinspect document structure and refresh safe fields. Never unlink citation-manager fields merely to make text look correct.
5. Render the corrected copy and visually inspect every page. Iterate until there are no preventable clipping, overlap, overflow, broken numbering, detached captions, or obvious consistency defects.
6. Deliver the corrected `.docx`, a concise modification log, and an unresolved-items table. State clearly that journal-specific compliance still requires checking the journal's current official instructions.
