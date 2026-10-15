# Related Work

Recent studies have explored the use of large language models (LLMs) and multi-agent systems to support programming tasks such as code generation, code review, and debugging. These approaches use specialized agents and collaborative workflows to improve code quality, identify errors, and refine generated solutions [1]–[5]. The following table summarizes the main contributions, methodologies, and findings of the selected studies.

| Study | Main Idea | Methodology | Results and Limitations |
|---|---|---|---|
| **AdaCoder [1]** | Adaptive multi-agent framework for function-level code generation. | Four agents handle planning, code generation, evaluation, and debugging. The workflow adapts based on whether errors are detected. | Reported a 27.69% improvement in pass@1 over MapCoder, with faster execution and lower token consumption. Generalization to complex programming tasks remains unclear. |
| **From Tool to Partner [2]** | Examines AI agents as programming partners in VR pair programming. | Compares voice-only and embodied GPT-4o agents, including reactive and proactive responses during block-based programming tasks. | Knowledge assessment increased from 50% to 88.9% with the embodied agent, with a similar increase for the voice-only agent. The study was limited by the number of tasks and available agent actions. |
| **AnnCoder [3]** | Multi-agent code generation and optimization through iterative feedback. | Three agents retrieve relevant cases, synthesize code, and diagnose defects in a feedback loop. | Achieved higher pass@1 values in most reported benchmark comparisons. Iterative optimization adds computational overhead, and domain-specific applications remain challenging. |
| **Collaborative Multi-Agent Framework [4]** | Combines autonomous code generation and debugging using multiple agents and external tools. | Four LangGraph-based agents handle architecture, programming, reviewing, and debugging through iterative execution and feedback. | Reported higher pass@k values than a single-LLM agent and other multi-agent baselines. Evaluation focuses on Python, and the framework adds computational overhead. |
| **Multi-Agent LLM Collaboration [5]** | Adaptive code review, debugging, and security analysis with personalized feedback. | Three specialized agents communicate to refine findings, while FAISS-based memory stores previous interactions to reduce repeated suggestions. | Reported reduced processing time compared with independent agent execution and more personalized feedback. Evaluation focuses on Python, with other languages left for future work. |

## Research Gap

The reviewed studies demonstrate the potential of multi-agent collaboration for programming assistance. However, there remains an opportunity to investigate how findings from code review, error detection, testing, and debugging agents can be shared to support one another before producing a final result. This project explores that approach through a multi-agent programming assistant in which specialized agents use one another's findings to identify errors and improve the final code output.

# References

[1] Y. Zhu, C. Liu, X. He, X. Ren, Z. Liu, R. Pan, and H. Zhang, “AdaCoder: An adaptive planning and multi-agent framework for function-level code generation,” *IEEE Transactions on Software Engineering*, 2025, doi: 10.1109/TSE.2025.3642621.

[2] X. Yang, Y. Zhan, N. Matsuda, and Q. Jin, “From tool to partner: Exploring the roles of embodiment on AI agent in pair programming,” in *2025 IEEE Symposium on Visual Languages and Human-Centric Computing (VL/HCC)*, 2025, pp. 234–240, doi: 10.1109/VLHCC65237.2025.00033.

[3] Z. Zhang, J. Wang, Z. Li, Y. Wang, and J. Zheng, “AnnCoder: A multi-agent-based code generation and optimization model,” *Symmetry*, vol. 17, no. 7, p. 1087, 2025, doi: 10.3390/sym17071087.

[4] P. Nazareth, P. Uppoor, Y. Poojary, et al., “Collaborative multi-agent framework for autonomous code generation and debugging,” in *2025 IEEE 9th International Conference on Information and Communication Technology (CICT)*, 2025, pp. 1–6, doi: 10.1109/CICT67193.2025.11399205.

[5] T. Sharanarthi and S. Polineni, “Multi-agent LLM collaboration for adaptive code review, debugging, and security analysis,” in *2025 International Conference on Mechatronics, Robotics, and Artificial Intelligence (MRAI)*, 2025, pp. 541–546, doi: 10.1109/MRAI65197.2025.11135756.
