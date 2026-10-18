# 个人简历（My Resume）

一个基于 HTML + CSS 的个人简历网页，由 ASP.NET Web 项目改造而来，现为纯静态单页，可直接托管到 GitHub Pages。

## 文件说明

| 文件 / 目录 | 说明 |
| --- | --- |
| `index.html` | 简历主页（GitHub Pages 默认首页） |
| `My Resume.html` | 简历页面（精修版） |
| `StyleSheet.css` | 样式表（深 / 浅色自适应） |
| `pictures/` | 头像与照片 |
| `backup/` | 原始版本备份 |
| `MY Resume.sln` / `Web.config` | 原 ASP.NET 项目文件 |

## 本地预览

```sh
# 直接双击打开
start index.html          # Windows
open  index.html          # macOS

# 或起本地服务
python -m http.server 8000
```

## 在线访问

启用 GitHub Pages 后访问：

```text
https://linsezhitu.github.io/my-resume/
```
