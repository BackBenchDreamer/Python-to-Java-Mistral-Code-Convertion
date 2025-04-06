<h1 align="center" id="title">Python to Java Code Translator using Mistral API</h1>

<p align="center"><img src="https://socialify.git.ci/BackBenchDreamer/Python-to-Java-Mistral-Code-Convertion/image?font=Raleway&amp;language=1&amp;name=1&amp;owner=1&amp;pattern=Circuit+Board&amp;theme=Light" alt="project-image"></p>

## 📌 Overview
This project translates Python code to Java using the **Mistral API**, all inside a **Google Colab notebook**. It securely loads your API key from **Google Drive** and sends Python code to be translated using a simple function call.

---

## ✅ Prerequisites
- A Google account with access to **Google Drive**
- **Google Colab** (runs in your browser, no setup required)
- A valid **Mistral API key**

---

## 📁 Folder Setup (for Secure API Key Storage)

1. Open your Google Drive
2. Create a folder named `Secrets`
3. Inside the `Secrets` folder, create a file called `mistral.key`
4. Paste your **Mistral API key** into the file (no extra spaces or newlines)
5. Save the file

---

## 🚀 How to Use

1. **Open the Colab notebook**
2. Run the first cell to install requirements and mount your Google Drive
3. Authorize Colab when prompted
4. The notebook will automatically load the API key from your `mistral.key` file
5. Replace the default Python code with your own (inside triple quotes)
6. The `translate_python_to_java()` function sends your code to the API
7. The translated **Java** code will be printed below

---

## ⚙️ Customization Options

- Replace the Python code string with your own
- Modify model parameters like:
  - `temperature`
  - `max_tokens`
  - `model` version (`codestral-latest` by default)
- Save the translated output as a `.java` file (optional)

---

## 🛠️ Troubleshooting

- 🔑 **API Key Errors**: Make sure the file path and contents of `mistral.key` are correct
- 🌐 **HTTP Errors**: Ensure your API access is valid and not rate-limited
- 💾 **Drive Mount Issues**: Try “Restart Runtime” and rerun the mount cell

---

## 🔒 Security Tip

> **Never commit or share your API key.**
> Always keep the `mistral.key` file private in your Google Drive.

---

## 🙌 Credits

This project was created to help developers easily use the Mistral Code API in an interactive and secure environment like Google Colab.

---

## 📬 Support

If you face any issues or need help, feel free to open an issue on this repository.
