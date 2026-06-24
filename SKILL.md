---
name: template-based-apa-professional-paper
description: Create or review template-based APA 7th edition professional papers with running head, title page, abstract, body text, APA headings, author-date citations, and reference list formatting.
---

**Bundled Template Assets**

Use the **Skill directory** shown above as the base directory. All relative paths below resolve from that directory.

Bundled files:
- ./apa-professional-paper-template.docx
- ./create_apa_professional_paper_template.py

When generating or revising the Word document, copy the bundled template from the Skill directory into the active workspace. Prefer directly editing the copied template. Write a new template only if the bundled template cannot support the requested output.

**Target write language**: {{ product_language }}

For every writing artifact, all user-visible text MUST use {{ product_language }}

# APA Professional Paper

APA professional papers are editable scholarly or professional manuscripts that follow APA 7th edition professional-paper formatting. They use a running head, professional title page, abstract, APA heading levels, author-date citations, and a References list.

## APA Professional Paper Standard

### Source Basis

This skill already contains rules researched and summarized from APA and academic writing-center sources. Do not search again for routine APA professional paper generation.

Search or inspect additional sources only when:

- The user asks for the latest/current APA rule set.
- The user names a specific journal, publisher, university, course, professor, or template.
- The user provides a file/manual that may override generic APA practice.
- A formatting requirement conflicts with the rules below.

Primary source entry points used for this skill:

- APA Style paper format: `https://apastyle.apa.org/style-grammar-guidelines/paper-format`
- APA Style sample papers: `https://apastyle.apa.org/style-grammar-guidelines/paper-format/sample-papers`
- Purdue OWL APA general format: `https://owl.purdue.edu/owl/research_and_citation/apa_style/apa_formatting_and_style_guide/general_format.html`
- Purdue OWL APA 7 professional sample paper: `https://owl.purdue.edu/owl/research_and_citation/apa_style/apa_formatting_and_style_guide/apa_sample_paper.html`
- Purdue OWL APA headings: `https://owl.purdue.edu/owl/research_and_citation/apa_style/apa_formatting_and_style_guide/apa_headings_and_seriation.html`
- Purdue OWL APA reference list rules: `https://owl.purdue.edu/owl/research_and_citation/apa_style/apa_formatting_and_style_guide/reference_list_basic_rules.html`
- Purdue OWL APA in-text citations: `https://owl.purdue.edu/owl/research_and_citation/apa_style/apa_formatting_and_style_guide/in_text_citations_author_authors.html`
- Purdue OWL APA tables and figures: `https://owl.purdue.edu/owl/research_and_citation/apa_style/apa_formatting_and_style_guide/apa_tables_and_figures.html`
- Trent University APA 7 professional paper formatting: `https://www.trentu.ca/academicskills/documentation-guide/apa-style/apa-7-style-formatting-guidelines/apa-7-style-formatting-professional`

Note: APA's official web pages may block automated retrieval. When direct access fails, use the official URLs as the authoritative target and cross-check implementation details with accessible university writing-center pages and sample papers.

### Variant Choice

Default to APA 7 professional paper format.

This default means:

- Professional papers include a running head in the header on every page.
- Professional title pages include title, author names, affiliations, and an author note.
- Abstract page is included by default.
- Student-only elements such as course number/name, instructor, and assignment date are not included unless requested.
- APA professional papers do not normally include a table of contents.

Do not default to:

- APA student paper format unless the user explicitly asks to adapt it.
- Student-only course, instructor, and due-date fields.
- Thesis/dissertation front matter or journal-specific front matter unless requested.
- MLA, Chicago, Harvard, Vancouver, IEEE, or other citation styles.

### Document Setup

- **Use a plain white page background with black text throughout the paper.**
- **Do not use colored heading themes, blue Word default headings, tinted page backgrounds, publisher mastheads, institutional logos, or decorative color blocks unless the user, journal, publisher, or institution explicitly requests them.**
- Paper: Letter, 8.5 x 11 in.
- Margins: 1 in on all sides.
- Font: default to 12 pt Times New Roman. Other APA-accepted readable fonts may be used if requested.
- Line spacing: double-space the entire paper, including title page, abstract, body, block quotes, references, tables, and figure notes.
- Paragraphs: indent the first line of body paragraphs 0.5 in.
- Alignment: left-align text; do not justify.
- Page numbers: top right on every page, starting with title page as page 1.
- Running head: top left on every page, all caps, shortened title, maximum 50 characters including spaces and punctuation. Do not prefix with `Running head:`.
- Keep all text, citations, reference entries, tables, figures, notes, and appendices editable.
- Do not use hidden tables or borderless layout tables for title-page positioning or ordinary layout.

### Headings

Use APA 7 heading levels in order:

- Level 1: centered, bold, title case.
- Level 2: flush left, bold, title case.
- Level 3: flush left, bold italic, title case.
- Level 4: indented, bold, title case, period; text continues on the same line.
- Level 5: indented, bold italic, title case, period; text continues on the same line.

Do not number APA headings.

### Abstracts

Use an abstract page by default for APA professional papers.

