# BellLab4TIQC 组织网站

BellLab4TIQC 的公开组织首页，使用 GitHub Pages 托管。

**网站地址：** https://belllab4tiqc.github.io/

## 文件说明

| 文件 | 用途 |
| --- | --- |
| `index.html` | 页面结构、组织介绍与导航链接 |
| `style.css` | 视觉样式及移动端布局 |
| `favicon.svg` | 浏览器标签图标 |
| `.nojekyll` | 告诉 GitHub Pages 直接发布静态文件 |

网站使用原生 HTML、CSS 和 SVG，不需要安装依赖或执行构建。

## 修改网站

1. 修改 `index.html` 中的文字、链接，或 `style.css` 中的样式。
2. 在浏览器中预览页面，检查桌面和手机宽度下的显示及链接。
3. 通过 Pull Request 讨论改动，合并到 `main` 后由 GitHub Pages 发布。

如需本地预览，可在仓库目录运行：

```sh
python -m http.server 8000
```

然后打开 <http://localhost:8000>。

## GitHub Pages 设置

仓库名应为 `belllab4tiqc.github.io`。在仓库 **Settings → Pages → Build and deployment** 中选择：

- Source：**Deploy from a branch**
- Branch：**main**
- Folder：**/ (root)**

默认使用 `https://belllab4tiqc.github.io/`，不需要自定义域名。不要删除 `.nojekyll`。

## 内容范围

此仓库和网站均为公开内容。适合维护组织介绍、通用软件方向和公开入口；内部仓库的详细设计、运行环境、实验数据、设备地址与凭据应保存在有访问控制的内部文档中。

页面中的离子链为概念插图，不代表实际设备结构。

## 相关入口

- [GitHub 组织](https://github.com/BellLab4TIQC)
- [仓库目录](https://github.com/orgs/BellLab4TIQC/repositories)
- [公开组织简介源文件](https://github.com/BellLab4TIQC/.github/blob/main/profile/README.md)
