# Task Ticket

任务编号：PG-DESIGN-IMG-20260611-001

状态：TODO

Owner：phone-claw

Lock：prompts/parent_guide_design_image_prompts.md, outputs/parent-guide/design-images/

## 目标

为「父母指南」微信小程序生成 8 张后续设计图，覆盖首页、信息收集页、答题页、结果页、心路历程页、海报分享页、课程/行动清单页、历史记录页。

## 背景

「父母指南」是一个父母育儿风格测评小程序。当前代码目录为 `E:\personal-code\parents-test`，已经有基础页面框架，但后续需要更完整、更一致的设计图来指导前端精修和上线前体验优化。

设计方向：温暖、安全感、不评判、陪伴感、真实生活、手绘温度。不要科技感，不要 AI 感，不要模板化营销风。

## 输入材料

- 提示词文件：`prompts/parent_guide_design_image_prompts.md`
- 代码目录：`E:\personal-code\parents-test`
- 产品资产目录：`D:\personnal-assets\personnal-assets\projects\parent-guide`
- 参考文档：`D:\personnal-assets\personnal-assets\projects\parent-guide\docs\父母指南_上线前检查清单.md`

## 交付物

请生成并保存以下 8 张 PNG：

- `outputs/parent-guide/design-images/page_01_home.png`
- `outputs/parent-guide/design-images/page_02_info.png`
- `outputs/parent-guide/design-images/page_03_quiz.png`
- `outputs/parent-guide/design-images/page_04_result.png`
- `outputs/parent-guide/design-images/page_05_journey.png`
- `outputs/parent-guide/design-images/page_06_poster.png`
- `outputs/parent-guide/design-images/page_07_courses.png`
- `outputs/parent-guide/design-images/page_08_history.png`

同时输出一份简短说明：

- `outputs/parent-guide/design-images/README.md`

说明每张图对应的页面、生成工具、生成时间、是否需要返工。

## 验收标准

- 8 张设计图均为 375x812px PNG。
- 文件名与交付物列表完全一致。
- 中文文字清晰可读，无乱码。
- 8 张图风格统一，像同一个微信小程序。
- 不出现 AI、算法、智能诊断、精准诊断等字样。
- 不使用 emoji 字符。
- 不出现科技感、霓虹渐变、机器人、芯片、抽象几何主视觉。
- 每张图都能指导前端实现，布局、按钮、卡片、状态清楚。
- 文字不溢出，元素不重叠。

## 权限

按 `rules/approval_policy.md` 执行。

额外授权：

- 允许 phone-claw 使用移动端图片生成工具生成草图。
- 允许 pc-claw 在本地整理、重命名、压缩图片。
- 允许 admin-ai 要求返工，但不要同时让多个 Claw 修改同一张图。

## 禁止事项

- 未经明确授权，不要公开发布这些设计图。
- 不要改动 `E:\personal-code\parents-test` 的代码。
- 不要删除旧设计稿。
- 不要使用含版权风险的真实人物照片、品牌素材或平台截图。
- 不要把二维码做成真实可扫码链接，除非用户另行提供小程序码。

## 执行记录

- 时间：2026-06-11
- 操作：创建任务票据和提示词文件
- 结果：待执行

## 阻塞

- 阻塞原因：无
- 已尝试：已整理完整提示词
- 需要确认：如生成工具无法准确输出中文 UI，可先生成低字版视觉稿，再交给 pc-claw 用前端或设计工具复刻文字。

## 结果

- 产出链接：待回填
- 截图：待回填
- PR：无
- 发布链接：无
- 测试结果：待回填

## 复盘

- 做得好的地方：待回填
- 问题：待回填
- 下次改进：待回填
- 写入记忆库的偏好：待回填
