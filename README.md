<div align="center">

# Awesome Agentic Time Series

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Last Commit](https://img.shields.io/github/last-commit/ustc-time-series/Awesome-Agentic-Time-Series?color=green)](https://github.com/ustc-time-series/Awesome-Agentic-Time-Series)
[![Stars](https://img.shields.io/github/stars/ustc-time-series/Awesome-Agentic-Time-Series?color=yellow)](https://github.com/ustc-time-series/Awesome-Agentic-Time-Series/stargazers)
[![Forks](https://img.shields.io/github/forks/ustc-time-series/Awesome-Agentic-Time-Series?color=lightblue)](https://github.com/ustc-time-series/Awesome-Agentic-Time-Series/network)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)](https://github.com/ustc-time-series/Awesome-Agentic-Time-Series/pulls)

*A curated collection of papers on Agentic Time Series.*

[Motivation](#-motivation) | [Scientific Question](#-scientific-question) | [Related Work](#-related-work) | [Citation](#-citation)

</div>

---

## 💡 Motivation

Current time series analysis paradigms face fundamental limitations:

<table>
  <tr>
    <th width="50%">❌ Traditional Paradigm</th>
    <th width="50%">✅ Agentic Paradigm</th>
  </tr>
  <tr>
    <td>
      <b>Fixed, Single-step, Single-direction, Limited</b><br/><br/>
      Static and one-shot — once trained, the model produces predictions in a single forward pass without any ability to revisit, refine, or adapt its reasoning process.
    </td>
    <td>
      <b>Adaptive, Interactive, Closed-loop, Cyclic</b><br/><br/>
      Iterative perception, planning, action, reflection, and memory accumulation — enabling closed-loop and self-adaptive time series analysis.
    </td>
  </tr>
</table>

## 🔬 Scientific Question

> We formulate time series analysis as a **sequential decision optimization and path search** problem — moving beyond static model-centric prediction toward multi-step reasoning, tool-augmented decision-making, and experience-driven evolution.

---

## 📚 Related Work

### Position

|  | Paper | Highlight | Links |
|:---:|-------|-----------|:-----:|
| 1 | Mingyue Cheng, Xiaoyu Tao, Qi Liu, Ze Guo, Enhong Chen. <br/> **Position: Beyond Model-Centric Prediction — Agentic Time Series Forecasting** | 率先探索 Agentic Time Series Forecasting 范式的立场 paper。 | [![arXiv](https://img.shields.io/badge/arXiv-2602.01776-b31b1b.svg)](https://arxiv.org/pdf/2602.01776) |

### Time Series Forecasting

|  | Paper | Highlight | Links |
|:---:|-------|-----------|:-----:|
| 2 | Xiaohan Zhang, Tian Gao, Mingyue Cheng\*, Bokai Pan, Ze Guo, Yaguo Liu, Xiaoyu Tao. <br/> **AlphaCast: A Human Wisdom-LLM Intelligence Co-Reasoning Framework for Interactive Time Series Forecasting** | 率先探索人机协同交互式时间序列预测范式。 | [![arXiv](https://img.shields.io/badge/arXiv-2511.08947-b31b1b.svg)](https://arxiv.org/pdf/2511.08947) <br/> [![GitHub](https://img.shields.io/badge/Code-GitHub-blue.svg)](https://github.com/SkyeGT/AlphaCast_Official) |
| 3 | Xiaoyu Tao, Mingyue Cheng, Chuang Jiang, Tian Gao, Huanjian Zhang, Yaguo Liu. <br/> **Cast-R1: Learning Tool-Augmented Sequential Decision Policies for Time Series Forecasting** | 首个基于多轮强化学习训练的时间序列预测智能体。 | [![arXiv](https://img.shields.io/badge/arXiv-2602.13802-b31b1b.svg)](https://arxiv.org/pdf/2602.13802) <br/> [![GitHub](https://img.shields.io/badge/Code-GitHub-blue.svg)](https://github.com/Xiaoyu-Tao/Cast-R1-TS) |
| 4 | Xiaoyu Tao, Mingyue Cheng\*, Ze Guo, Shuo Yu, Yaguo Liu, Qi Liu, Shijin Wang. <br/> **MemCast: Memory-Driven Time Series Forecasting with Experience-Conditioned Reasoning** | 率先探索基于经验积累与持续进化的时间序列预测范式。 | [![arXiv](https://img.shields.io/badge/arXiv-2602.03164-b31b1b.svg)](https://arxiv.org/pdf/2602.03164) <br/> [![GitHub](https://img.shields.io/badge/Code-GitHub-blue.svg)](https://github.com/Xiaoyu-Tao/MemCast-TS) |

### Time Series Anomaly Detection

|  | Paper | Highlight | Links |
|:---:|-------|-----------|:-----:|
| 5 | Xiaoyu Tao, Yuchong Wu, Mingyue Cheng, Ze Guo, Tian Gao. <br/> **AnomaMind: Agentic Time Series Anomaly Detection with Tool-Augmented Reasoning** | — | [![arXiv](https://img.shields.io/badge/arXiv-2602.13807-b31b1b.svg)](https://arxiv.org/pdf/2602.13807) <br/> [![GitHub](https://img.shields.io/badge/Code-GitHub-blue.svg)](https://github.com/Xiaoyu-Tao/AnomaMind-TS) |

---

## 📖 Citation

If you find this collection helpful, please consider citing our position paper:

```bibtex
@article{cheng2026atsf,
  title   = {Position: Beyond Model-Centric Prediction -- Agentic Time Series Forecasting},
  author  = {Cheng, Mingyue and Tao, Xiaoyu and Liu, Qi and Guo, Ze and Chen, Enhong},
  journal = {arXiv preprint arXiv:2602.01776},
  year    = {2026}
}
```

---

<div align="center">

**If you notice missing papers or incorrect metadata, feel free to open an [issue](https://github.com/ustc-time-series/Awesome-Agentic-Time-Series/issues) or submit a [PR](https://github.com/ustc-time-series/Awesome-Agentic-Time-Series/pulls).**

</div>
