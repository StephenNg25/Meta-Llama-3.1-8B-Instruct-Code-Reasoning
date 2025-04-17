# 🧠 Meta-Llama-3.1-8B-Instruct-Code-Reasoning (Fine-Tuned)

This is a fine-tuned version of **Meta Llama 3.1 8B Instruct**, optimized to explain solutions clearly, walk through the code line by line with examples and result in a clear and beginner-friendly format.

It was trained on curated examples where the model:
- Explains the **approach before jumping in solutions** with strong reasoning.
- Walks through a **sample input** step-by-step like a dry-run.
- Highlights **common mistakes** and provides **corrections**.
- Keeps the explanation clean, concise, and beginner-readable.


## 🖥️ Try It Out Instantly Using LLMs Studio

1. **Download LLMs Studio:**
   - Visit [https://llms.studio](https://llms.studio) and install LLMs studio for your OS (Windows/Mac/Linux).

2. **Download the Model from Hugging Face:**
   - Go to the model repo:  
     👉 [Meta-Llama-3.1-8B-Instruct-Code-Reasoning](https://huggingface.co/Stefenn/Meta-Llama-3.1-8B-Instruct-Code-Reasoning)
   - Download the file: `unsloth.Q4_K_M.gguf`
   - Place the `.gguf` file in your local models folder (LLMs Studio will guide you if unsure)

3. **Load the Model in LLMs Studio:**
   - Click **“Load Model from File”**
   - Select the `.gguf` model you downloaded

4. **Set This System Prompt Before Chatting:**

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
