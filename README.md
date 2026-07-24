# 李雨润 · 投资研究备忘录（GitHub Pages）

四篇买方投资备忘录的在线发布版本：**具身智能 / AI 算力芯片 / AI 制药 / AIGC 数字文化消费**。
用于投递、面试展示与作品集沉淀。

## 目录结构

```
memo-site/
├── index.html                          # 导航首页
├── 投资备忘录_具身智能_v4.html
├── 投资备忘录_AI算力芯片_v4.html
├── 投资备忘录_AI制药_v4.html
├── 投资备忘录_AIGC数字文化消费_v4.html
└── assets/                             # 图表（米黄原图，网页引用）
```

## 本地预览

```bash
cd memo-site
python -m http.server 8000
# 浏览器打开 http://localhost:8000
```

## 发布到 GitHub Pages

本目录已 `git init` 并提交到 `main` 分支，你只需：

1. 在 GitHub 新建一个 **公开（Public）** 仓库，例如 `investment-memos`。
2. 关联并推送：

   ```bash
   git remote add origin https://github.com/<你的用户名>/investment-memos.git
   git push -u origin main
   ```

3. 仓库 → **Settings → Pages** → Source 选 **main** 分支、目录 **/root** → Save。
4. 等待约 1 分钟，访问 `https://<你的用户名>.github.io/investment-memos/` 即可看到导航页。

## 二维码

拿到上面的链接后，可用任意二维码工具生成 PNG（也可让 川 用脚本直接生成），贴进简历 / 打印件 / 面试展示。

## 说明

- 网页仅引用本地 `assets/`，无外部字体 / JS 依赖，离线可看。
- 内容为脱敏的买方研究框架，可公开。
- 如需更新，修改对应 HTML 后 `git add . && git commit -m "update" && git push` 即可，GitHub Pages 会自动重新部署。
