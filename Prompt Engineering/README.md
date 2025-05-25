# 🤖 Prompt Engineering with Shivaay AI ✨

Prompt engineering is the art of crafting your input messages to get better, more precise, and relevant responses from Shivaay AI.

In this folder, you'll find:

-  Examples showing how to design prompts using **system** and **user** roles.
-  How to control response style by adjusting parameters like **temperature** and **max_tokens**.
-  Ways to write multi-turn conversations for richer interactions.
-  Sample code snippets using both the OpenAI-compatible Python SDK and the raw `requests` library.

---

## 🔍 Understanding Parameters

### 🌡️ `temperature`  
This controls the randomness of the response:
- Lower values like `0.2` make the output more focused and deterministic.
- Higher values like `0.8` or `1.0` make the output more creative or varied.

Use a **low temperature** for factual, concise answers.  
Use a **high temperature** for storytelling, brainstorming, or open-ended tasks.

---

### 🧮 `max_tokens`  
This controls the **length** of the response:
- It sets the **maximum number of tokens (words & symbols)** the AI can return.
- A token roughly corresponds to a word (or part of it).

Use a **small value** for short answers, and a **larger value** if you want detailed explanations.

---

Good prompt engineering unlocks the full potential of Shivaay AI for your use case. 🚀
