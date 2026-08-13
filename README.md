# 前端八股抽背工作台

手绘风格的前端面试闪卡抽背工具，覆盖 **15 个模块 / 216 道面试题**，支持手机浏览器访问（部署在 GitHub Pages）。

## 功能
- 闪卡式抽背：正面题目、点击翻转看解析，解析可滚动
- 左侧抽屉切换模块（全部 / 各专项）
- 每日计划：设定每天背多少题、倒计时天数、进度追踪
- 本地存档：进度、已掌握题目、每日目标存于浏览器 localStorage

## 模块
JS · CSS · 浏览器 · Vue · React · TypeScript · 工程化 · 数据可视化 · Three.js · 跨端 · Node · AI 应用 · 网络 · 算法 · 简历

## 本地运行
```bash
# 需要本地服务器（直接双击 index.html 会被 CORS 拦截，无法加载 data/*.json）
npx serve .        # 或 python -m http.server
```
打开页面后题目会从 `data/<模块>.json` 按需加载。

## 部署
推送到本仓库 `main` 分支后，在仓库 **Settings → Pages** 选择 `Deploy from a branch` / `main` / `/root` 即可。
