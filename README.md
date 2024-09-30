# jekyll-build-action

本人项目中使用的Jekyll构建Action，将`README.md`作为首页构建静态网站。如果项目还包含`README_zh.md`，则会构建中文首页，地址为`/zh`。

## 参数

| 参数         | 说明               | 必需 | 默认值     |
|------------|------------------|----|---------|
| `docs-dir` | 文档目录，指定构建的源目录    | 是  | -       |
| `site-dir` | 网站目录，指定构建输出的目标目录 | 否  | `_site` |

## 使用方法

见[LeeCo项目的用法](https://github.com/JezaChen/LeeCo/tree/master/.github/workflows)

