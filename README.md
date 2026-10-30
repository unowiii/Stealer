# 偷心行动 · 完整版

网页互动剧，静态站点，由 GitHub Pages 托管。

## 在线观看

- **原版（铺满全屏）**：https://unowiii.github.io/Stealer/
- **观影框（等比缩放，手机推荐）**：https://unowiii.github.io/Stealer/index-viewer.html

## 文件结构

| 路径 | 说明 |
| --- | --- |
| `index.html` | 正片主体（546 KB，纯代码） |
| `assets/` | 35 张角色与背景图（2.7 MB） |
| `index-viewer.html` | 观影外框，把正片等比缩放铺进屏幕 |
| `.github/workflows/deploy.yml` | 推送即自动发布 |

图片已从 HTML 中拆分为独立文件，主文件保持可读、可直接查看源码。

## 怎么更新

改了 `index.html` 或替换了 `assets/` 里的图片后，提交到 `main` 分支，GitHub Actions 会自动重新发布，约 1 分钟生效。
