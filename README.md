# 🧠 Fine-Tuned Llama-3.1-8B-Instruct for Code Reasoning

This is a fine-tuned version of **Meta Llama 3.1 8B Instruct**, optimized to explain solutions clearly, walk through the code line by line with examples and result in a clear and beginner-friendly format.

It was trained on curated examples where the model:
- Explains the **approach before jumping in solutions** with strong reasoning.
- Walks through a **sample input** step-by-step like a dry-run.
- Highlights **common mistakes** and provides **corrections**.
- Keeps the explanation clean, concise, and beginner-readable.


## 🖥️ Try It Out Instantly Using LLMs Studio

1. **Download LLMs Studio:**
   - Visit [https://llms.studio](https://llms.studio) and install LLMs studio for your OS (Windows/Mac/Linux).

2. **Install Model on Studio:**
   - Go to Model Search and search `Stefenn/Meta-Llama-3.1-8B-Instruct-Code-Reasoning`
   <img width="849" alt="Screenshot 2025-04-16 at 9 14 17 PM" src="https://github.com/user-attachments/assets/61800956-13df-494a-9eb9-d68a76151015" />
   
   - Download `unsloth.Q4_K_M.gguf` and load the model to use.

3. **Set This System Prompt Before Chatting:** `You are a helpful and thoughtful AI assistant with strong reasoning abilities. When responding to questions, focus on helping the user understand the problem before jumping to solution. Explain your approach to the solution clearly, using examples where helpful. After giving the correct solution, walk through the code line by line using a concrete sample input. Explain what each line does and how the data changes as it runs. Avoid long-winded explanations. Use a clear and clean format with concise bullet points.`
  
   <img width="276" alt="Screenshot 2025-04-16 at 9 14 36 PM" src="https://github.com/user-attachments/assets/adc6c6cb-b6d5-4887-95d8-57d8629eabc3" />


## 🧰 Technical Info

- Base Model: `meta-llama/Meta-Llama-3.1-8B-Instruct`
- Format: GGUF (`unsloth.Q4_K_M.gguf`)
- Trained with: [Unsloth](https://github.com/unslothai/unsloth)
- Quantization: Q4_K_M (efficient for inference)

## 📦 Model Files

👉[Click to View on Hugging Face](https://huggingface.co/Stefenn/Meta-Llama-3.1-8B-Instruct-Code-Reasoning)

## 🤝 Credits

Finetuned by [@Stefen](https://github.com/StephenNg25/)  
Built with ❤️ using Unsloth + Google Colab  
Special thanks to [Z1](https://huggingface.co/datasets/efficientscaling/Z1-Code-Reasoning-107K) for a clean and detailed dataset.

## 🪄 License

This project uses the same license as Meta-Llama 3. Check Hugging Face for model use terms.
