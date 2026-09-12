# Salat Now — 法务页面（GitHub Pages）

本目录对应仓库：`fei665671/salat-now-legal`  
当前模式：**App Store 付费下载**（无内购 / 无 Pro 解锁）。

## App Store Connect 填这个

```text
https://fei665671.github.io/salat-now-legal/SalatNow-Legal/privacy.html
```

条款页：

```text
https://fei665671.github.io/salat-now-legal/SalatNow-Legal/terms.html
```

首页：

```text
https://fei665671.github.io/salat-now-legal/SalatNow-Legal/
```

## 如何发布本次更新

在仓库根目录（桌面 `salat-now-legal`）提交并推送即可，例如用 GitHub Desktop，或：

```bash
cd ~/Desktop/salat-now-legal
git add SalatNow-Legal
git commit -m "Update legal pages for paid App Store build"
git push
```

推送后等 1–2 分钟，刷新上面的 `privacy.html` 确认已是「Paid app / 付费下载」版本。

## 文件说明

| 文件 | 说明 |
|------|------|
| `privacy.html` | 英文隐私政策（Connect 主链接） |
| `terms.html` | 英文使用条款 |
| `privacy-*.html` / `terms-*.html` | 英 / 中 / 阿 |
| `index.html` | 语言入口 |
| `README.md` | 本说明 |

内容与 App 内 `SalatNow/Resources/Legal/` 一致。联系邮箱：`luolin0231@gmail.com`
