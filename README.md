# token-cost-optimizer 🦞

OpenClaw Token 成本优化 Skill，从8个维度系统性降低 API 费用。

## 安装

npx clawhub install token-cost-optimizer

## 功能

- 控制上下文长度，压缩无关历史
- 要求模型简要输出，减少 output token
- 多 Agent 合理分工，避免重复请求
- 监控 API 调用频率，发现死循环
- 定期清理配置文件和过期 memory
- 切换低价模型（支持 Kimi K2.5 零成本）
- 配置自动模型路由，按复杂度选模型
- 优化定时任务，关闭无效心跳

## 使用方法

安装后在飞书/WhatsApp/Telegram 对 OpenClaw 说：
- "帮我检查 token 消耗"
- "优化一下配置"
- "有没有浪费的地方"

## 作者

taod7062-a11y
