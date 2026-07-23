# Report Template Map

Canonical template: `templates/报告模板新2026.6.29.docx`.

The template body, its Word comments, styles, tables, and page layout jointly define the report contract. Template comments are formatting instructions. Disease names, datasets, genes, sample counts, thresholds, figures, and conclusions shown in the template are examples only and must never be copied into a real report unless independently supported by that project's proposal and results.

## Output Naming

- Default path: `report/<项目编号>_<YYYYMMDD>_report.docx`.
- If the path exists, append `_v2`, `_v3`, and so on; never overwrite an earlier report.
- Before delivery, remove all placeholders, example content, comments, unresolved tracked changes, and stale table-of-contents fields.

## Page And Typography

- Paper: A4 portrait. Preserve the template section layout and margins: 25.4 mm top/bottom and 31.75 mm left/right.
- Chinese font: 宋体. Western font: Times New Roman. Text is black unless a rule below explicitly assigns a highlight color.
- Cover title: 小二（18 pt）, bold, centered, 1.5 line spacing, and visually centered on the page.
- Project number label and value: 三号（16 pt）, bold, centered, 1.5 line spacing.
- Directory title: 四号（14 pt）, centered. Directory entries: 小四（12 pt）, 1.5 line spacing.
- Heading 1: 二号（22 pt）, bold, black, no first-line indent, 1.5 line spacing.
- Heading 2: 三号（16 pt）, bold, black, no first-line indent, 1.5 line spacing.
- Heading 3, when needed: 四号（14 pt）, bold, black, no first-line indent.
- Body: 小四（12 pt）, justified, first-line indent of 2 Chinese characters, 1.5 line spacing. Use Chinese full-width parentheses and punctuation in Chinese prose.
- In-text literature numbers use superscript. Reference-list numbers use `[1]`, `[2]`, `[3]`, and so on.
- Start page numbering at `1 项目概述`; cover and directory pages do not consume the displayed report page number.
- Insert a page break before `2 分析结果`, `3 项目总结`, `4 项目调整`, `5 软件列表`, `6 报告质检`, and `参考文献`.

## Required Structure

1. Cover: project title and project number.
2. Auto-updating directory with correct heading levels and page numbers.
3. `1 项目概述`: `1.1 项目背景`, `1.2 分析方法`, `1.3 数据来源`, `1.4 研究目标`, `1.5 拟解决的关键科学问题`, `1.6 创新性`, and `1.7 流程图`.
4. `2 分析结果`: project-specific subsections arranged in analysis order.
5. `3 项目总结`.
6. `4 项目调整`.
7. `5 软件列表`: include `5.1 本研究中使用的主要软件`, `5.2 本研究中使用的R包`, and `5.3 R包参考文献`; add equivalent Python package, online tool, or database entries when actually used.
8. `6 报告质检`: use the fixed 19-item checklist in `references/report-qc-rules.md`.
9. `参考文献`.
10. Preserve the template-provided `联系我们` closing page when it is present and valid; do not invent contact information.

## Section Content Rules

- Sections before `2 分析结果` come from the proposal and confirmed project facts. Preserve the proposal's scientific intent while normalizing it to the template structure.
- `1.2 分析方法` systematically states data sources, comparison groups, methods, R/Python packages and versions, package/tool references, and actual screening thresholds.
- `1.3 数据来源` uses body formatting without first-line indent and may use automatic numbering. Dataset identifiers are bold blue. Include disease, source, sample type/count, platform or sequencing method, purpose, and access date when available.
- `1.7 流程图` uses the actual project workflow; the figure and its caption are centered.
- `2 分析结果` uses real project outputs only. Describe the method and the key numerical result for each analysis point; combine related analysis points when that improves the scientific narrative.
- In result paragraphs, dataset identifiers are bold blue, thresholds are bold green, and the most important result statements or values are bold red. Use highlighting sparingly when a paragraph contains many results.
- After every result subsection, add a bold dark-red remark naming the result folders that contain its data and figures. The remark is 小四（12 pt）, no first-line indent, and uses 1.5 line spacing.
- `3 项目总结` explains the biological significance and mechanistic interpretation connecting the key results rather than listing analysis steps. It must exceed 2 A4 pages and cite at least 5 relevant key-gene references. A mechanism diagram is not required.
- `4 项目调整` records every departure from the proposal, including dataset/module/threshold/validation changes and failed analyses. If there was no adjustment, write `无`.
- `5 软件列表` is derived from actual scripts, manifests, package metadata, online tools, and databases. Each entry must provide name, version or access/version date, purpose, and reference where applicable.
- `参考文献` combines proposal literature with references for actual methods, packages, tools, databases, and special thresholds. Use one consistent citation style and do not add unsupported citations.

## Figures And Tables

- Word reports insert PNG images only. Every report figure must also have a readable PDF counterpart in the result folder; PDF files remain deliverables and are not inserted into Word.
- Center every image. Size it so labels remain legible and avoid using one full A4 page for a single image unless the content truly requires it.
- Place the figure caption immediately below the image or grouped panel. Do not add a separate light-blue image-name line.
- Figure captions and explanatory figure notes are 五号（10.5 pt）, black, centered, 宋体/Times New Roman, and use 1.5 line spacing.
- Caption numbering and panel labels must match the result text, directory, and source files.
- Software and QC tables are three-line tables. Use 五号（10.5 pt）black text, 宋体/Times New Roman, with centered cell content.
