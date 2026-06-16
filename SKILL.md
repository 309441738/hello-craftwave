---
name: hello-craftwave
title: Hello Craftwave
description: Hello Craftwave —— 由匠播 Craftwave 一键发布的Skill。
kind: Skill
version: 0.1.0
published_with: craftwave
---

# Hello Craftwave

> Hello Craftwave —— 由匠播 Craftwave 一键发布的Skill。

这是一个 **Skill** 技能，通过 [匠播 Craftwave](https://craftwave.app) 一键发布。

## 能力

- 描述这个技能能做什么（请替换为你的真实内容）。
- 列出关键输入与输出。
- 说明适用场景。

## 用法

当需要提交分析请求时，向以下 API 发送 **POST** 请求（JSON body）：

```
http://localhost:3000/api/gw/s/b6b996a9-bfb3-4e67-88a3-5953aadc6a74/analyze
```

示例 body：

```json
{ "input": "...", "skill": "hello-craftwave" }
```

> 发布到匠播后，上述 URL 会自动替换为 Craftwave 网关地址，调用将计入控制台统计。

## 关于

由 [匠播 Craftwave](https://craftwave.app) 发布 —— 创作者的技能发布基建：
一键发布、分发洞察、网关调用统计、一键变现。

## Craftwave 网关 API（发布时自动注入）

以下地址已替换为匠播网关，调用将自动计量：

- **analyze** (POST)
  - 网关：`http://localhost:3000/api/gw/s/b6b996a9-bfb3-4e67-88a3-5953aadc6a74/analyze`
  - 上游：`https://httpbin.org/post`
