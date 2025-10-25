# Web-page-player
# 本地网页视频播放器（纯 HTML 实现）
![Web-page-player](https://socialify.git.ci/xyz66882/Web-page-player/image?font=Raleway&forks=1&issues=1&name=1&owner=1&pattern=Plus&pulls=1&stargazers=1&theme=Auto)
<p align="center">
  <!-- 创建日期 --><img alt="GitHub Created At" src="https://img.shields.io/github/created-at/xyz66882/Web-page-player?logo=github&label=%E5%88%9B%E5%BB%BA%E6%97%A5%E6%9C%9F">
  <!-- 下载量 --><a href="https://github.com/xyz66882/Web-page-player/releases"><img src="https://img.shields.io/github/downloads/xyz66882/Web-page-player/total?logo=github&label=%E4%B8%8B%E8%BD%BD%E9%87%8F"></a>
  <!-- 贡献者 --><a href="https://github.com/xyz66882/Web-page-player/graphs/contributors"><img src="https://img.shields.io/github/contributors-anon/xyz66882/Web-page-player?logo=github&label=%E8%B4%A1%E7%8C%AE%E8%80%85"></a>
  <!-- 最新版本 --><a href="https://github.com/xyz66882/Web-page-player/releases/"><img src="https://img.shields.io/github/release/xyz66882/Web-page-player?logo=github&label=%E6%9C%80%E6%96%B0%E7%89%88%E6%AC%A1"></a>
  <!-- 问题数 --><a href="https://github.com/xyz66882/Web-page-player/issues"><img src="https://img.shields.io/github/issues-raw/xyz66882/Web-page-player?logo=github&label=%E9%97%AE%E9%A2%98"></a>
  <!-- 讨论数 --><a href="https://github.com/xyz66882/Web-page-player/discussions"><img src="https://img.shields.io/github/discussions/xyz66882/Web-page-player?logo=github&label=%E8%AE%A8%E8%AE%BA"></a>
  <!-- 仓库大小 --><a href="https://github.com/xyz66882/Web-page-player"><img src="https://img.shields.io/github/repo-size/xyz66882/Web-page-player?logo=github&label=%E4%BB%93%E5%BA%93%E5%A4%A7%E5%B0%8F"></a>
</p>

## 说明文档

本项目是一个**基于纯 HTML 的本地网页视频播放器**，适用于在本地或服务器上播放在线视频。以下为使用过程中需要注意的事项和技术限制说明。

---

## 🌐 协议相关注意事项

### HTTPS 与 HTTP 视频播放限制

- **HTTPS 部署环境**
  - 只能播放以 `https://` 开头的视频链接。
  - 无法播放以 `http://` 开头的视频资源。
  - 这是由于现代浏览器的安全策略（混合内容限制）所导致，并非程序 Bug。
  - 特例：某些浏览器（如 **X 浏览器**）支持忽略证书限制，可播放 http 视频。

- **HTTP 部署环境**
  - 支持播放 `http://` 和 `https://` 开头的视频资源。
  - 更适合用于测试或局域网内部使用。

> ⚠️ 注意：这不是代码问题，而是互联网所有在线视频播放器都会遇到的标准限制。

---

## 📱 移动端浏览器兼容性说明

### 抖音直播流播放问题

- 某些手机浏览器可能无法播放抖音直播流。
- 原因分析：
  - 并非代码 Bug。
  - 是部分浏览器对直播协议（如 HLS、FLV）或 CDN 路径不支持。
  - 已验证：
    - vivo 自带浏览器可以正常播放抖音直播直链。
    - PC 端 Edge 和 360 浏览器支持播放。

---

## 🧩 解决方案建议

| 使用场景 | 推荐部署方式 | 说明 |
|----------|---------------|------|
| 本地播放 |`本地 `| 无跨域限制，适合调试 |
| 局域网内分享 | `http` 部署 | 可播放所有协议开头的视频 |
| 公网访问 | `https` 部署 | 需统一使用 `https` 视频源 |

---
## 🎥 mkv视频提取字幕教程

如需从 MKV 视频文件中提取字幕，可以参考此视频教程：[Bilibili - MKV视频提取字幕教程](https://www.bilibili.com/video/BV16KbLzvEmP/)

---
## 📓 思源笔记使用教程
参考https://github.com/xyz66882/Web-page-player/issues/10
---

## ❓常见问题解答

### Q：为什么视频无法加载？
A：请检查视频链接是否符合当前部署环境的协议要求（HTTP/HTTPS）。

### Q：如何让 HTTPS 页面播放 HTTP 视频？
A：除非使用代理服务器转为 HTTPS，否则现代浏览器不允许此类操作。

### Q：移动端无法播放直播怎么办？
A：尝试更换浏览器，优先使用系统默认浏览器或 Chrome。

---

## 📝 总结

- 本播放器为纯 HTML 实现，简单易用。
- 请根据部署环境选择合适的视频协议。
- 手机浏览器兼容性需注意直播协议和浏览器支持情况。

# 🚀 贡献者

<a href="https://github.com/xyz66882/Web-page-player/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=xyz66882/Web-page-player" />
</a>
<br /><br />


# ⭐️ 收藏 历史

<a href="https://www.star-history.com/#xyz66882/Web-page-player&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=xyz66882/Web-page-player&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=xyz66882/Web-page-player&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=xyz66882/Web-page-player&type=Date" />
 </picture>
</a>

--- 




效果图




![电脑](https://github.com/user-attachments/assets/d4611747-876e-4640-b9ff-ae9317390a7d)
![手机](https://github.com/user-attachments/assets/2b81bb5e-10bf-400e-9e2c-17e43ec07a47)

