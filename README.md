## Hi there 👋
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Dylan632/Dylan632/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Dylan632/Dylan632/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Dylan632/Dylan632/output/github-contribution-grid-snake.svg">
</picture>

## GitHub 主页贪吃蛇配置知识

### 最小闭环
- 仓库建议保持 **Public**（`用户名/用户名` 个人主页仓库）。
- `.github/workflows/snake.yml` 通过 `Platane/snk@v3` 生成 `dist/*.svg`。
- 同一工作流把 `dist` 推送到 `output` 分支。
- README 使用 `<picture>` 引用 `output` 分支中的 light/dark 两个 SVG。

### 排障要点
- 若主页不显示蛇图，先检查图片链接是否返回 200。
- 若返回 404，常见原因是仓库为 **Private**，`raw.githubusercontent.com` 无法公开访问该资源。
- 保持私有仓库时，可将蛇图发布到公开仓库或公开 Pages 地址，再在 README 引用公开 URL。



<!--
**Dylan632/Dylan632** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
