# Average-cost

## 简介 (Chinese)
- 单页静态应用：直接打开 `index.html` 即可使用，无需额外构建或服务器。
- 功能：输入用逗号/空格分隔的数字，计算平均值并展示绝对值结果。
- 技术：使用 Tailwind CSS 与 Font Awesome CDN，逻辑集中在页面内联脚本。
- 国际化：支持中英文文本，页面右上角可通过语言切换按钮快速切换。

## Introduction (English)
- Single-page static app: open `index.html` directly—no build step or server required.
- Feature: enter comma/space-separated numbers to get the average and its absolute value.
- Tech stack: Tailwind CSS & Font Awesome via CDN, with all logic in inline scripts.
- Internationalization: Chinese and English text available; use the toggle button in the top-right corner of the page.

## 快速开始 / Quick Start
1. 打开 `index.html` 查看页面；如需离线访问，请将 CDN 资源替换为本地文件。
2. 输入数字序列，点击“计算平均值 / Calculate Average”。
3. 查看原始平均值与正数结果，如需重置输入可使用“清空输入 / Clear Input”。

## 目录结构 / Project Structure
- `index.html`: 页面主体、样式配置、逻辑脚本及语言切换实现。
- `CNAME`: 用于部署的自定义域名配置（如托管在 GitHub Pages）。

## 改进建议 / Improvements
- 增加输入校验与错误提示，提升用户体验。
- 拆分脚本与样式为独立文件，引入构建工具（如 Vite）以便扩展。
- 补充自动化测试，覆盖解析逻辑和计算逻辑。
