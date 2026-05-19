+++
date = '2026-05-19T15:33:54+08:00'
draft = false
title = 'Del Not'
+++
1. 进入项目目录
    cd E:\zozowbsite
2. 删除源文件
    del content\posts\fname.md
3. 重新生成静态文件
    hugo --minify
4. 提交删除到git
    git add -A
    git commit -m “del-file”
    git push
5. 等待刷新网站
6. 删除图片/附件: 如果文中引用了 `static/`的文件，需要手动删除文件，否则仍会存在于public但无人链接