- Start on page 2.
- Use the centered bold label `Abstract`.
- Abstract text is one paragraph, double-spaced, not indented.
- Most APA abstracts are concise and usually no more than 250 words unless the journal specifies otherwise.
- Put keywords below the abstract when useful or required. Indent the keyword line 0.5 in; italicize `Keywords:`; separate keywords with commas; do not end the keyword list with a period.

### Citations

Use APA author-date citations.

- Parenthetical citation: `(Smith, 2024)`.
- Narrative citation: `Smith (2024)`.
- Two authors: use `and` in narrative citations and `&` in parenthetical citations: `Smith and Lee (2024)`; `(Smith & Lee, 2024)`.
- Three or more authors: use first author plus `et al.` in every citation unless ambiguity requires more names.
- Direct quotations require a location: `(Smith, 2024, p. 15)` or `(Smith, 2024, para. 4)` when no page is available.
- Multiple works in one parenthetical citation are ordered alphabetically and separated by semicolons.
- Same author/same year works use lowercase letters: `(Smith, 2024a, 2024b)`.
- Secondary citations should be avoided; when unavoidable, use `as cited in` and include only the source actually read in the reference list.

### References

Use APA 7 reference style.

- Invert author names: `Surname, A. A.`
- List up to and including 20 authors. For 21 or more authors, list the first 19, an ellipsis, and the final author.
- Use sentence case for article, chapter, book, report, and webpage titles.
- Use title case for periodical titles.
- Italicize book/report titles and periodical titles/volume numbers.
- Include DOI as a URL when available. Use stable URLs for online works without DOI.
- Do not add retrieval dates unless the content is designed to change over time or the source requires it.

Common models:

Journal article:
`Author, A. A., & Author, B. B. (2024). Title of article in sentence case. Title of Periodical, 12(3), 45-67. https://doi.org/xxxxx`

Book:
`Author, A. A. (2024). Title of book in sentence case. Publisher. https://doi.org/xxxxx`

Edited book chapter:
`Author, A. A. (2024). Title of chapter in sentence case. In E. E. Editor (Ed.), Title of book in sentence case (pp. 10-25). Publisher.`

Webpage:
`Author, A. A. or Group Author. (2024, Month Day). Title of webpage in sentence case. Site Name. URL`

Report:
`Group Author. (2024). Title of report in sentence case (Report No. 123). Publisher. URL`

### Figures/Tables

- Refer to every table and figure in the text before it appears.
- Number tables and figures separately: `Table 1`, `Figure 1`.
- Put the table/figure number in bold.
- Put the title on the next line in italic title case.
- Place notes below the table or figure as needed, beginning with italic `Note.`
- Keep table and figure text readable and double-spaced unless a publisher requests otherwise.
- Use tables and figures only when they help communicate information; do not use tables for ordinary page layout.

## Recommand Structure

Default professional paper structure:

1. Title page.
2. Abstract page.
3. Text/body, beginning on a new page.
4. References, beginning on a new page.
5. Footnotes, tables, figures, appendices, and supplemental materials only when needed or requested.

Title page:

- Running head and page number in the header.
- Full title centered, bold, title case, placed about three to four double-spaced lines below the top margin.
- Author names one double-spaced line below the title.
- Author affiliations directly below author names.
- `Author Note` label centered and bold.
- Author note paragraphs may include ORCID IDs, affiliation changes, disclosures/acknowledgments, and correspondence details. Omit nonapplicable parts.

Body:

- Start on a new page after the abstract.
- Repeat the full title at the top, centered and bold.
- Do not use an `Introduction` heading; the title functions as the first-level heading for the introduction.
- Use headings only where they reflect real section structure.

References:

- Start on a new page.
- Use the centered bold label `References`.
- Double-space all entries.
- Apply 0.5 in hanging indent.
- Alphabetize entries by first author surname or group author name.

## How to Write APA Professional Papers Using the Template

Use the template as the paper blueprint: map the user's content into the recommended APA professional paper structure, preserve APA 7 professional-paper formatting, and fill only the fields that are supported by the user's request or source files.

When generating the final Word paper, directly edit the Python script that creates the `.docx` file. You must implement template changes in the Word-generation `.py` file so that document structure, running head, professional title page, author note, abstract, headings, body formatting, citations, References entries, tables, figures, and notes are reproducible. After editing the script, rerun it to regenerate the Word output and verify the generated document.

## Validation and Fixes

Run validation before making fixes; use the validation reports to identify issues, apply only necessary fixes, then rerun validation before final delivery.

### Mandatory Self-Contained And Source-Grounded Validation

Call `validate_document` through `jupyter_execute`:

```python
import sys
sys.path.insert(0, "/app/skills/common/doc_new_split_agent")
from validate import validate_document

result = await validate_document(
    generated_path="uploaded_files/output.html",
    source_files=[
        {
            "path": "parsed_files/source.md",
            "origin": "uploaded",
            "description": "Parsed text of the user-uploaded source document",
        }
    ],
    user_instruction="""{verbatim user request}""",
)

print(result["verdict"])
print(result["self_contained"]["report"])
if result["source_grounded"]:
    print(result["source_grounded"]["report"])
```
