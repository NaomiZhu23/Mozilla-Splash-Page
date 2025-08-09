# Mozilla-Splash-Page（Demo）

本仓库是我根据 [MDN 教程](https://developer.mozilla.org/zh-CN/docs/Learn_web_development/Core/Structuring_content/Mozilla_splash_page) 亲手复现的「Mozilla 欢迎页面」示例代码。仅用于个人练习与分享，**不保证完全正确**，但功能完整、可直接运行。

> **版本差异说明**  
> 提交本仓库时，英文版 MDN 已不再强制要求使用 `120 px` 与 `600 px` 宽度的图片；中文版仍保留该要求。因此仓库内同时提供了两组尺寸文件（120 px / 400 px 及 600 px / 1200 px），可按需选用或自行删除。

## 📁 目录结构

```
mozilla-splash-page/
├─ index.html               # 主页面
├─ pattern.png              # 背景纹理
├─ firefox_logo-120.png     # Firefox 徽标（120 px）
├─ firefox_logo-400.png     # Firefox 徽标（400 px）
├─ mozilla_dinosaur_head-120.png
├─ mozilla_dinosaur_head-400.png
├─ firefox_addons-120.jpg
├─ firefox_addons-400.jpg
├─ mdn.svg                  # MDN 徽标（SVG）
├─ red-panda-600.jpg        # 红熊猫竖版（600px）
├─ red_panda-1200.jpg       # 红熊猫横版（1200px）
└─ README.md                # 你正在阅读的这份说明文档
```

## 🚀 本地预览（推荐方式）

使用 **VS Code + Live Server 插件** 一键开启热重载：

1. **安装插件**  
   在 VS Code 扩展商店搜索并安装 **Live Server**（作者：Ritwick Dey）。

2. **打开项目**  
   在 VS Code 中把项目根目录添加为工作区。

3. **一键启动**  
   - 右键 `index.html` → **“Open with Live Server”**  
   - 浏览器自动弹出 `http://localhost:5500`（默认端口）。

4. **实时刷新**  
   每次保存文件，页面自动热重载，无需手动刷新。


## ⚠️ 注意事项

- **不要直接浏览 `index.html`** ：直接用浏览器打开 `index.html` 文件会导致跨域限制：Bilibili 视频无法加载。
- **端口占用** ：Live Server 默认使用 `5500` 端口；如被占用，插件会自动切换到 `5501`、`5502`… 

## 🖼️ 素材声明

- **版权归属**：所有 `firefox_*`、`mozilla_*`、`red-panda-*` 等素材均来自 **MDN 官方仓库**，**仅供学习参考使用**。  

---

Happy hacking! 🎉  
