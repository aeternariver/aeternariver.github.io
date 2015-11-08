---
layout: post
title:  "我的第一篇日志 - 论如何发布日志"
date:   2015-11-08 00:00:58 +0800
categories: jekyll update
---
今天正式启用自己的域名，来记录一些没有具体规划的东西。规则是每天一篇，如果某天不幸没能完成，第二天就要写好两篇（补上前一天的份额）。

下面总结一下用 Jekyll 发布日志的流程。（话外，之所以想起要写Blog，是因为偶然间提到了 **Dr Jekyll and Mr Hyde** 这部音乐剧，让某灯想起了 **Jekyll** 这个日志工具。）

1. 写文章 <br>
  在 `/Users/Bai/Blog/_posts` 中，用 Atom 新建并编辑 `.md` 文档。文档命名格式为：<br> 2015-11-08-start-from-here.md <br>
  （日期 + 名称）
<br>
2. 本地预览 <br>
  - 在 Terminal 中写入你的 Blog 所在的位置。对我来说，就是：<br>
  `Bai$ cd /Users/Bai/Blog`
  - 启动 Jekyll：<br>
  `Bai$ jekyll serve`
  - 查看 `http://localhost:4000/`，你的日志便在那里了。
<br>

3. 发布 <br>
  在 GitHub 中 Commit，然后 Sync 即可~ <br>
  每次 Commit 都要慎重，因为 Commit 的改动会被记录下来，而且凭我自己可能无法顺利删掉。
<br>

很晚了，已经23:30，该睡啦！
