+++
date = '2026-05-19T15:18:01+08:00'
draft = false
title = 'Add New Note'
+++
1. 进入项目目录
   cd E:\zozowbsite
2. 创建新文章
   hugo new content posts/my-note.md
3. 编辑文章
   * 用记事本打开 E:\zozowbsite\content\posts\my-note.md
   * 将`draft = true` 改为 `draft = false`
   * 修改标题、添加正文内容、保存
4. 生成静态文件
   hugo --minify
5. 提交到git并推送云端
   * git add .
   * git commit -m “add my note”
   * git push
6. 等待片刻 刷新网站 `https://zozo-website.1784427175.workers.dev`
7. 添加文件/图片：将图片放入 `static/images`,然后文章中用`![describe](/images/fname.jpeg)`引用；文件放入 `static/files/`，用`[download](/files/fname.pdf)`链接