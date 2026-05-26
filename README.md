# DeepBlueIdentity — AI身份提示词库

专属角色扮演提示词仓库，为驾驭智能体提供专业AI助手人格切换能力。

## 目录结构

```
DeepBlueIdentity/
├── manifest.json          # 资源索引
└── identities/            # 角色身份提示词
    └── <category>/        # 按角色分类
        └── <name>.md      # YAML frontmatter + Markdown
```

## 资源格式

每个身份提示词文件包含 YAML frontmatter 和 Markdown 正文：

```markdown
---
id: identity-<type>-<sequence>
name: 角色名称
type: identity
category: 角色分类
score: 4.5
summary: 角色用途简述
source_url: 
tech_stack: []
---

# 角色定义正文
...
```

## 使用方式

通过深蓝工坊的驾驭智能体，在开发专业任务时自动匹配对应的身份提示词，让 AI 以特定角色身份工作。
