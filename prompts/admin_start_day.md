# Admin Start Day Prompt

管理员，开始今日调度。

请读取并遵守：

- `rules/agent_roles.md`
- `rules/approval_policy.md`
- `rules/workflow_rules.md`
- `rules/do_not_do.md`
- `memory/user_preferences.md`

执行要求：

1. 检查 `tasks/active/` 中所有任务。
2. 按优先级分配给 online-claw、mobile-claw、desktop-claw。
3. 每个任务只能有一个主负责人。
4. 除 `approval_policy.md` 中必须确认的事项外，不要打扰用户。
5. 每 2 小时只汇报：已完成、阻塞、待用户确认。
6. 晚上生成日报并写入 `logs/`。

