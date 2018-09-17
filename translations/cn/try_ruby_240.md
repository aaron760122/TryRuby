---
lang:   CN
title:  一本空白的书
answer: ^(splendid|quite_good|mediocre|quite_not_good|abysmal)$
load:   books = {}
ok:     是的，这是一个新的评论
error:  使用splendid(出色的), quite_good(相当好的), mediocre(非常好的), quite_not_good(相当不好), abysmal(糟透的). 不要忘记了冒号":"
---

你做了一个空的 __hash__(哈希)。哈希就像一个数组，只是它的每个元素都有一个名字。

我们将在我们的新 __hash__ 中填写一些微型书评。这是我们的评级系统：

- :splendid &rarr; 杰作
- :quite\_good &rarr; 非常好
- :mediocre &rarr; 一般的
- :quite\_not\_good &rarr; 相当不好
- :abysmal &rarr; 糟透的

要为一本书评分，请将标题放在方括号中，并将等级放在"="之后。例如：

    books["Gravitys Rainbow"] = :splendid

> 到目前为止，我认为让TryRuby的所有课程彼此分开是公平的。
> 因此，如果你疯狂地在这里输入书评，你只能在本课中使用'em。  
> 如果您想在下一课中使用您的评论，则应 复制/粘贴 它们。  
> 不要太担心这一点，每节课都有很多预定义的东西供你玩。
