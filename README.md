# 追寻梵高之旅 · 2026 亲子人文之旅

> **In the Footsteps of Van Gogh** — 10 days · 9 nights · Netherlands × France
> 2026.07.19 — 07.28

法律先生（Mr. Law）出品的暑期亲子人文之旅招生落地页。

## 内容

- `index.html` — 移动优先的杂志风格落地页
- `brochure.pdf` — 完整招生简章（15 页 A4 PDF）
- `.nojekyll` — 关闭 GitHub Pages 的 Jekyll 处理，让文件名以下划线开头的资源也能正常加载

## 在本地预览

```bash
# 最简单：直接双击 index.html 在浏览器打开
# 或用 Python 起一个本地服务器：
python3 -m http.server 8000
# 然后访问 http://localhost:8000
```

## 部署到 GitHub Pages

```bash
# 1. 在 GitHub 上新建一个 public 仓库，比如 vangogh-journey-2026
# 2. 在本地把本文件夹推上去：
git init
git add .
git commit -m "Launch landing page"
git branch -M main
git remote add origin https://github.com/<你的用户名>/vangogh-journey-2026.git
git push -u origin main

# 3. 在仓库页 Settings → Pages → Source 选 "Deploy from a branch"，
#    Branch 选 main / root，保存。
# 4. 稍等 1–2 分钟，访问：
#    https://<你的用户名>.github.io/vangogh-journey-2026/
```

## 需要你替换的内容

| 位置 | 当前 | 需要换成 |
|---|---|---|
| CTA 区 QR 占位 | 虚线方框 | 真实微信 QR 图片（替换 `index.html` 里 `.qr` 的那一块，或直接改成 `<img src="wechat-qr.png">`） |
| 微信号 | `flxs77` | 如有变动请统一修改 |

## 联系

- 微信：`flxs77`
- 项目方：法律先生 · Mr. Law
