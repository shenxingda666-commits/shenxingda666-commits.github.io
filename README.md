# 随笔

一个使用 [Jekyll](https://jekyllrb.com/) 搭建、托管在 GitHub Pages 上的个人随笔站。

## 写一篇新随笔

1. 在 `_posts/` 目录下新建一个文件，命名为 `年-月-日-标题.md`，例如 `2026-09-02-某个下午.md`；
2. 在文件开头写下标题和日期：

   ```markdown
   ---
   layout: post
   title: 某个下午
   date: 2026-09-02 15:00:00 +0800
   ---
   ```

3. 接着写正文即可。

推送到 `main` 分支后，GitHub Pages 会自动构建并发布。

## 修改站点信息

- 站点名称 / 简介：编辑 `_config.yml` 中的 `title` 和 `description`。
- 关于页：编辑 `about.md`。

## 本地预览（可选）

```bash
bundle install
bundle exec jekyll serve
```
