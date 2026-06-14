# AI Shared Knowledge Base

这是一个供多个 AI 智能体共享的知识库，本地和远程的 agent 都可以访问。

## 目录结构

```
ai-shared-kb/
├── 技术文档/      # 技术相关的文档、API 说明、架构设计等
├── 项目笔记/      # 项目进展、决策记录、会议纪要等
├── 工作流程/      # 标准操作流程、工作规范等
└── README.md      # 本文件
```

## 使用指南

### 对于本地 Agent
直接读取文件系统中的 Markdown 文件即可。

### 对于远程 Agent
通过 GitHub API 或 clone 仓库访问：
```bash
git clone https://github.com/<your-username>/ai-shared-kb.git
```

### 贡献指南
1. 创建新文件时使用 Markdown 格式
2. 文件名使用中文或英文均可
3. 每个文件应包含清晰的标题和摘要
4. 提交时写清楚 commit message

## 文件命名建议
- 使用有意义的名称，如 `API认证流程.md`
- 避免特殊字符和空格
- 日期格式建议：`YYYY-MM-DD`
