```markdown
# Chat App

A modern, Windows-based GUI application for interacting with the Ollama CLI to generate responses using various AI models. Built as part of a Udemy course project by Bibhatsu Kuiri.

## Features
- Select from a list of Ollama models or fetch available models dynamically.
- Enter prompts and generate responses with a sleek loading animation.
- Custom app icon and a professional Windows-like interface.
- No console window for a clean user experience.

## Prerequisites
To run `Chat App` on your Windows PC, you need:
1. **Ollama CLI Installed**:
   - Download and install Ollama from [ollama.ai](https://ollama.ai/).
   - Ensure `ollama` is added to your system PATH:
     - During installation, check the option to add Ollama to PATH, or manually add the installation directory (e.g., `C:\Program Files\Ollama`) to your Environment Variables.

2. **Ollama Models**:
   - Download at least one model supported by the app. Open a command prompt and run:
ollama pull deepseek-r1:1.5b
ollama pull deepseek-r1:14b
ollama pull deepseek-r1:32b
ollama pull phi4:latest
ollama pull llama2:7b

- Alternatively, use the "List Models" button in the app to see available models after installing others with `ollama pull <model_name>`.

3. **Windows Operating System**:
- This executable is designed for Windows. It won’t work on macOS or Linux.

## Installation
1. **Download the App**:
- Obtain `appbk2.exe` from the provided source (e.g., a shared link or repository).

2. **Run the Executable**:
- Double-click `appbk2.exe` to launch the app. No additional installation is required.

## Usage
1. **Launch the App**:
- Run `appbk2.exe`. The GUI will appear with a Windows-like interface.

2. **Select a Model**:
- Use the dropdown to choose a model or click "List Models" to fetch available models from Ollama.

3. **Enter a Prompt**:
- Type your prompt in the text box labeled "Enter your prompt:".

4. **Generate Response**:
- Click "Generate Response" to process your prompt. A loading animation will appear while the response is generated.

5. **View Output**:
- The response will appear in the "Response" text area.

6. **Exit**:
- Click "Exit" or use the "File > Exit" menu to close the app.

## Troubleshooting
- **"Error running Ollama" Message**:
- Ensure Ollama is installed and in your system PATH. Test by opening a command prompt and typing `ollama --version`. If it fails, reinstall Ollama and add it to PATH.
- **No Models Found**:
- Run `ollama pull <model_name>` for each model you want to use (e.g., `ollama pull llama2:7b`).
- **App Doesn’t Start**:
- Ensure you’re on a Windows system. Contact the developer if issues persist.

### Instructions
1. **Copy the Text**:
   - Select and copy everything inside the code block above, including the ```markdown opening and closing lines.

2. **Create the File**:
   - Open a text editor (e.g., Notepad, VS Code).
   - Paste the copied text.
   - Save it as `README.md` (ensure the extension is `.md`, not `.txt`).

3. **Verify**:
   - Open `README.md` in a Markdown viewer (e.g., VS Code with a Markdown plugin, or GitHub) to ensure it renders correctly.

This ensures you get the exact raw Markdown text, avoiding any rendered formatting issues. Let me know if you need further assistance!
## About
- **Developer**: Bibhatsu Kuiri
- **Project**: Udemy Course Project
- **Version**: 1.0
- **Contact**: [Insert your contact info if desired]

## Notes
- No Python installation is required as all dependencies are included.

Enjoy using Chat App!
