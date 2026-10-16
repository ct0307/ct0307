# 你好，我是陈涛

杭州师范大学 · 计算机科学与技术本科（2024–2028）  
**求职方向：AI Agent 应用开发实习**

我关注如何把文件解析、工具调用和业务流程连接起来，做成能实际使用的应用。独立开发过从前端交互、后端接口到数据库与部署的完整项目。

## 代表项目

### [轻量化任务管理系统](https://github.com/ct0307/task-management-system)

面向个人学习与日常规划，把任务拆解、周期日程、课表导入和文件解析整合到一个系统。

**个人职责：**独立负责需求拆解、数据模型、前后端实现、Python 解析与 MCP 接入、部署及回归验证。

| 业务问题 | 我的实现 |
| --- | --- |
| 不同来源的课表字段不一致，手动录入繁琐 | 提供导入预览与字段映射，规范星期和时间；按星期与课程名合并记录，反馈成功、失败、合并和跳过数量 |
| 文件解析能力需要被业务系统和 AI 工具复用 | 使用 Python 解析 PDF、图片和 DOCX；封装 `parse_file`、`parse_pdf`、`ocr_image`、`parse_docx` 四个 MCP 工具，并提供 Express 调用入口 |
| 一个目标需要拆成多个可执行步骤 | 支持父子任务、批量创建子任务、排序，以及任务与子任务之间的转换 |

[查看源码与项目说明](https://github.com/ct0307/task-management-system#readme) · [查看解析与协议测试](https://github.com/ct0307/task-management-system/tree/main/tests)

## 技术与工作方式

- **应用开发：**React、JavaScript、Ant Design、Express、MySQL。
- **工具接入：**Python 文件解析、OCR、MCP；关注参数校验、错误返回与依赖边界。
- **交付验证：**Git、Docker Compose、Linux 部署；通过测试与页面验收检查业务链路。
- **AI 辅助开发：**使用 Codex、Claude Code、WorkBuddy 辅助编码，自己负责需求判断、代码审查、问题定位和结果验收。

希望在实习中继续打磨 AI 工具与真实业务结合的能力，也愿意从具体功能、测试和文档工作做起。
