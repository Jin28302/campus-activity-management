# 配置管理文档

## 1. 配置项范围
- README.md
- 01-project-charter.md
- 02-wbs.md
- 03-schedule.md
- 04-config-plan.md
- 05-summary-report.md
- conflict.md

## 2. 分支策略
- `main`：稳定版本，仅允许通过 PR 合并
- `dev`：集成开发分支
- `feature-*`：功能/文档分支

## 3. 命名约定
- 文档命名：数字前缀 + 英文小写 + 连字符
- 分支命名：`feature/<功能名>`
- 提交信息：`<type>: <subject>`

## 4. 合并规则
- feature → dev：需经一人审阅（项目经理审核）
- dev → main：由项目经理执行
- 出现冲突时，由相关成员手工解决

## 5. 版本留痕
- 每次提交使用有意义的 message
- 最终版本打标签 `v1.0-final`
- 每个成员使用拼音全称作为 `user.name`
