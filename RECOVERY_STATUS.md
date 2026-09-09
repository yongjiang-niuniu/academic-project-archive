# 最终项目恢复进度和缺失材料

截至 2026 年 9 月 9 日，Blackboard 已登录，并已识别 2025–2026 学年全部可访问的 11 门课程。课程列表已完整列出；逐项已提交作业及最终项目核对尚未完成。统一课程覆盖清单见 [COURSE_COVERAGE.md](COURSE_COVERAGE.md)：2 门正式报告已核实，9 门待逐项检查。

## Blackboard 核对进度

入口：[Blackboard](https://vle.shef.ac.uk/ultra/course)

当前浏览器只能返回窗口标题，无法读取页面内容或截图；已请求恢复浏览器访问并完成可能出现的系统登录确认。其余课程附件和学校 GitLab 最终源码的核对暂时受此影响。

当前已恢复 **2 份正式提交的报告附件**：COM6523 软件重构团队最终报告，以及 COM6103 eWaste 团队最终报告。课程出现在列表中不代表它存在已完成的项目提交；以下状态按已取得的证据记录。

| 课程 | 课程名称 | 最终提交核对状态 |
| --- | --- | --- |
| COM6906 | COM PGT Dissertation Project | 待核对正式提交；已有 HPC 研究仓库不自动视为最终提交版本。 |
| COM6009 | Modelling and Simulation of Natural Systems | 待核对最终项目和提交附件。 |
| COM6103 | Team Software Project | 正式报告已保存；现有代码为 3 月后端，最终完整 GitLab 源码仍待恢复。 |
| COM6521 | Parallel Computing with Graphical Processing Units (GPUs) | 待核对最终项目和提交附件。 |
| COM6523 | Software Reengineering | 已下载已提交的 Attempt 1 最终报告，校验值与现有课堂最终 PDF 一致。 |
| COM6115 | Text Processing | 待核对最终项目和提交附件。 |
| COM6503 | 3D Computer Graphics | 待核对最终项目和提交附件。 |
| COM6516 | Object Oriented Programming and Software Design | 待核对正式提交，并与已有语言模型项目匹配。 |
| COM6655 | Professional Issues | 待核对最终提交及其项目性质。 |
| SSDC012 | Skills Audit for Maths and Stats 11 | 待确认是否存在适合归档的最终项目。 |
| FCEC005 | Understanding Harassment & Sexual Misconduct - Faculty of Engineering | 待确认课程内容性质，不将培训或测验默认归为软件项目。 |

### COM6523 正式最终报告

- 提交项：[Group Project Final Submission (Group Feedback)](https://vle.shef.ac.uk/ultra/courses/_123483_1/assessment/_9085796_1/overview)。
- 已提交的 Attempt 1，组别 PGT05；页面显示提交时间为 `20/05/2026, 10:01 (UTC+8)`。
- 文件：`PG_05_COM6523_Software_Reengineering_Group_Project_Report.pdf`，396,344 字节。
- SHA-256：`de0b49b299663d7dc180f24d015b760ee9c024c6326ee124c6d1e3584e7a659c`。
- 该 PDF 与已有私有 yarl 项目 `Report/` 中的最终 PDF 一致。额外找到的本地 PDF 副本文件哈希不同，但记录中的文字和页面对比与标准报告一致，继续独立保留。
- Blackboard 要求 PDF 报告，代码及活动记录位于 GitHub Classroom，分析材料位于 `Submission/`。未提交的 Attempt 2 是草稿，未打开或更改。

### COM6103 正式团队报告

- 提交项：[Team Project](https://vle.shef.ac.uk/ultra/courses/_123515_1/assessment/_9028411_1/overview)。
- 已提交的 Attempt 1，组别 1 eWaste；页面显示提交时间为 `07/05/2026, 01:13 (UTC+8)`。
- 文件：`1 eWaste.pdf`，6,588,326 字节。
- SHA-256：`1cded5fef40262c3e30cb883781ca83a682f3e64c261ccac4e75fd23e37cdc37`。
- 正式报告及提交来源记录已保存于私有 `team` 项目。提交项要求上传 PDF；源码未作为附件提供。现有代码为 2026 年 3 月后端快照，最终完整团队源码仍待从 GitLab 恢复。

## 其他已知缺失

- EVRP：原始报告已保存；源码、原始实验日志、基准文件和可编辑论文源文件尚未恢复。
- eWaste：私有 `team` 仓库保存正式 Blackboard 报告及 2026 年 3 月后端快照。该快照并非报告所述最终完整系统；最终前端、扩展后端及相应测试等源码仍待从 GitLab 恢复。
- HPC：现有公开仓库保存已提交的模拟项目快照。正在其他任务中编辑的本地论文、实验和数据目录保持原状。
- 自然系统建模：本地约 4.17 GiB 的教学、解答和复习材料保留在本地；个人最终项目是否存在，以后续正式提交核对为准。
- SPR318 作文/封面尚未确认课程及身份关系；学位论文模板也不能作为已完成论文展示。

## 每周练习移除

9 个 COM6523 每周练习已移出活动项目目录。远端删除尚未完成：CLI 首次删除因缺少 `delete_repo` 权限被 GitHub 拒绝，未继续尝试其他目标。已核验的本地备份和课堂来源继续保留。完整状态见 [history/README.md](history/README.md)。

恢复过程中保留不同版本和来源证据。尚未找到的源码、附件或实验记录继续标为待恢复，不以新生成内容替代原始课程成果。
