# 🌱 Hexo-Source | xiaochengxuyuan的博客源码

> 本仓库保存博客的 **源码**（文章、主题、配置）。  
> 生成的静态页面部署在 [xiaochenxuyuan.github.io](https://xiaochenxuyuan.github.io)。

---

## 📦 快速开始（换电脑 3 步复活）

```bash
# 1. 克隆源码（含子模块主题）

git clone --recursive https://github.com/xiaochenxuyuan/hexo-source.git
cd hexo-source

# 2. 安装依赖

npm ci          # 严格按 lock 版本

# 3. 本地预览

hexo server     # http://localhost:4000
```

## 🏗️ 日常写作流程

``` bash
graph LR
 A[hexo new post "标题"] --> B[Markdown 写作]
 B --> C[hexo server 本地预览]
 C --> D[git push 备份源码]
 D --> E[hexo d 部署 GitHub Pages]
```

## 📁 目录一览

```bash
hexo-source
├─ _config.yml # 站点配置
├─ source/_posts/ # 博客文章
├─ themes/anzhiyu # 主题（子模块）
├─ scaffolds/ # 文章模板
└─ package.json # 插件依赖
```

## 🚀 部署

```bash
hexo clean && hexo generate && hexo deploy
```

## 🧩 常用命令备忘录

| 需求     | 命令                   |
| ------ | -------------------- |
| 新建文章   | `hexo new post <标题>` |
| 新建页面   | `hexo new page <标题>` |
| 本地实时预览 | `hexo server`        |
| 生成静态文件 | `hexo generate`      |
| 一键部署   | `hexo deploy`        |
| 清理缓存   | `hexo clean`         |

## 📄 License

MIT © [xiaochenxuyuan](https://github.com/xiaochenxuyuan)
