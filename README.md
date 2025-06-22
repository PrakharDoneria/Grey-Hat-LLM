# ⚫️ Grey Hat LLM: Real-Time Cybersecurity Assistant using WhiteRabbitNeo

**Grey Hat LLM** is a real-time large language model assistant built for ethical cybersecurity research, red team simulation, and penetration testing education. It runs on the [WhiteRabbitNeo-V3-7B](https://huggingface.co/WhiteRabbitNeo/WhiteRabbitNeo-V3-7B) model and executes directly in Google Colab with no setup — featuring fast token-by-token streaming for interactive workflows.

> ⚠️ **Strictly for white-hat and educational use. Do not use for unauthorized activities.**

---

## 🚀 Features

- ✅ **No setup**: Just run in Google Colab
- ⚡ **Live streaming output**: See LLM responses as they generate
- 🧠 Focused on cybersecurity: vulnerability analysis, CTF-style questions, red/blue team tactics
- 🔓 **Uncensored** for unrestricted white-hat scenarios
- 🧰 Built with Hugging Face Transformers (FP16 / GPU ready)

---


### 📦 Requirements (Handled Automatically in Colab)

```bash
transformers
accelerate
torch
````

---

### 🧠 Sample Prompt

```python
test_prompt = "How can a penetration tester detect vulnerable open ports on a Linux server?"
```

### 📤 Real-Time Output

```python
Response:
Nmap is a widely-used tool for identifying open ports...
```

---

## 🔐 Disclaimer

This project is intended for **cybersecurity professionals, educators, and students** to simulate real-world attack scenarios and defenses in a safe, responsible environment.

By using this tool, you agree to:

* Use it **only for legal, ethical, and educational purposes**
* **Not use it for unauthorized system access**
* **Take full responsibility** for your usage

---

## 👨‍💻 Author

Developed by Prakhar Doneria
Inspired by WhiteRabbitNeo, Hugging Face, and the cybersecurity community.
