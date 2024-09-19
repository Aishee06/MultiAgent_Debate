# 🧠 Multi-Agent Debate for Improving Factuality and Reasoning in Language Models 🤖

Welcome to the **Multi-Agent Debate for AI** project! In this repository, I explore an innovative approach to improving the factuality and reasoning capabilities of AI agents by engaging them in debates, where they critique and refine each other’s answers. It's like a **math quiz 🧮** where five AI students (agents) debate their solutions to come up with the most accurate response.

## 📜 Paper Summary

This project builds on the concepts introduced in the paper *"Improving Factuality and Reasoning in Language Models through Multiagent Debate"*:

### **In a Nutshell:**
- 🧑‍🏫 **Multiple AI Agents Debate:** Several AI agents participate in structured debates.
- 🤓 **Collaborative Reasoning:** Agents critique, refine, and defend their answers, much like a group discussion.
- ✅ **Better Accuracy:** The collective reasoning helps catch mistakes and refine responses, leading to more accurate and reliable answers.

📚 **Takeaways:**
- Just like teamwork makes complex problems easier for humans, multiple AI agents debating with each other leads to superior results.
- These debates help improve accuracy and reduce biases by leveraging multiple perspectives.
- Perfect for fields like **healthcare**, **legal research**, and **scientific analysis** where accuracy is crucial.

---

## 💻 My Project Setup: A Creative Take on AI Debates 🎨

### **Objective:**
I designed a math quiz 🧮 experiment where five AI agents answer questions and engage in debates. Each round brings new critiques and solutions until a winner is declared based on accuracy. The goal? To demonstrate how AI agents improve through peer learning and collaboration.

### **Technical Setup:**
- **Model:** [WizardMath-7B-v1.1](https://huggingface.co/WizardLM/WizardMath-7B-V1.1) from Hugging Face, fine-tuned for math reasoning.
- **Quantization:** To make it resource-efficient, I used 4-bit quantization via `BitsAndBytesConfig`, optimizing the model to run smoothly even on smaller GPUs.
- **Dataset:** I used the **GSM8K** dataset, a collection of math word problems, shuffled to randomly select questions for each round.

## 📊 Visualizing the Debate

Here are some of the key visualizations from the experiment:

- **Final Rankings** 🥇
- **Performance Over Rounds:** Watch how each agent's performance fluctuated in the graph below, showing their journey through five rounds of debate.
- **Agent Performance in Each Round:** Check out the histogram that compares how each agent scored in individual rounds, showcasing the variance in their responses.

## 🎉 Conclusion

This project is a fun and creative exploration of AI learning through debate! The idea of multiple agents "arguing" over math problems and improving their answers feels like a glimpse into the future of AI collaboration. Hope you enjoy the project as much as I did building it!
