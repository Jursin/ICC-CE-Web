# ICC-CE 官网储存库

使用 VitePress 搭建

## 快速开始
- 环境要求
  - Node.js 20+
  - pnpm
- 安装依赖
  ```bash
  pnpm install
  ```
- 启动开发服务器
  ```bash
  pnpm run docs:dev
  ```
  开发服务器将运行在 [http://localhost:5173](http://localhost:5173)
- 构建生产版本
  ```bash
  pnpm run docs:build
  ```
  构建结果将输出到 .vitepress/dist 目录
- 预览生产版本
  ```bash
  pnpm run docs:preview
- 内容编写指南
  - 所有文档使用 Markdown 格式编写
  - 在 docs 目录下创建新的 .md 文件即可自动生成对应页面
  - 使用 Frontmatter 配置页面元数据：
  - 在 `/docs/.vitepress/config.ts` 中配置站点

## 贡献指南
欢迎贡献文档：

- Fork 本项目
- 创建新分支
- 提交更改
- 推送到分支
- 创建 Pull Request
