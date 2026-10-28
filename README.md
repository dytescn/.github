# dytescn

dytescn 组织主页与官网源码。

- 官网：https://www.dytes.cn
- 组织主页：https://github.com/dytescn
- 核心项目：https://github.com/dytescn/dytes

## 目录

```text
profile/README.md     # GitHub 组织主页
load_pages/           # www.dytes.cn 静态站点
```

## 本地预览

```bash
cd load_pages
deno task view
```

## 发布

`load_pages/` 由 GitHub Pages workflow 部署，CNAME 指向 `www.dytes.cn`。
