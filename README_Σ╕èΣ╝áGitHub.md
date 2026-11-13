# Arcade Racing WEB v1.0

这是浏览器版，不需要安装 Python / Pygame。

## 本地试玩
直接打开 `index.html` 即可。部分浏览器为了安全会限制本地音效；如果画面能玩但没有声音，上传 GitHub Pages 后即可正常使用。

## 上传 GitHub Pages
1. 新建一个 GitHub repository。
2. 把这个 ZIP 解压。
3. **上传解压后的全部文件和 assets 文件夹，不要把 ZIP 本身当网页上传。**
4. 确认 repository 最外层直接看到：
   - `index.html`
   - `game.js`
   - `style.css`
   - `assets/`
5. GitHub → Settings → Pages。
6. Source 选择 `Deploy from a branch`。
7. Branch 选择 `main`，Folder 选择 `/ (root)`，Save。
8. 等 GitHub Pages 给你网址后，用 iPhone / Android / Windows 浏览器打开即可。

## 主要控制
- W / ↑ / Space：油门
- S / ↓：Brake
- A / D 或 ← / →：转向
- X：Boost，最高 500 km/h
- Z / Ctrl / J：飞弹
- 飞弹按住 ≥2 秒：3颗
- 飞弹按住 ≥5 秒：5颗
- P / Esc：暂停
- Xbox/兼容手柄：RT油门、LT/B Brake、左摇杆转向、X Boost、A飞弹

## 网页版已包含
- 30款车型选择
- 各车型 idle / low / hard / high / release / quick 网页音效
- 设置自动保存在浏览器 localStorage
- Landscape / Portrait
- NPC安全车距
- NPC碰撞
- 警车追赶、警笛、5秒后扣HP
- Point / Health Gift，Health Gift 3-2-1倒数
- Health Gift 慢速下移
- Brake轮胎痕迹与白烟
- 短油门排气喷火
- 1 / 3 / 5颗飞弹
- Gamepad API 手柄支持
- 手机触控按钮
