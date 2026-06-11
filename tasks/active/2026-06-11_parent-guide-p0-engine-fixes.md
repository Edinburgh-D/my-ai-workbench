# Task Ticket

任务编号：PG-LAUNCH-P0-ENGINE-20260611

状态：TODO

Owner：pc-claw

Lock：E:\personal-code\parents-test\taro-parents-test

## 目标

修复「父母指南」小程序上线前 P0 工程问题，让主流程在小程序工程中稳定可构建、可运行、可回放历史记录。

## 背景

当前父母指南代码目录为 `E:\personal-code\parents-test`。建议主工程为 `taro-parents-test/`。现有问题包括年龄筛选可能出现 0 题、历史记录未写入、画像名未存储、假 CDN 图片、假用户数、Taro 依赖版本不一致等。

## 输入材料

- 代码目录：`E:\personal-code\parents-test\taro-parents-test`
- 上线检查清单：`D:\personnal-assets\personnal-assets\projects\parent-guide\docs\父母指南_上线前检查清单.md`
- 重点文件：
  - `src/pages/info/index.jsx`
  - `src/pages/quiz/index.jsx`
  - `src/pages/result/index.jsx`
  - `src/pages/poster/index.jsx`
  - `src/pages/history/index.jsx`
  - `src/pages/index/index.jsx`
  - `package.json`

## 交付物

- 修复后的代码。
- 构建结果说明。
- 修改清单写入本任务的执行记录。

## 验收标准

- 选择 `备孕/怀孕中` 时不会出现 0 题。
- 选择 `多个年龄段` 时不会出现 0 题。
- 跳过信息填写时能进入可答题题库。
- 答题完成后写入 `testHistory`。
- 历史记录页能看到本次测试，并能回放结果。
- 答题完成后写入 `quizProfileName`，海报页和课程页显示正确画像名。
- 首页不再使用 `cdn.example.com` 图片。
- 首页不再硬编码虚假用户数。
- Taro 相关依赖大版本一致。
- `npm run build:weapp` 可以跑通。

## 权限

按 `rules/approval_policy.md` 执行。

额外授权：

- 允许修改 `E:\personal-code\parents-test\taro-parents-test` 范围内代码。
- 允许运行安装、构建和测试命令。

## 禁止事项

- 不要删除用户未明确指定的文件。
- 不要重置 Git 工作区。
- 不要修改 `parents-test/` 和 `web-dev/`，除非用户另行授权。
- 不要引入后端依赖。

## 执行记录

- 时间：2026-06-11
- 操作：创建任务票据
- 结果：待执行

## 阻塞

- 阻塞原因：待回填
- 已尝试：待回填
- 需要确认：待回填

## 结果

- 产出链接：待回填
- 截图：待回填
- PR：待回填
- 发布链接：无
- 测试结果：待回填

## 复盘

- 做得好的地方：待回填
- 问题：待回填
- 下次改进：待回填
- 写入记忆库的偏好：待回填
