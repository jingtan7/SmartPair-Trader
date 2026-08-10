# SmartPair Trader

SmartPair 配对交易（Pairs Trading）分析系统。

## ✨ 规划功能

- **配对选择**：筛选具有协整关系的标的对
- **价差分析**：价差计算、z-score 标准化、均值回归判断
- **信号生成**：基于价差偏离度生成开仓/平仓信号
- **回测与统计**：策略收益、最大回撤等指标

## 🚀 打开方式

直接用浏览器打开 `index.html` 即可，无需任何服务器。

## 📁 文件结构

```
SmartPair Trader/
├── index.html          # 主页面
├── css/
│   └── style.css       # 样式
├── js/
│   └── main.js         # 配对交易主逻辑
├── data/               # 数据文件（价格、价差、信号）
├── docs/               # 设计文档
└── README.md
```

## 📦 远程仓库

```bash
git clone https://github.com/jingtan7/SmartPair-Trader.git
```
