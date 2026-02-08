# Gen-AI-based-Medical-Assistant-Chatbot

In this project, I built a lightweight medical chatbot using a local LLM (Ollama) combined with real-time web retrieval and conversational memory. The goal was to explore how context impacts user experience in healthcare-style conversations.

I first implemented a **no-memory version**, where each user question is treated independently. This quickly showed its limitations — follow-up questions lost context and resulted in generic or disconnected responses.

I then added a simple **conversation memory layer**, allowing the assistant to retain prior interactions. With memory enabled, the system was able to understand follow-up questions (like rest duration after an ankle sprain) and provide coherent, context-aware guidance. This small change made the interaction feel much more natural and realistic.

Through this project, I gained hands-on experience with:

- Local LLM deployment using Ollama  
- Retrieval-augmented generation (RAG) with DuckDuckGo search  
- Prompt engineering for domain-specific responses  
- Designing conversational memory from scratch  
- Comparing stateless vs stateful AI behavior  
- Debugging real-world GenAI pipelines  

Overall, this work helped me better understand how modern language systems combine retrieval, reasoning, and memory to support user-centered applications. It also reinforced the importance of context persistence when building practical conversational AI — especially in sensitive domains like healthcare.

This project reflects my broader interest in applied machine learning and language technologies, and I’m excited to continue building systems that are not just intelligent, but genuinely helpful and human-centered.
