# 🧠 Meta-Llama-3.1-8B-Instruct-Code-Reasoning (Fine-Tuned)

This is a fine-tuned version of **Meta Llama 3.1 8B Instruct**, optimized to explain solutions clearly, walk through the code line by line with examples and result in a clear and beginner-friendly format.

It was trained on curated examples where the model (Check it out here: 👉 [Meta-Llama-3.1-8B-Instruct-Code-Reasoning](https://huggingface.co/Stefenn/Meta-Llama-3.1-8B-Instruct-Code-Reasoning))
- Explains the **approach before jumping in solutions** with strong reasoning.
- Walks through a **sample input** step-by-step like a dry-run.
- Highlights **common mistakes** and provides **corrections**.
- Keeps the explanation clean, concise, and beginner-readable.


## 🖥️ Try It Out Instantly Using LLMs Studio

1. **Download LLMs Studio:**
   - Visit [https://llms.studio](https://llms.studio) and install LLMs studio for your OS (Windows/Mac/Linux).

2. **Install Model on Studio:**
   - Go to Model Search and search `Stefenn/Meta-Llama-3.1-8B-Instruct-Code-Reasoning`

   - Download `unsloth.Q4_K_M.gguf` and load the model to use.

3. **Set This System Prompt Before Chatting:** `You are a helpful and thoughtful AI assistant with strong reasoning abilities. When responding to questions, focus on helping the user understand the problem before jumping to solution. Explain your approach to the solution clearly, using examples where helpful. After giving the correct solution, walk through the code line by line using a concrete sample input. Explain what each line does and how the data changes as it runs. Avoid long-winded explanations. Use a clear and clean format with concise bullet points.`

## 🧰 Technical Info

- Base Model: `meta-llama/Meta-Llama-3.1-8B-Instruct`
- Format: GGUF (`unsloth.Q4_K_M.gguf`)
- Trained with: [Unsloth](https://github.com/unslothai/unsloth)
- Quantization: Q4_K_M (efficient for inference)

---

## 📦 Model Files

You can download or integrate the GGUF model from the Hugging Face repo:

- [Click to View on Hugging Face](https://huggingface.co/Stefenn/Meta-Llama-3.1-8B-Instruct-Code-Reasoning)

---

## 🧠 Ideal Use Cases

- Code tutoring platforms
- LLM teaching agents
- Interactive explainers for junior devs
- Chatbot-style debugging walkthroughs

---

## 🤝 Credits

Finetuned by [@Stefenn](https://github.com/your-username)  
Built with ❤️ using Unsloth + Google Colab  
Special thanks to the [Z1 Paper](https://github.com/Z1Research/Z1) for inspiring clean reasoning formatting.

---

## 🪄 License

This project uses the same license as Meta-Llama 3. Check Hugging Face for model use terms.
