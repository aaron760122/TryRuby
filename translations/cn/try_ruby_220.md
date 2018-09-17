---
lang:   CN
title:  链接方法的圆环
answer: ^More still did (.+)
load:   prev
ok:     表现的不错, 我的朋友! 这个join方法拿到这行数组，并把他们组合成一个字符串。
error:  
---

那你现在看到了什么? 这里发生了什么? 你键入 __poem.lines.reverse__ 后什么发生了?

发生了两件事. 你使用lines方法把这首诗放到了一行列表中。
使用"Lines"方法，决定了这种转换方式是先把字符串拆分并将它们转换到一个数组中。

然后, 你翻转这个列表。你有了每一行。你反转了他们。仅此而已。

让我们在后面添加更多的方法:

    puts poem.lines.reverse.join

 像这种组合方法被称为 _method chaining_ (链接调用)。
