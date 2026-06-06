# ⚛️ AI Quantum

AI量子计算工具，支持量子算法、量子编程、量子应用。

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-blue?logo=python" />
  <img src="https://img.shields.io/badge/OpenAI-API-green?logo=openai" />
  <img src="https://img.shields.io/badge/License-MIT-yellow" />
</p>

## ✨ 特性

- 📖 量子概念解释
- 🔬 Qiskit电路生成
- 🧮 量子算法设计
- 💡 量子应用建议
- 🤖 量子机器学习
- ⚖️ 经典/量子比较

## 🚀 快速开始

```bash
pip install openai

python tools.py
```

## 📖 使用

```python
from ai_quantum import create_tools

tools = create_tools()

# 概念解释
concept = tools.explain_quantum_concept("量子纠缠", "beginner")

# Qiskit电路
circuit = tools.generate_qiskit_circuit("Grover搜索", 4)

# 量子算法
algorithm = tools.design_quantum_algorithm("大数分解")

# 量子应用
applications = tools.suggest_quantum_application("金融")

# 量子ML
qml = tools.generate_quantum_ml("分类任务", "pennylane")

# 经典/量子比较
comparison = tools.compare_classical_quantum("优化问题")
```

## 📁 项目结构

```
ai-quantum/
├── tools.py       # 量子计算工具核心
└── README.md
```

## 📄 许可证

MIT License
