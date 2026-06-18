# Example: Quick Explain

## User request

```text
简单解释一下 API 是什么，用大白话讲。
```

## Expected mode

快速解释

## Why this mode

用户只是想快速知道一个概念是什么，没有表达“想系统学习”或“想真正掌握”。

## Good response shape

```md
API 可以理解成“让两个软件互相说话的接口”。

比如你在一个天气 App 里看到天气，不是这个 App 自己知道天气，而是它去问天气服务，对方再把结果返回给它。

所以 API 的本质就是：
一套提前约定好的沟通方式，让一个软件可以向另一个软件要数据或让它执行动作。
```

## What should not happen

- 不要自动进入完整学习流程
- 不要生成路线图
- 不要要求用户复述
- 不要生成 Anki

## Design note

这个案例用来说明：豆芽菜学习法不是见到“知识问题”就一律重模式启动，而是先判断用户到底要的是“知道”还是“学会”。
