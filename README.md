# 接线话术看板

面向图拉斯客服接线场景的单文件 HTML 工具。通过关键词或输入法缩写查找话术，查看全文并复制到接待窗口。

## 在线使用

- [GitHub Pages](https://yujunyi1018-rgb.github.io/torras-quick-replies/)
- [Vercel](https://torras-quick-replies.vercel.app)
- [下载 ZIP 安装包](https://github.com/yujunyi1018-rgb/torras-quick-replies/releases/download/v1.0.0/torras-quick-replies-v1.0.0.zip)

## 功能

- 搜索关键词或快捷键，按接线场景筛选。
- 复制话术正文，复制前可临时修改金额、型号和地址。
- 收藏常用话术，查看最近成功复制的话术；这些记录保存在当前浏览器。
- 保留相同快捷键对应的不同话术，分别显示。
- 原文划掉的内容默认不出现在全部话术中，可进入「已划掉内容」查看。
- 自动复制受浏览器限制时，提供手动复制窗口。

快捷操作：`Ctrl K` 定位搜索框，`↑` / `↓` 切换搜索结果，`Ctrl Enter` 复制当前话术，`Esc` 清空搜索。

## 本地使用

下载 ZIP 并解压，用 Chrome 或 Edge 打开 `index.html` 即可。不需要安装依赖，也不需要构建；本地版本可以离线使用。

## 内容与版本

话术来自飞书《话术》文档，读取日期为 2026-10-05，源文档版本为 2。本版本包含 192 条记录，其中 182 条保留未删除内容，10 条已全部划掉；删改后仅剩称呼的两条记录不提供正文复制。

快捷键采用原文的「缩写,候选序号」格式。输入法需配置对应自定义短语才能使用缩写；看板可独立复制话术正文。

## 部署

GitHub Pages 使用 `main` 分支根目录的 `index.html`。Vercel 使用仓库根目录，框架选择 `Other`，项目中的 `vercel.json` 已配置静态部署。

仓库包含完整 HTML、静态部署配置和使用说明。
