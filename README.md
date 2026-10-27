# Frontend Prompt

安静的前端提示词样板间：逐项积累设计规则，以可交互 HTML 验证实际效果。

- 线上：https://frontend-prompt.anjing.cc/
- `prompt.txt`：完整组合提示词，包含局部规则范围与本次试稿选择。
- `index.html`：HTML、CSS、JavaScript 样板间；左侧说明与右侧组件通过引线关联，可隐藏讲解层。
- 展示内容：蜡笔纸张、hover 链接卡片、带本节阅读进度的文章目录、透明输入框与按需显示的工具栏。

发送、停止、错误、模型切换为本地交互演示。附件仅展示本地文件名，不上传。

## 本地

运行 `npm run dev`，访问终端给出的地址。运行 `npm run build` 检查内联脚本语法并生成 `dist/`。

## 发布

Cloudflare Pages 直接连接 `anjing-le/frontend-prompt`，生产分支 `main`，构建命令 `npm run build`，输出目录 `dist`，Node.js 由 `.node-version` 固定。

推送 `main` 后自动构建部署。自定义域名 `frontend-prompt.anjing.cc`。`/version.json` 记录构建对应提交，用于核对线上是否已更新；push 成功不代表部署成功。

## 维护

修改设计规则时同步更新提示词与样板间。保留局部组件规则与全局风格的优先关系；未确认的选择明确标记。检查桌面、窄屏、键盘、hover、目录定位及输入框状态，避免仅凭构建判断体验。
