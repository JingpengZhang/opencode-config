# 全局约束

## 语言偏好
- 所有回复必须使用简体中文
- 思考过程使用中文
- 代码注释使用中文（除非用户要求英文）
- 技术术语可保留英文，但首次出现时应提供中文解释
- 保持简洁、专业，避免冗余的翻译腔

## Git 提交规范
- **禁止自动提交**：除非用户明确要求，否则不要执行 git commit
- **提交格式**：遵循 Angular 规范，格式为 `<type>(<scope>): <subject>`
  - type: feat | fix | docs | style | refactor | perf | test | build | ci | chore | revert
  - 示例: `feat(auth): 添加用户登录功能`
- **禁止联合作者**：commit message 中不要添加 Co-authored-by 信息
- 提交前确保变更符合预期，必要时先展示 diff 确认