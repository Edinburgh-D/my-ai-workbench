# Task Ticket

任务编号：PG-LAUNCH-P1-SHARE-20260611

状态：TODO

Owner：pc-claw

Lock：E:\personal-code\parents-test\taro-parents-test\src\pages\poster, E:\personal-code\parents-test\taro-parents-test\src\pages\result

## 目标

实现「父母指南」小程序分享传播闭环：结果页能进入海报页，海报页能基于本次测试结果生成可保存、可分享的海报。

## 背景

当前海报页主要是静态 View 预览，保存按钮只是 toast，分享功能未完成。上线冷启动需要海报作为小红书、微信私域传播素材。

## 输入材料

- 代码目录：`E:\personal-code\parents-test\taro-parents-test`
- 设计图提示词：`E:\get-music\my-ai-workbench\prompts\parent_guide_design_image_prompts.md`
- 上线检查清单：`D:\personnal-assets\personnal-assets\projects\parent-guide\docs\父母指南_上线前检查清单.md`

## 交付物

- Canvas 海报生成实现。
- 保存到相册实现。
- 分享给朋友路径和文案配置。
- 小程序码或二维码占位方案。
- 真机或开发者工具验证记录。

## 验收标准

- 海报上的画像名来自本次测试结果。
- 海报上的 A/B/C/D 分数来自本次测试结果。
- 海报文案来自当前画像，不再默认“温室园丁”。
- 点击保存到相册触发真实保存流程，不只是 toast。
- 分享路径能回到小程序首页或测试入口。
- 没有真实小程序码时，用清晰占位方案，并在代码注释中说明替换点。
- 微信开发者工具中无明显报错。

## 权限

按 `rules/approval_policy.md` 执行。

额外授权：

- 允许修改 poster/result 相关页面。
- 允许新增本地静态占位素材。

## 禁止事项

- 不要使用外部 CDN 图片。
- 不要生成假二维码冒充真实可扫码链接。
- 不要引入需要后端的强依赖。
- 不要公开发布设计图或海报。

## 执行记录

- 时间：2026-06-11
- 操作：创建任务票据
- 结果：待执行

## 阻塞

- 阻塞原因：待回填
- 已尝试：待回填
- 需要确认：是否已有正式小程序码，如没有先使用占位。

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
