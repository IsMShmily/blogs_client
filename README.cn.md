<div align="right">
  <a href="README.md">English</a> | <a href="README.cn.md">中文</a>
</div>

# Vue 3 + TypeScript 博客

博客项目的前端源代码使用了最新的技术 **_Vue3 + Tyepscript + Vite + TailWindocss + Threejs ..._**

<div >
  <img alt="Vue" src="https://img.shields.io/badge/-vue-%23000000?style=flat-square&logo=vuedotjs" />
  <img alt="Static Badge" src="https://img.shields.io/badge/-TypeScript-000?style=flat-square&logo=tsnode">
  <img alt="Vite" src="https://img.shields.io/badge/-vite-%23000000?style=flat-square&logo=vite" />
  <img alt="Static Badge" src="https://img.shields.io/badge/-ThreeJs-000?style=flat-square&logo=threedotjs">
  <img alt="Static Badge" src="https://img.shields.io/badge/-sass-000?style=flat-square&logo=sass">
  <img alt="Static Badge" src="https://img.shields.io/badge/-pnpm-%23000?style=flat-square&logo=pnpm">
</div>
<br/>

`博客主页`：<a>https://www.shmilyyy.cn</a>

`CSDN主页`：<a>https://blog.csdn.net/shmilynn_?spm=1001.2014.3001.5343</a>

`GitHub主页`：<a>https://github.com/IsMShmily</a>

---

### 项目结构

```md
├─ public                   # 静态资源
├─ src                      # 根目录
│  ├─ App.vue
│  ├─ api                   
│  │  ├─ backend            # 后端接口
│  │  ├─ common             # 公共接口
│  │  └─ index.ts
│  ├─ assets
│  ├─ components            # 组件
│  ├─ global                # 全局
│  ├─ hook                  # 钩子
│  ├─ main.ts
│  ├─ pages                 # 页面
│  ├─ plugins               # 插件
│  ├─ router                # 路由
│  ├─ store                 # Pinia 状态管理
│  ├─ styles
│  ├─ type.d.ts
│  ├─ types
│  ├─ utils                 # 工具文件
│  └─ vite-env.d.ts
├─ .env
├─ .env.development
├─ .env.production
├─ .prettierrc.json
├─ CHANGELOG.md
├─ LICENSE
├─ README.md
├─ commitlint.config.js     # Commitlint 配置
├─ eslint.config.js
├─ index.html
├─ package.json
├─ pnpm-lock.yaml
├─ postcss.config.js        # PostCSS 配置
├─ tailwind.config.js       # Tailwind CSS 配置
├─ tsconfig.json
├─ tsconfig.node.json
└─ vite.config.ts
```

### 开始使用
默认情况下，您的电脑应该已经安装了 Node.js、Vue、MongoDB 和代码编辑器。请参考我的环境配置：
```
Node.js: v18.18.0
@vue/cli 5.0.8
```
```
git clone https://github.com/IsMShmily/Vue3_Ts_blog.git
```

| 命令          | 说明                        |
| -------------- | ------------------------------ |
| pnpm i         | 安装依赖          |
| pnpm run dev   | 启动开发服务器     |
| pnpm run build | 构建生产环境         |

---

### Next.js 系列

- [Next.js 15 入门](https://blog.csdn.net/shmilynn_/article/details/137891060?spm=1001.2014.3001.5502)
- [Next.js 15 - App Router](https://blog.csdn.net/shmilynn_/article/details/137904724?spm=1001.2014.3001.5502)
- [Next.js 15 - 使用 Route Handlers](https://blog.csdn.net/shmilynn_/article/details/146515380?spm=1001.2014.3001.5501)
- [Next.js 15 - 使用 Middleware](https://blog.csdn.net/shmilynn_/article/details/146543636?spm=1001.2014.3001.5501)
- [Next.js 15 - 理解 CSR、SSR、SSG 和 ISR](https://blog.csdn.net/shmilynn_/article/details/146544013?spm=1001.2014.3001.5501)
- [Next.js 15 - 服务端组件(RSC)与客户端组件](https://blog.csdn.net/shmilynn_/article/details/146572565?spm=1001.2014.3001.5501)
- [Next.js 15 - 客户端组件](https://blog.csdn.net/shmilynn_/article/details/146582184?spm=1001.2014.3001.5501)
- [Next.js 15 - 什么是流式传输？](https://blog.csdn.net/shmilynn_/article/details/146582094?spm=1001.2014.3001.5501)
- [Next.js 15 - 服务端渲染策略](https://blog.csdn.net/shmilynn_/article/details/146582209?spm=1001.2014.3001.5501)

---

### TypeScript 体操系列

- [为什么 TypeScript 被称为类型体操？](https://blog.csdn.net/shmilynn_/article/details/137981157?spm=1001.2014.3001.5502)
- [TypeScript 支持哪些类型和类型运算（上）](https://blog.csdn.net/shmilynn_/article/details/137996269?spm=1001.2014.3001.5502)
- [TypeScript 支持哪些类型和类型运算（下）](https://blog.csdn.net/shmilynn_/article/details/138050067?spm=1001.2014.3001.55022)
- [TypeScript 类型体操详解：extends 和 infer](https://blog.csdn.net/shmilynn_/article/details/138072708?spm=1001.2014.3001.5502)

---

