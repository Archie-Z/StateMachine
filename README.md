# StateMachine 📝

![StateMachine](public/assets/favicon.svg)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Astro](https://img.shields.io/badge/Astro-FF5D01?style=for-the-badge&logo=astro&logoColor=white)

StateMachine是一个基于[AstroPaper](https://github.com/satnaing/astro-paper)构建的个人博客网站。保留了AstroPaper的极简、响应式和SEO友好的特性，同时根据个人需求进行了定制化。

## 🔥 特点

- [x] 类型安全的Markdown
- [x] 超快的性能表现
- [x] 无障碍设计（键盘/屏幕阅读器）
- [x] 响应式布局（移动设备～桌面）
- [x] SEO优化
- [x] 明暗模式切换
- [x] 模糊搜索功能
- [x] 草稿文章与分页
- [x] 站点地图和RSS订阅
- [x] 遵循最佳实践
- [x] 高度可定制
- [x] 博客文章动态OG图像生成

## 🚀 项目结构

StateMachine的文件夹和文件结构如下：

```bash
/
├── public/
│   └── assets/
├── src/
│   ├── assets/
│   │   ├── icons/
│   │   └── images/
│   ├── components/
│   ├── data/
│   │   └── blog/
│   ├── layouts/
│   ├── pages/
│   │   ├── archives/
│   │   ├── posts/
│   │   └── tags/
│   ├── styles/
│   └── utils/
│       ├── og-templates/
│       └── transformers/
└── astro.config.ts
```

Astro会查找`src/pages/`目录中的`.astro`或`.md`文件。每个页面都会根据其文件名暴露为一个路由。

静态资源（如图片）存储在`public/`目录中，而组件特定的资源则位于`src/assets/`中。

所有博客文章都存储在`src/data/blog`目录中。

## 💻 技术栈

**主框架** - [Astro](https://astro.build/)  
**类型检查** - [TypeScript](https://www.typescriptlang.org/)  
**样式** - [TailwindCSS](https://tailwindcss.com/)  
**静态搜索** - [FuseJS](https://fusejs.io/)  
**图标** - [Tablers](https://tabler-icons.io/)  
**代码格式化** - [Prettier](https://prettier.io/)  
**部署** - [Vercel](https://vercel.com/)  
**代码检查** - [ESLint](https://eslint.org)

## 👨🏻‍💻 本地运行

你可以通过克隆仓库并运行以下命令在本地启动这个项目：

```bash
# 克隆仓库
git clone https://github.com/yourusername/StateMachine.git
cd StateMachine

# 安装依赖
npm install

# 启动开发服务器
npm run dev
```

网站将在`http://localhost:4321`上可用。

## 🧞 命令

所有命令都在项目根目录的终端中运行：

| 命令                  | 操作                                                                                                      |
| :-------------------- | :-------------------------------------------------------------------------------------------------------- |
| `npm install`         | 安装依赖                                                                                                 |
| `npm run dev`         | 在`localhost:4321`启动本地开发服务器                                                                      |
| `npm run build`       | 将生产站点构建到`./dist/`                                                                                |
| `npm run preview`     | 在部署前本地预览构建                                                                                     |
| `npm run format:check`| 使用Prettier检查代码格式                                                                                 |
| `npm run format`      | 使用Prettier格式化代码                                                                                   |
| `npm run sync`        | 为所有Astro模块生成TypeScript类型                                                                        |
| `npm run lint`        | 使用ESLint进行代码检查                                                                                   |

## 📖 文档

如果你想了解更多关于如何使用和定制这个博客主题的信息，可以参考原始AstroPaper的文档：

- 配置 - [博客文章](https://astro-paper.pages.dev/posts/how-to-configure-astropaper-theme/)
- 添加文章 - [博客文章](https://astro-paper.pages.dev/posts/adding-new-posts-in-astropaper-theme/)
- 自定义颜色方案 - [博客文章](https://astro-paper.pages.dev/posts/customizing-astropaper-theme-color-schemes/)
- 预定义颜色方案 - [博客文章](https://astro-paper.pages.dev/posts/predefined-color-schemes/)

## 🤝 贡献

欢迎贡献！请随时提交Pull Request。

1. Fork仓库
2. 创建你的功能分支（`git checkout -b feature/amazing-feature`）
3. 提交你的更改（`git commit -m 'Add some amazing feature'`）
4. 推送到分支（`git push origin feature/amazing-feature`）
5. 打开Pull Request

## 📜 许可证

本项目基于MIT许可证 - 详情请参阅LICENSE文件。

---

使用 [Astro](https://astro.build) 和 ❤️ 构建