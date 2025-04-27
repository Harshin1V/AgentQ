# AgentQ
## Building AI Browser Agents with Agent Q and MCTS Planning

**Description:**  
Designed and implemented autonomous AI browser agents capable of web navigation and task automation. Integrated **Agent Q** architecture combining **LLMs**, **Monte Carlo Tree Search (MCTS)**, and **self-critique mechanisms** to enhance decision-making and action planning in dynamic web environments. Trained and fine-tuned agents using **off-policy Direct Preference Optimization (DPO)** to improve reliability and success rates across complex, multi-step web tasks.

**Key Contributions:**
- Developed simple and autonomous web agents using LLM-based action generation and observation-based feedback loops.
- Integrated **MCTS** search guided by LLM evaluations to optimize multi-step task planning.
- Implemented **self-critique** modules enabling agents to prune low-quality action branches during search.
- Fine-tuned agents using **DPO** on preference pairs generated from agent feedback and MCTS scoring.
- Conducted extensive agent evaluation and monitoring to improve web task success rates iteratively.
- Explored future directions for browser agents, emphasizing **iterative learning**, **task generalization**, and **low-shot agent refinement**.

**Tech Stack:**
- Python, OpenAI GPT APIs, AutoGen v2
- Monte Carlo Tree Search (MCTS)
- DPO Fine-tuning techniques
- Research Reference: Agent Q – *Advanced Reasoning and Learning for Autonomous AI Agents* (arXiv:2408.07199)
