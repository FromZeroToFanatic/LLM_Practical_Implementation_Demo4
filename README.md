# 大模型应用实战（基于 LangChain 搭建 LLMs 应用）

## 学习资料

### 【原理】LangChain 工具学习
- 【课程视频】[B站视频](https://www.bilibili.com/video/BV1BgfBYoEpQ)  
- 【LangChain 实战】[GitHub: DeepLearning/llms](https://github.com/QunBB/DeepLearning/tree/main/llms)  
- 【VectorDB 原理】[向量数据库原理](https://guangzhengli.com/blog/zh/vector-database/?continueFlag=0ab5f417fc4f5e7f838819b4dc745acf)  

---

### 【手撕】RAG 从基础到进阶
- 【学习视频】[YouTube 播放列表](https://www.youtube.com/playlist?list=PLfaIDFEXuae2LXbO1_PKyVJiQ23ZztA0x)  
- 【国内 B站】[B站视频](https://www.bilibili.com/video/BV1pZ421g7iv)  
- 【配套代码】[rag-from-scratch](https://github.com/langchain-ai/rag-from-scratch)  
- 【RAG 进阶】[Advanced RAG](https://github.com/NisaarAgharia/Advanced_RAG)  

---

### 【实战】MCP 实战
- 【MCP 基础】[B站视频](https://www.bilibili.com/video/BV1AnQNYxEsy)  
- 【Function Calling 用法】[阿里云文档](https://help.aliyun.com/zh/model-studio/qwen-function-calling)  
- 【MCP 实战代码】[mcp-client-for-weather-example](https://github.com/a-persimmons/mcp-client-for-weather-example)  

---

### 【实战】从 0 到 1 手撕 Agent
- 【基本理念】[B站视频](https://www.bilibili.com/video/BV1FCR3Y1EnJ)  
- 【Agent 入门】[B站视频](https://www.bilibili.com/video/BV1QF4m177Rx)  
- 【动手写 Agent】[GitHub: wow-agent](https://github.com/datawhalechina/wow-agent/tree/main/notebooks)  
- 【复杂案例实战】[awesome-llm-apps/advanced_ai_agents](https://github.com/Shubhamsaboo/awesome-llm-apps/tree/main/advanced_ai_agents)  

---

## 实战

选择任意一个熟悉的 Agent 框架（如 **LangChain**、**LangGraph**、**MetaGPT**、**Agently** 等）完成一个数据探索任务。  
输入数据为 **一个包含 800 多行的 CSV 表格**。  

任务目标是通过 **自然对话的形式** 完成数据分析与探索，不能手写代码，所有功能均需通过 **大模型驱动的 Agent** 来实现。  

---

### 要求

1. **数据 Summary**
   - 统计数据的均值、方差、最大值、最小值等基本指标。

2. **缺失值处理**
   - 对缺失值 `NULL` 进行填充，使用 **均值填充**。

3. **可视化**
   - 绘制图表，例如对 `Survived` 列的分布进行统计并画图。

4. **建模与预测**
   - 使用 **sklearn** 作为工具，训练模型并完成预测。

---

### 注意事项
- 以上功能 **必须全部通过大模型完成**，不可手写代码实现。  
- 每个功能都需要通过一次 **Agent 对话交互** 来实现。  
- 模型不限（如 **GPT-4** 或 **DeepSeek** 均可）。  

---
