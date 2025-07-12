# 项目目录结构

## 📁 目录组织

```
lead_weight_round_robin/
├── pages/                    # 📄 HTML页面文件
│   ├── assignGroupEdit_Plan1.html    # 分配组编辑页面 - 方案1（主要版本）
│   ├── assignGroupEdit_Plan2.html    # 分配组编辑页面 - 方案2
│   ├── lead_assignWRR.html          # 线索分配权重轮询页面
│   ├── lead_assign_advanced.html    # 高级线索分配页面
│   ├── lead_assign_demo.html        # 线索分配演示页面
│   └── version2_from_gemini.html    # Gemini生成的版本2
├── docs/                    # 📚 文档文件
│   ├── readme.md                    # 项目说明
│   ├── log.md                       # 开发日志
│   ├── design_review.md             # 设计评估报告
│   ├── staffinfo.md                 # 员工信息
│   └── newAssignGroupPageREQ.MD     # 新分配组页面需求
├── data/                    # 📊 数据文件
│   └── user.csv                     # 用户数据
├── currentDesign/           # 🎨 设计文件
│   ├── assignGroupList.html         # 分配组列表页面
│   ├── currentassigndialog.html     # 当前分配对话框
│   ├── 1.AssignGroup_LIST.png       # 分配组列表设计图
│   └── 2. editAssignGroup.png       # 编辑分配组设计图
├── .gitignore               # Git忽略文件配置
└── PROJECT_STRUCTURE.md     # 项目结构说明（本文件）
```

## 🎯 文件说明

### 📄 页面文件 (pages/)
- **assignGroupEdit_Plan1.html** - 主要的分配组编辑页面，功能最完整
- **assignGroupEdit_Plan2.html** - 替代方案的分配组编辑页面
- **lead_assignWRR.html** - 线索分配权重轮询算法演示页面
- **lead_assign_advanced.html** - 高级线索分配功能页面
- **lead_assign_demo.html** - 基础线索分配演示页面
- **version2_from_gemini.html** - AI生成的版本2页面

### 📚 文档文件 (docs/)
- **readme.md** - 项目总体说明和使用指南
- **log.md** - 详细的开发日志和版本变更记录
- **design_review.md** - 设计评估报告，包含改进建议
- **staffinfo.md** - 员工信息和相关说明
- **newAssignGroupPageREQ.MD** - 新分配组页面的需求文档

### 📊 数据文件 (data/)
- **user.csv** - 用户数据，包含员工信息

### 🎨 设计文件 (currentDesign/)
- **assignGroupList.html** - 分配组列表页面的设计实现
- **currentassigndialog.html** - 当前分配对话框的设计实现
- **1.AssignGroup_LIST.png** - 分配组列表的设计图
- **2. editAssignGroup.png** - 编辑分配组的设计图

## 🚀 快速开始

1. **查看主要功能**：打开 `pages/assignGroupEdit_Plan1.html`
2. **了解项目背景**：阅读 `docs/readme.md`
3. **查看开发历程**：阅读 `docs/log.md`
4. **查看设计评估**：阅读 `docs/design_review.md`

## 📝 项目特点

- **静态页面**：纯HTML+CSS+JavaScript实现
- **产品演示**：适合产品经理演示和原型验证
- **功能完整**：包含完整的CRUD操作和交互逻辑
- **多方案对比**：提供多个版本的页面供选择

## 🔧 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式设计
- **JavaScript (ES6+)** - 交互逻辑
- **Tailwind CSS** - 样式框架
- **SVG** - 图标和头像系统 