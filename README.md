# Java Development Manual Skill

基于阿里巴巴 Java 开发手册（嵩山版）的 Claude Code Skill，为 AI 辅助编程提供 Java 开发规范参考。

## 简介

本 Skill 将阿里巴巴 Java 开发手册的规约整理为结构化文档，涵盖 7 大维度：

| 维度 | 说明 |
|------|------|
| 编程规约 | 命名风格、代码格式、OOP 规约、并发处理、集合处理 |
| 异常日志 | 错误码规范、异常处理、日志规约 |
| 单元测试 | 测试用例、覆盖率、Mock 规范 |
| 安全规约 | SQL 注入、XSS、CSRF、数据脱敏 |
| MySQL 数据库 | 建表规约、索引规范、SQL 规约、ORM 规约 |
| 工程结构 | 分层架构、依赖管理、服务器规约 |
| 设计规约 | UML 规范、设计模式、设计原则 |

## 安装使用

### 方法一：克隆到 Claude Code skills 目录

```bash
cd ~/.claude/skills
git clone https://github.com/<your-username>/java-development-manual.git
```

### 方法二：手动复制

将 `.claude/skills/java-development-manual` 目录复制到你的 Claude Code skills 目录。

## 目录结构

```
.claude/skills/java-development-manual/
├── SKILL.md                    # Skill 主文件
└── references/                 # 详细规约文档
    ├── coding-convention.md    # 编程规约
    ├── exception-log.md        # 异常日志
    ├── unit-test.md            # 单元测试
    ├── security.md             # 安全规约
    ├── mysql.md                # MySQL 数据库
    ├── project-structure.md    # 工程结构
    └── design.md               # 设计规约
```

## 规约级别说明

| 级别 | 含义 | 说明 |
|------|------|------|
| **【强制】** | 必须遵守 | 违反可能导致严重问题 |
| **【推荐】** | 建议遵守 | 提升代码质量和可维护性 |
| **【参考】** | 可选择性采纳 | 根据实际情况判断 |

## 使用场景

- 编写或审查 Java 代码
- 检查命名/代码规范
- 处理异常和日志
- 编写单元测试
- 安全编码
- 数据库设计
- 工程架构设计

## 声明

本 Skill 基于《阿里巴巴 Java 开发手册（嵩山版）》整理，仅供学习参考。

- 原手册版权归原作者所有
- 本项目仅对规约进行结构化整理，方便 AI 辅助编程时参考

## License

本项目的整理内容采用 MIT License，但原《阿里巴巴 Java 开发手册》的内容版权归阿里巴巴集团所有。

