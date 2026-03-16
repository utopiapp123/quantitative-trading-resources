# 量化股票交易开源项目资源集合

Quantitative Stock Trading Open Source Projects Collection

> 📊 精选 GitHub 高星量化交易项目 | 持续更新中
> 
> **最后更新**: 2026 年 3 月 (Tavily API 搜索验证)

---

## 📊 综合框架

### 1. [vn.py](https://github.com/vnpy/vnpy) ⭐ 20k+
- **语言**: Python
- **简介**: 中国最流行的开源量化交易框架，支持股票、期货、期权等多种交易品种
- **特点**: 
  - 完整的交易生态系统（数据、策略、回测、实盘）
  - 丰富的国内券商/期货接口
  - 活跃的中文社区
- **适合**: A 股量化交易者首选

### 2. [Backtrader](https://github.com/mementum/backtrader) ⭐ 10k+
- **语言**: Python
- **简介**: 功能强大的回测和交易框架
- **特点**:
  - 灵活的策略编写方式
  - 支持多种数据源和 broker
  - 丰富的技术指标库
- **适合**: 策略研究和回测

### 3. [Zipline](https://github.com/quantopian/zipline) ⭐ 15k+
- **语言**: Python
- **简介**: Quantopian 开发的量化回测框架
- **特点**:
  - 事件驱动架构
  - 支持美股数据
  - 因子分析工具
- **适合**: 美股量化研究

---

## 🤖 机器学习/深度学习

### 4. [FinRL](https://github.com/AI4Finance-Foundation/FinRL) ⭐ 8k+
- **语言**: Python
- **简介**: 基于深度强化学习的量化交易框架
- **特点**:
  - 支持多种 DRL 算法（PPO, A2C, SAC 等）
  - 提供美股、A 股数据接口
  - 完整的训练 - 回测 - 部署流程
- **适合**: AI 量化交易研究

### 5. [Qlib](https://github.com/microsoft/qlib) ⭐ 10k+
- **语言**: Python
- **简介**: 微软开发的 AI 量化投资平台
- **特点**:
  - 端到端的 AI 量化工作流
  - 丰富的机器学习模型
  - 高性能数据处理
- **适合**: AI 驱动的量化的研究

### 6. [FinGPT](https://github.com/AI4Finance-Foundation/FinGPT) ⭐ 5k+
- **语言**: Python
- **简介**: 开源金融大语言模型
- **特点**:
  - 金融情感分析
  - 市场预测
  - 基于 LLM 的交易策略
- **适合**: LLM+ 量化前沿研究

---

## 📈 技术分析

### 7. [TA-Lib](https://github.com/mrjbq7/ta-lib) ⭐ 9k+
- **语言**: Python/C
- **简介**: 技术分析指标库
- **特点**:
  - 150+ 技术指标
  - 高性能 C 实现
  - 多语言绑定
- **适合**: 技术指标计算

### 8. [pandas-ta](https://github.com/twopirllc/pandas-ta) ⭐ 4k+
- **语言**: Python
- **简介**: 基于 pandas 的技术分析库
- **特点**:
  - 纯 Python 实现，易安装
  - 130+ 指标
  - 与 pandas 无缝集成
- **适合**: 快速原型开发

---

## 🌐 数据获取

### 9. [yfinance](https://github.com/ranaroussi/yfinance) ⭐ 10k+
- **语言**: Python
- **简介**: Yahoo Finance 数据下载器
- **特点**:
  - 免费美股数据
  - 历史数据和实时数据
  - 简单易用
- **适合**: 数据获取入门

### 10. [akshare](https://github.com/akfamily/akshare) ⭐ 15k+
- **语言**: Python
- **简介**: 中国金融数据接口库
- **特点**:
  - 覆盖 A 股、期货、基金等
  - 免费开放数据源
  - 持续更新维护
- **适合**: A 股数据获取

### 11. [Tushare](https://tushare.pro/) 
- **语言**: Python
- **简介**: 中国金融数据社区（部分免费）
- **特点**:
  - 丰富的 A 股数据
  - 稳定的 API 服务
  - 积分制访问
- **适合**: 专业 A 股研究

---

## 🎯 策略库

