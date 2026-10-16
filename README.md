# WIND POLICY WATCH | 风电政策法规与行业动态监测

完整使用说明（部署、AI Secret、页面说明、故障排查）见 **[README_GITHUB_CN.md](README_GITHUB_CN.md)**。

- 顶部双入口：**政策法规**（`site/index.html`）、**行业动态**（`site/news.html`）
- 121 个用户配置的法规来源（100 个国内、21 个海外/国际），18 个法规维度
- 16 个现有行业动态来源，保留历史资讯数据
- 每日 GitHub Actions 自动采集、去重、按证据辅助分析、生成 CSV 并发布 GitHub Pages
- `OPENAI_API_KEY` 可选；不配置时不调用付费模型，规则分析和静态网站仍可使用
- 不编造官方发布时间、法律义务或成功抓取状态

> 网站公开展示的所有内容是法规候选初筛，不替代官方原文及法律合规复核。
