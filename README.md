# 李雨润 · 投资研究备忘录（GitHub Pages）

五篇投资研究主题备忘录的在线发布版本，涵盖**具身智能、AI 算力芯片、AI 制药、AIGC 数字文化消费、二手奢侈品（循环时尚）**五个方向。可作为投资研究能力的展示作品集。

## 目录结构

```
memo-site/
├── index.html              # 导航首页
├── embodied-ai.html        # 具身智能
├── ai-compute.html         # AI 算力芯片
├── ai-pharma.html          # AI 制药
├── aigc-culture.html       # AIGC 数字文化消费
├── luxury-resale.html      # 二手奢侈品（循环时尚）
└── assets/                 # 报告图表（本地图片，无外部依赖）
```

> 网页内文件名使用英文 slug，便于 GitHub Pages 生成干净的 URL；对外展示名见导航页卡片。

## 本地预览

```bash
cd memo-site
python -m http.server 8000
# 浏览器打开 http://localhost:8000
```

## 发布到 GitHub Pages

本目录已 `git init` 并提交到 `main` 分支，你只需：

1. 在 GitHub 新建一个 **公开（Public）** 仓库，例如 `Investment_Memos`。
2. 关联并推送：

   ```bash
   git remote add origin https://github.com/<你的用户名>/Investment_Memos.git
   git push -u origin main
   ```

3. 仓库 → **Settings → Pages** → Source 选 **main** 分支、目录 **/root** → Save。
4. 等待约 1–2 分钟，访问 `https://<你的用户名>.github.io/Investment_Memos/` 即可看到导航页。

## 二维码

拿到上面的链接后，可用任意二维码工具生成 PNG（也可让 川 用脚本直接生成），贴进简历 / 打印件 / 面试展示。

## 说明

- 网页仅引用本地 `assets/`，无外部字体 / JS 依赖，离线可看。
- 内容为脱敏的投资研究框架，可公开，不代表任何机构观点或投资建议。
- 如需更新，修改对应 HTML 后 `git add . && git commit -m "update" && git push` 即可，GitHub Pages 会自动重新部署。