### 12. [QuantConnect Lean](https://github.com/QuantConnect/Lean) ⭐ 7k+
- **语言**: C#/Python
- **简介**: 机构级量化交易引擎
- **特点**:
  - 支持多资产类别
  - 云端回测和实盘
  - 社区策略库
- **适合**: 专业量化开发

### 13. [freqtrade](https://github.com/freqtrade/freqtrade) ⭐ 25k+
- **语言**: Python
- **简介**: 加密货币量化交易机器人
- **特点**:
  - 完整交易流程
  - 策略优化工具
  - 活跃社区
- **适合**: 加密货币量化（可借鉴策略）

---

## 🇨🇳 A 股/可转债专项

### 14. [bondTrader](https://github.com/freevolunteer/bondTrader)
- **语言**: Python
- **简介**: A 股可转债日内自动 T+0 交易
- **特点**:
  - 实时行情接口
  - 策略触发 + 交易托管
  - 专注可转债套利
- **适合**: A 股可转债量化

### 15. [tqsdk-python](https://github.com/shinnytech/tqsdk-python) ⭐ 4k+
- **语言**: Python
- **简介**: 天勤量化开发包（信易科技）
- **特点**:
  - 期货/期权/股票支持
  - 历史数据 + 实时交易
  - 简洁的 API 设计
- **适合**: 国内期货量化

### 16. [Hikyuu](https://github.com/fasiondog/hikyuu) ⭐ 3k+
- **语言**: C++/Python
- **简介**: 高性能量化交易研究框架
- **特点**:
  - C++ 核心 + Python 绑定
  - 专注 A 股市场
  - 高性能回测引擎
- **适合**: 对性能要求高的量化研究

---

## 📖 中文学习资源

### 17. [WhaleQuant](https://datawhalechina.github.io/whale-quant/)
- **简介**: Datawhale 量化开源课程
- **内容**: 量化金融知识 + Python 实战
- **适合**: 系统化学习量化

### 18. [je-suis-tm/quant-trading](https://github.com/je-suis-tm/quant-trading) ⭐ 2k+
- **简介**: Python 量化交易策略合集
- **内容**: VIX 计算器、模式识别、蒙特卡洛、期权策略等
- **适合**: 策略灵感参考

---

## 📚 学习资源

### 书籍
- 《量化交易：如何建立自己的算法交易业务》- Ernest Chan
- 《主动投资组合管理》- Grinold & Kahn
- 《打开量化投资的黑箱》- Rishi K. Narang

### 在线课程
- [Quantopian Lectures](https://github.com/Quantopian/lectures)
- [WorldQuant University](https://www.worldquantuniversity.org/)
- [Coursera 金融工程与风险管理](https://www.coursera.org/)

### 社区
- [JoinQuant 聚宽](https://www.joinquant.com/) - 中国量化社区
- [RiceQuant 米筐](https://www.ricequant.com/) - 量化研究平台
- [QuantStart](https://www.quantstart.com/) - 量化交易教程

---

## 🚀 快速开始

### 环境搭建
```bash
# 创建虚拟环境
python -m venv venv
source venv/bin/activate  # Linux/Mac
# 或 venv\Scripts\activate  # Windows

# 安装基础包
pip install pandas numpy matplotlib
pip install backtrader talib
pip install akshare yfinance
```

### 简单策略示例
```python
import backtrader as bt

class MovingAverageStrategy(bt.Strategy):
    params = (('period', 20),)
    
    def __init__(self):
        self.ma = bt.indicators.SimpleMovingAverage(
            self.data.close, period=self.params.period
        )
    
    def next(self):
        if self.data.close[0] > self.ma[0]:
            self.buy()
        elif self.data.close[0] < self.ma[0]:
            self.sell()
```

---

## 📝 项目说明

本仓库收集整理量化股票交易相关的开源项目，按类别分类，方便快速查找和学习。

**更新日期**: 2025
**维护者**: OpenClaw Agent

---

## ⚠️ 免责声明

- 本项目仅供学习和研究使用
- 量化交易有风险，投资需谨慎
- 过往业绩不代表未来表现
- 实盘交易前请充分测试和风险评估
