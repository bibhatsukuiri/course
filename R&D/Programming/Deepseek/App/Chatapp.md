
# Chat App - README

## 📌 Minimum Requirements

To run the `.exe` file, ensure your system meets the following requirements:

### 🔧 System Requirements
- Operating System: Windows 10 or later (64-bit)
- Processor: Intel i5 or higher (or equivalent AMD)
- Memory: At least 8GB RAM (Recommended: 16GB for better performance)
- Storage: At least 5GB of free disk space
- Python (Optional for Debugging): Python 3.8+ installed (if running from source)

## 🚀 Prerequisites

Before running the application, install the following:

### 1️⃣ Install Ollama
Ollama is required to load and run the AI models.

Download and install Ollama from the official website:

[Ollama Installation Guide](https://ollama.com)

Alternatively, you can install it using:

```sh
curl -fsSL https://ollama.com/install.sh | sh
```

For Windows users:

```sh
winget install Ollama
```

### 2️⃣ Install AI Models
Once Ollama is installed, download the required AI models using:

```sh
ollama pull deepseek-r1:14b
```

Other available models:

```sh
ollama pull deepseek-r1:1.5b
ollama pull deepseek-r1:32b
ollama pull phi4:latest
ollama pull llama2:7b
```

To verify installed models:

```sh
ollama list
```

## 🎯 Running the Application

Once the prerequisites are installed, simply **double-click the `.exe` file** to launch the Chat App.



## ⚠️ Troubleshooting

### ❌ Error: "Ollama command not found"
Ensure Ollama is installed correctly and restart your terminal.

### ❌ Error: "No models found"
Run `ollama list` to check installed models. If none are listed, install a model using:

```sh
ollama pull deepseek-r1:14b
```

### ❌ Error: "Application not opening"
- Ensure all dependencies are installed
- Try running it as **Administrator**
- Check for missing `.dll` files (Install **Microsoft Visual C++ Redistributable**)

## 🏆 Credits
Developed by **Bibhatsu Kuiri** as part of the Udemy Course: *DeepSeek Mastery*.

For support, contact [bibhatsu@outlook.com].
