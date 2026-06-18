# ecommerce-image-diagnosis

**电商主图 & 详情页诊断 WorkBuddy Skill**

给它商品主图、详情页截图、搜索结果截图或商品链接，自动生成结构化 HTML 可视化诊断报告。

## 功能

- **多输入支持**：主图图片 / 详情页截图 / 搜索结果截图 / 商品链接（任意组合）
- **10维度评分**：主图（视觉清晰度、信息传达、差异化、信任感、平台合规）+ 详情页（首屏冲击力、信息架构、场景化呈现、信任背书、转化促进），共200分
- **综合评级**：S / A / B / C / D
- **行动清单**：P0 立即修复 / P1 本周优化 / P2 下次迭代
- **平台覆盖**：淘宝、拼多多、抖音电商、京东

## 触发词

主图诊断、详情页诊断、商品图分析、主图优化、帮我看看主图、分析详情页、ecommerce image diagnosis

## 文件结构

```
├── SKILL.md                           # 主流程定义
├── references/
│   └── diagnosis_framework.md        # 诊断维度评分标准
└── scripts/
    └── generate_report.py            # HTML 报告生成脚本
```

## 安装

将整个目录放入 `~/.workbuddy/skills/ecommerce-image-diagnosis/` 即可在 WorkBuddy 中使用。

## 使用示例

```
用户：帮我诊断一下这个主图 [上传图片]
→ 自动触发诊断流程，输出 HTML 报告
```

---

Made with ❤️ for Chinese e-commerce sellers
