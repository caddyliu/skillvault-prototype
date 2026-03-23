# SkillVault 原型实验室

## 📁 项目结构

```
skillvault-prototype/
├── index.html           # 导航首页 - 选择原型版本
├── v1-technical.html    # v1 技术版原型 - 适合技术人员
├── v2-user-friendly.html  # v2 用户友好版原型 - 适合非技术人员
└── README.md            # 项目说明文档
```

## 🧪 原型对比

### v1 - 技术版 (v1-technical.html)
- **目标用户**：技术人员、开发者
- **核心隐喻**：版本管理系统
- **展示方式**：代码 diff、行数统计
- **审批方式**：详细审查后批准
- **分组方式**：按技术模块

**主要功能：**
- Skill 列表显示
- Diff 变更对比（代码级）
- 变更统计（新增行数、删除行数、修改文件数）
- 版本历史管理
- 技术审批流程

### v2 - 用户友好版 (v2-user-friendly.html)
- **目标用户**：非技术人员、业务人员
- **核心隐喻**：助手成长日记
- **展示方式**：效果预览、使用示例
- **审批方式**：👍/👎 一键决策
- **分组方式**：按使用场景

**主要功能：**
- 助手本领列表
- 一句话说明（能帮你做什么）
- 效果对比（Before/After）
- 使用示例（你可以说的话）
- 直接审批（确认学习/暂时不需要）
- 历史版本查看

## 🎨 设计差异对照

| 特性 | v1 技术版 | v2 用户友好版 |
|------|-----------|---------------|
| 首页标题 | SkillVault - Skill 版本管理 | 我的助手 - AI 技能成长空间 |
| 色彩方案 | 深色主题 (dark mode) | 浅色主题 (light mode) |
| 字体选择 | 等宽字体 (monospace) | 圆润字体 (sans-serif) |
| 核心概念 | 版本管理 | 助手学习 |
| 变更展示 | Code Diff | Before/After 图片 |
| 审批方式 | 详细审查弹窗 | 一键approve/reject按钮 |
| 分组逻辑 | feishu-* 技术模块 | 数据处理、时间管理等场景 |

## 🚀 使用方法

### 1. 本地打开
```bash
open index.html
# 或
open v1-technical.html
open v2-user-friendly.html
```

### 2. GitHub Pages 部署
- 默认首页是 `index.html`
- 可通过导航页访问所有原型版本
- 新增原型只需添加到导航页

### 3. 添加新原型
1. 创建新 HTML 文件：`v3-new-feature.html`
2. 在 `index.html` 中添加导航卡片
3. 链接指向新原型

## 📝 设计原则

### v1 - 技术版
- ✅ 完整的技术细节
- ✅ 精确的变更对比
- ✅ 开发者熟悉的术语
- ✅ 深色主题（IDE 风格）

### v2 - 用户友好版
- ✅ 生活化的隐喻（"助手学习"）
- ✅ 业务语言（不说"diff"说"哪里变好了"）
- ✅ 效果可视化（Before/After 图）
- ✅ 一键决策（👍/👎）
- ✅ 浅色温暖主题

## 🎯 下一步

- [ ] 添加 v3 - 团队协作版
- [ ] 添加对比说明文档
- [ ] 收集用户反馈
- [ ] 基于反馈迭代设计

## 💡 反馈渠道

有任何想法？欢迎在 GitHub Issues 中反馈：

https://github.com/caddyliu/skillvault-prototype/issues

---

**Last Updated:** 2026-03-23  
**Maintained by:** Caddy  
**License:** MIT
