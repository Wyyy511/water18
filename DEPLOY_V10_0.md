# WaterPulse V10.0 部署与 Demo

1. 将 ZIP 解压后的全部文件放到 GitHub 仓库根目录并部署 Railway。
2. Railway Variables 配置 `DEEPSEEK_API_KEY`。
3. `/api/health` 应显示 `version: 10.0`。
4. `/api/deepseek/test` 应显示 `ok: true` 才代表 DeepSeek 真实连通。

## Demo 演示顺序
- 直接提问，展示 AI 需求理解；
- 点击“体验示例”，系统自动发送甘蔗虚拟采购组合；
- 确认识别出来的 6 个节点与假设采购比例；
- 运行当前水风险分析；
- 运行主要供应地中断压力测试；
- 展示 AI 管理建议；
- 导出企业决策报告。

也可以展示“上传数据”和“Excel 模板”入口。最终 Demo 不展示非结构化报告入口。
