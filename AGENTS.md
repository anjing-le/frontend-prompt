# 协作约定

- 本仓库积累前端设计提示词及对应 HTML 样板间；提示词和实现同步维护，保持轻量静态站，不自动引入框架、后端或真实模型服务。
- 样板间保留可隐藏的讲解层、要素说明与引线。无字要求仅用于风格展示；文章、输入框、链接卡片适用明确的局部规则。
- 使用 HTML 实际页面交付视觉迭代，不用截图代替。
- 发布前执行 npm run build 和 git diff --check。区分 push、Cloudflare 部署成功、线上内容匹配与实际浏览器检查。
- 生产分支 main。Git 作者和提交者均为 anjing-le <245548353+anjing-le@users.noreply.github.com>，只配置仓库本地身份。SSH 使用 ~/.ssh/id_rsa_anjing，不依赖默认身份。
- 不提交凭据或本地环境文件。
