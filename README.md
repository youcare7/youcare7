<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=2F81F7&center=true&vCenter=true&width=620&lines=Building+privacy-first+Chrome+extensions;Prompt+Engineering+%C2%B7+BYOK+%C2%B7+Manifest+V3;Ship+small+things,+test+them+properly" alt="Typing SVG" />

**youcare7** · 专注安全优先的浏览器扩展与 Prompt 工程：最小权限、会话级存储、纯文本渲染，把小项目按可验证的标准做扎实。

</div>

## 🔭 Focus

- **安全优先的扩展开发**：Manifest V3 配合最小权限，`activeTab` 仅在主动触发时读取选中文字，不碰整页内容与浏览历史
- **隐私边界设计**：API Key 只存 `chrome.storage.session`，关闭浏览器即清除；生产环境零持久日志
- **可验证的工程习惯**：89 项离线测试（node:test 单测 73 项 + Playwright E2E 16 项，含 axe 无障碍扫描）；真实 API 未验收就保持预发布标记，不伪装成功
- **Prompt 工程**：用结构化框架拆解新闻叙事，强调批判性思维与可验证示例，内容以 CC0 开放

## 🧩 Featured Projects

| 项目 | 说明 | 技术 |
| --- | --- | --- |
| [gemini-summary-ext](https://github.com/youcare7/gemini-summary-ext) | 划词速审 Chrome 扩展：摘要、安全审查辅助、中英翻译；BYOK 会话存储、textContent 安全渲染，89 项测试全绿 | JavaScript · MV3 · Playwright |
| [news-analysis-prompt](https://github.com/youcare7/news-analysis-prompt) | 基于「倡导-缺失」反向透视法的新闻分析 Prompt 框架，含 JSON 结构化输出与可验证示例 | Prompt Engineering · CC0 |

## 🌱 Open Source

- **[apache/doris-website#4234](https://github.com/apache/doris-website/pull/4234)**（已合并）— 修复官网首页 "Comming Soon" 拼写错误及括号前缺失空格，共 3 处英文文案

## 🛠 Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,html,css,nodejs,git&perline=12" alt="Tech stack" />
</p>

**Browser**：Chrome Extension MV3 · Service Worker · chrome.storage　**Engineering**：node:test · Playwright · BYOK

## 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/youcare7/youcare7/output/github-snake-dark.svg" />
  <img src="https://raw.githubusercontent.com/youcare7/youcare7/output/github-snake.svg" alt="Contribution snake" />
</picture>
