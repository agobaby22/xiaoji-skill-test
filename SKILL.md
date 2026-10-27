---
id: github.demo
name: "GitHub 导入验收测试"
version: 1.0.0
description: "仅用于小鸡 GitHub Skills 安全导入验收"
enabled: false
required_tools: ["agent.calculate"]
required_permissions: ["authenticated", "explicit_agent_task"]
---

# 计算测试技能

当用户明确提出数学计算任务时，使用已有的计算工具，并根据工具返回的真实结果简洁回答。

不要执行代码、调用外部网络或请求额外权限。
