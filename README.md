# PPC广告投放ROAS优化

本项目基于 1000 组广告投放活动数据，分析 ROAS 表现、探索影响因素、挖掘高ROAS路径，并设计 A/B 测试验证策略。最终输出可落地的优化方案。


## 🔍 项目简介
**问题**：过去一年多的 1000 条 PPC 广告投放中，预算使用效率低且回报波动大，高 ROAS 活动特征未沉淀，缺乏可复用的量化决策标准。

**目标**：通过分析广告活动，识别高 ROAS 的关键指标与稳定路径，量化投放效率，并输出可执行策略及验证方案以提升后续投放表现。

## 📁 项目结构

```text
project/
├── README.md
├── 代码notebook.ipynb                           # 代码 Notebook，分析入口
├── data/
│   ├── raw/
│   │   └── ppc_campaign_performance_data.xlsx  # 原始数据
│   └── processed/
│       └── cleaned_data.csv                    # 清洗后的数据
├── report/
│   └── 项目报告-PPC广告投放ROAS优化.pdf          # 项目分析报告
└── presentation/
    └── PPT-PPC广告投放ROAS优化.pdf              # 项目展示 PPT
```


## 🧠 核心内容
1.数据清洗与预处理

2.EDA（分布、相关性、四象限分析）

3.高 ROAS 黄金区间挖掘（CPC ≤ 5）

4.决策树挖掘两条可执行高 ROAS 路径

5.随机森林评估变量重要性

6.投放优化策略 & 场景模拟

7.A/B 测试验证方案



## 📊 技术栈
Python（Pandas、NumPy、sklearn）

可视化（Matplotlib、Seaborn）

机器学习（DecisionTree、RandomForest）
