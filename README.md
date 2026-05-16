# 🧠 Academic AI External Brain (学术 AI 外脑前端)

这是一个纯净、学术克制风的个人知识库收录前端页面。通过无缝对接自动化工作流引擎（如 n8n/Airtable），实现一键抓取并利用大语言模型（LLM）对前沿学术论文、网页文章进行深度摘要与结构化标签归档。

## ✨ 特性
- **学术克制视觉**：采用现代明暗极简风，专注内容，拒绝信息过载。
- **动态历史追溯**：底层打通 Webhook，实时渲染最近收录的文献流。
- **高容错解析**：原生支持打平各种复杂嵌套的 JSON 数据结构。
- **零依赖运行**：纯原生 JavaScript + Tailwind CSS CDN，支持单文件双击直接本地部署运行。

## 🛠️ 快速开始
1. 克隆本项目到本地。
2. 打开 `index.html`，配置你自己的 `submitWebhookUrl` 和 `historyWebhookUrl`。
3. 双击 `index.html` 即可在本地浏览器完美运行，或将其一键拖拽至 Netlify 等平台发布。
