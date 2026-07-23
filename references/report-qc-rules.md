# Report QC Rules

Use the fixed 19-item checklist from `templates/报告模板新2026.6.29.docx`. Do not mark an item `无问题` until it has actually been checked; record the problem and corrective action when it fails.

| 序号 | 检查点 | 检查内容 |
| --- | --- | --- |
| 1 | 标题是否正确 | 疾病、研究方向和项目标题正确，无错别字。 |
| 2 | 目录 | 目录序号、层级和页码正确，并与实际分析内容匹配。 |
| 3 | 流程图 | 流程图与实际分析内容和执行顺序匹配。 |
| 4 | 数据信息 | 疾病、数据来源、样本信息、平台或测序方法、分组和用途完整准确。 |
| 5 | 疾病是否有错 | 全文疾病名称、缩写和研究对象一致。 |
| 6 | 全文数字是否正确 | 数据集、样本量、基因数、阈值、统计量、图表数字和结论相互一致。 |
| 7 | 图片是否正确 | 图与对应分析点、数据、组别和正文引用一致。 |
| 8 | 图片是否清晰完整 | 标签和图例可读，无裁切、拉伸、缺图或错误拼图。 |
| 9 | 分析是否符合规范 | 阈值、基因数、统计方法和模块要求符合项目与部门规范；例外已说明。 |
| 10 | 图注是否匹配 | 图号、面板、组别、颜色、坐标和统计说明与图片一致。 |
| 11 | 每个分析点是否有结果描述 | 写明使用什么方法、输入什么数据以及得到什么关键结果。 |
| 12 | 结果是否有对应文件夹路径 | 每个结果小节末尾有备注，且所列目录真实存在并包含对应数据和图。 |
| 13 | 总结不罗列分析点 | 总结围绕关键发现、生物学意义和机制解释展开，超过 2 页 A4，并引用至少 5 篇关键基因文献；不要求绘制机理图。 |
| 14 | 方案调整说明 | 所有调整均已列出；无调整时明确写 `无`。 |
| 15 | 软件列表是否合格 | 软件、包、工具和数据库与实际分析匹配，并有版本、用途和参考文献。 |
| 16 | 参考文献 | 引文完整、编号连续、正文引用可追溯且格式一致。 |
| 17 | 全文格式是否统一 | 字体、字号、颜色、1.5 倍行距、标题层级、首行缩进、分页和页码符合模板。 |
| 18 | 结果文件是否完整正确 | 每个分析点文件完整、正确、可打开；每张报告图同时有 PNG 和 PDF，Word 仅插入 PNG。 |
| 19 | 代码 | 分析代码完整、参数和路径清晰，可从项目输入复现交付结果。 |

## Additional Preflight

- Required cover, directory, sections, page breaks, page numbering, three-line tables, and closing page are present.
- Proposal-required modules appear in `2 分析结果` or are explicitly explained in `4 项目调整`.
- Dataset identifiers are bold blue, actual thresholds bold green, and selected key results bold red; highlighting is not applied to unsupported statements.
- Images and black five-size captions are centered; there is no legacy standalone light-blue image-name line.
- All referenced figure, table, code, and result paths exist.
- Proposal/template example images and text（示例图、示例内容）are not treated as real results.
- No genes, datasets, sample sizes, thresholds, results, or conclusions are invented（不得虚构）.
- Project ID, disease, species, data source, grouping, sample counts, and key genes match confirmed project facts or are explained in project adjustments.
- The final DOCX contains no placeholders, stale directory fields, unresolved tracked changes, comments, or broken references.
