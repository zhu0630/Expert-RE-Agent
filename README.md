# Expert-RE-Agent: Autonomous Reverse Engineering System

An advanced, single-agent autonomous system designed for expert-level reverse engineering tasks. This system leverages Long-chain Reasoning, Model Context Protocol (MCP), and Long-term Memory (LTM) to simulate human-like expertise in vulnerability analysis.

## 🚀 Architecture Highlights
- **Singular Expert Agent**: Unified architecture without the overhead of multi-agent communication, reducing latency and token consumption.
- **Long-chain Reasoning**: Capable of step-by-step logic deduction for obfuscated code.
- **MCP Integration**: Native interface to standard security tools (Ghidra, IDA Pro, Radare2).

## 🛠️ Usage
```bash
pip install -r requirements.txt
python main.py --target "sample_malware.bin" --mode "deep-analysis"
