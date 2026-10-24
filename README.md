# 模拟电子技术学习笔记

一套使用 [Obsidian](https://obsidian.md/) 整理的模拟电子技术学习笔记，内容从电路抽象与电阻网络出发，逐步覆盖网络定理、非线性元件、暂态分析、正弦稳态、双口网络、频率响应与滤波器，并已进入半导体基础知识。

> 本仓库仍在持续整理中，公式、例题与章节结构会随学习进度更新。

## 内容目录

| 章节 | 主要内容 |
| --- | --- |
| [1. 电路抽象](SimulatedElectronic/1.%E7%94%B5%E8%B7%AF%E6%8A%BD%E8%B1%A1.md) | 集总电路抽象、参考方向、KCL、KVL 与基本元件关系 |
| [2. 电阻网络](SimulatedElectronic/2.%E7%94%B5%E9%98%BB%E7%BD%91%E7%BB%9C.md) | 网络拓扑、串并联、分压分流与电路方程 |
| [3. 网络定理](SimulatedElectronic/3.%E7%BD%91%E7%BB%9C%E5%AE%9A%E7%90%86.md) | 节点电压法、回路电流法、叠加、戴维南与诺顿等效 |
| [4. 非线性元件](SimulatedElectronic/4.Non-Linear%20components.md) | 非线性方程、图形分析、分段线性与小信号分析 |
| [5. 储能元件](SimulatedElectronic/5.%E5%82%A8%E8%83%BD%E5%85%83%E4%BB%B6.md) | 电容、电感、寄生参数、变压器与典型激励 |
| [6. 一阶暂态](SimulatedElectronic/6.%2A%2A%E4%B8%80%E9%98%B6%E6%9A%82%E6%80%81%2A%2A.md) | RC/RL 电路、一阶微分方程、自然响应与受迫响应 |
| [7. 二阶暂态](SimulatedElectronic/7.%2A%2A%E4%BA%8C%E9%98%B6%E6%9A%82%E6%80%81%2A%2A.md) | RLC 电路与二阶系统响应（持续补充中） |
| [8. 正弦稳态](SimulatedElectronic/8.%E6%AD%A3%E5%BC%A6%E7%A8%B3%E6%80%81.md) | 正弦量、相量法、阻抗/导纳与交流稳态电路分析 |
| [8.2 频率响应和滤波器](SimulatedElectronic/8.2%20%E9%A2%91%E7%8E%87%E5%93%8D%E5%BA%94%E5%92%8C%E6%BB%A4%E6%B3%A2%E5%99%A8.md) | 频率响应、波特图与滤波器基础 |
| [9. 双口网络](SimulatedElectronic/9.%E5%8F%8C%E5%8F%A3%E7%BD%91%E7%BB%9C.md) | 双口网络的参数表示与基本分析方法 |
| [10.1 半导体基础知识](SimulatedElectronic/10.1%20%E5%8D%8A%E5%AF%BC%E4%BD%93%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86%20Semiconductor%20Fundamentals.md) | 载流子、本征与杂质半导体、PN 结、二极管、BJT 与 FET/MOSFET |

## 使用方法

建议将仓库克隆到本地后，直接把 `SimulatedElectronic` 目录作为 Obsidian 仓库（Vault）打开：

```bash
git clone https://github.com/sinuosun/SimulatedElectronicTechnology.git
```

随后在 Obsidian 中选择“打开本地仓库”，并定位到：

```text
SimulatedElectronicTechnology/SimulatedElectronic
```

笔记中的配图使用 Obsidian 的 `![[图片名称.png]]` 内部嵌入语法，因此在 Obsidian 中阅读可以获得完整效果；GitHub 页面可能不会直接渲染这些图片。

## 仓库结构

```text
.
├── README.md
└── SimulatedElectronic/
    ├── .obsidian/       # 可共享的 Obsidian 配置
    ├── 1.电路抽象.md
    ├── ...
    ├── 7.**二阶暂态**.md
    ├── 8.正弦稳态.md
    ├── 8.2 频率响应和滤波器.md
    ├── 9.双口网络.md
    ├── 10.1 半导体基础知识 Semiconductor Fundamentals.md
    └── *.png            # 笔记配图
```

## 说明

- 笔记以中文为主，保留必要的英文术语与数学表达。
- 内容用于个人学习、复习与交流，如发现错误，欢迎通过 Issue 或 Pull Request 指出。
- 仓库中的公式采用 Markdown/LaTeX 语法编写，建议使用支持数学公式的 Markdown 阅读器。

## License

目前仓库暂未附加开源许可证；未经许可，请勿将内容用于商业用途。
