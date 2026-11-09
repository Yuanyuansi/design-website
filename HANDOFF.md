# 司媛媛个人网站接续说明

本包包含当前网页源码、头像、61 张作品图片、原始简历 PDF，以及原网站身份配置。

## 在另一台电脑继续
1. 解压本包，打开 si-yuanyuan 文件夹。
2. 在 Codex 中登录原来的账号与工作区，将解压后的文件夹添加为本地项目。
3. 在新聊天中发送：“请先阅读 HANDOFF.md，继续维护这个已有的个人网站。沿用 .openai/hosting.json 中的 project_id，不要创建另一个网站。”
4. 本地预览需在 dist 目录启动静态 HTTP 服务。不要沿用另一台电脑的 localhost 预览地址。
5. 若要发布更新，使用 Sites 技能为原 project_id 获取新源码凭据，同步原网站并发布。登录凭据不包含在此包内。

## 网站信息
线上：https://si-yuanyuan-design.majesticpeach.chatgpt.site
现有 project_id：appgprj_6aed2e5341ac8191a052802f73dee645
网站保持原有仅所有者可见权限，不要自动更改访问权限。
静态目录：dist，无需安装依赖或构建。
页面：index.html（首页）、resume.html（简历）、portfolio.html（作品集）。

## 已完成的设计与内容
- 白灰简约风格，生成的长发眼镜女生形象。
- 首页两按钮“探索我的作品”“我的简历”，4px 圆角，简历按钮白底。
- 简历页内容来自用户提供 PDF。正文 14px，日期及辅助说明约 12px，颜色已加深；可下载原 PDF。
- 独立作品集，桌面左侧悬浮项目锚点，右侧图片；手机顶部横向目录。支持滚动高亮、点击放大、原始尺寸查看。
- 共 61 张图片。已移除原 53.png“导航与信息架构”页面。
- 原 04.png 人物模型图片已移至欣岳年第二张；欣岳年前三张顺序为 03.webp、04.webp、05.webp。
- 首页第一张大卡片：凤凰书苑第一页 10.webp；第二张：欣岳年第三页 05.webp；第三张：信息技术平台 33.webp。卡片标题及跳转匹配各自项目。
- 能力区三个图标已改为统一的灰色面性 SVG 图标。

## 文件说明
- dist/style.css 与 dist/app.js：主页样式与交互。
- dist/resume.css：简历样式。
- dist/portfolio.css 与 dist/portfolio.js：作品集样式、锚点高亮、放大交互。
- dist/assets/portfolio：网页优化后的作品 WebP，原文件夹未改动。
- .openai/hosting.json：原站身份与静态目录，需保留。

此包用于迁移文件和接续背景，不会导入完整聊天记录，也不建立两台电脑的自动文件同步。
