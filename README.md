# CS361-Biz-Optimization

Inspired by the Vending-Bench paper (Backlund & Petersson, 2025), this project investigates whether optimization techniques can synergize with LLM agents to stabilize autonomous business decision-making. While LLMs are pretty proficient at short-term reasoning, they often experience meltdowns over long-horizon tasks.

# Framework
- LLM interprets the situation, parses data 
- Quadratic Penalty method to incorporate constraints
- Loss terms include wasted inventory, out of stock frequency, price instability, and bankruptcy risk

# Stack
- likely python for simulation, C++ optimizerss
