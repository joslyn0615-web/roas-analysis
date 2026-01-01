# roas-analysis
Ad Campaign ROAS Optimization Project
🔍 项目简介
本项目基于 1000 组广告投放活动数据，分析 ROAS 表现、挖掘影响因素、探索优化路径，并设计 A/B 测试验证策略。最终输出可落地的投放优化方案。

📁 项目结构
├── clean_analysis.ipynb     # 干净版 notebook，适合阅读
├── raw_notebook.ipynb       # 原始 notebook（可选）
├── data/                    # 数据（如无法上传可放说明）
├── images/                  # 图表截图
└── ppt/                     # 作品集 PPT（可选）

🧠 核心内容
数据清洗与预处理
EDA（分布、相关性、四象限分析）
高 ROAS 黄金区间挖掘（CPC ≤ 5）
决策树挖掘两条可执行高 ROAS 路径
随机森林评估变量重要性
投放优化策略 & 场景模拟
A/B 测试验证方案


📊 技术栈
Python（Pandas、NumPy、sklearn）
可视化（Matplotlib、Seaborn）
机器学习（DecisionTree、RandomForest）
