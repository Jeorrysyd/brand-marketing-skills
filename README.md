# Brand Marketing Skills · 乐高积木 catalog

> **品牌营销 AI Agent 的 skill 乐高积木**——34+ 个组合式 skill 按 5 桶分类（扒信息 / 想策略 / 写内容 / 做视觉 / 跑自动化），4 套示范工作流（复刻爆款 / 自动产出内容 / 找客户 / 做视觉）。

**Live**: https://jeorrysyd.github.io/brand-marketing-skills/

## 内容

单页 HTML（`index.html`）：

- **34 个 skill**，按 5 桶分类，每个标注：触发场景、装哪、示例 prompts
- **4 套 workflow**：复刻爆款 / 自动产出内容 / 找客户 / 做视觉
- **跨 AI Agent 装法**：每个 skill 给 Claude Code / Codex CLI / 国内 Agent 三套安装命令

## 收录的 skill 来源

- [coreyhaines31/marketingskills](https://github.com/coreyhaines31/marketingskills) — 14 个英文营销 skill
- [jinggreen15/ai-design-team](https://github.com/jinggreen15/ai-design-team) — 10 个内容制作角色
- [op7418/Humanizer-zh](https://github.com/op7418/Humanizer-zh) — 中文去 AI 味
- [Jeorrysyd/brand-deck](https://github.com/Jeorrysyd/brand-deck) — PPT 生成器
- [Jeorrysyd/xhs-viral-decoder](https://github.com/Jeorrysyd/xhs-viral-decoder) — 6 个小红书爆款拆解 sub-skill
- [xpzouying/xiaohongshu-mcp](https://github.com/xpzouying/xiaohongshu-mcp) — 小红书 MCP server
- 飞书 CLI · Anthropic 内置 skill

## 怎么改

直接编辑 `index.html`：
- `SKILLS` 数组（line ~2136）— 加 / 改 skill entry
- `INSTALL_TARGETS` 对象（line ~2306）— 加新仓库的安装命令
- `WORKFLOWS` 对象（line ~2367）— 加 / 改示范工作流
- `SOURCE_META` 对象（line ~2296）— skill 来源标签

push 后 GitHub Pages 自动重新 deploy。

## License

MIT
