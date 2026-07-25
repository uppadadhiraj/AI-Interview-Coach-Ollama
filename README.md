# 🤖 AI Interview Coach using DeepSeek-R1:8B

An AI-powered interview preparation chatbot built using **Python**,
**Streamlit**, **LangChain**, and **Ollama**, powered by the
**DeepSeek-R1:8B** reasoning model.

This application provides an interactive ChatGPT-like interface to help
users prepare for technical interviews by answering interview questions,
explaining programming concepts, solving coding problems, and
maintaining conversation history for context-aware responses.

Unlike cloud-based AI assistants, this project runs **completely
locally**, ensuring privacy without requiring API keys or paid AI
services.

------------------------------------------------------------------------

# 🚀 Features

-   💬 Interactive ChatGPT-style interface
-   🧠 Context-aware conversations with chat history
-   🎯 Multiple response modes:
    -   Interview Answer
    -   Beginner Explanation
    -   Detailed Explanation
    -   Short Answer
-   👨‍💻 Technical interview preparation
-   💡 Coding problem explanations
-   ⚡ Powered by DeepSeek-R1:8B through Ollama
-   🔒 Fully local execution (No API keys required)
-   🎨 Clean and responsive Streamlit interface

------------------------------------------------------------------------

# 🧠 AI Model

This project uses **DeepSeek-R1:8B** running locally through **Ollama**.

### Why DeepSeek-R1?

-   Excellent reasoning capabilities
-   Strong coding and debugging performance
-   Ideal for technical interview preparation
-   Fast local inference
-   Complete privacy
-   No internet connection required after model installation

------------------------------------------------------------------------

# 🛠️ Tech Stack

-   Python
-   Streamlit
-   LangChain
-   LangChain-Ollama
-   Ollama
-   DeepSeek-R1:8B
-   Git
-   GitHub

------------------------------------------------------------------------

# 📂 Project Structure

``` text
AI-Interview-Coach-ollama/
│
├── chatbot.py
├── requirements.txt
├── .gitignore
└── README.md
```

------------------------------------------------------------------------

# ⚙️ Installation

## 1. Clone the Repository

``` bash
git clone https://github.com/uppadadhiraj/AI-Interview-Coach-ollama.git
```

## 2. Navigate to the Project

``` bash
cd AI-Interview-Coach-ollama
```

## 3. Create a Virtual Environment

### Windows

``` bash
python -m venv .venv
.venv\Scripts\activate
```

### Linux / macOS

``` bash
python3 -m venv .venv
source .venv/bin/activate
```

## 4. Install Dependencies

``` bash
pip install -r requirements.txt
```

------------------------------------------------------------------------

# 🤖 Install Ollama

Download and install Ollama from:

https://ollama.com

Pull the DeepSeek-R1:8B model:

``` bash
ollama pull deepseek-r1:8b
```

Verify that the model is installed:

``` bash
ollama list
```

------------------------------------------------------------------------

# ▶️ Run the Application

Start Ollama:

``` bash
ollama serve
```

Run the Streamlit application:

``` bash
streamlit run chatbot.py
```

The application will automatically open in your default web browser.

------------------------------------------------------------------------

# 💡 How It Works

1.  Enter an interview question into the chat.
2.  LangChain formats the prompt and conversation history.
3.  DeepSeek-R1:8B processes the request locally through Ollama.
4.  Streamlit displays the AI-generated response.
5.  Conversation history is maintained throughout the session for
    context-aware interactions.

------------------------------------------------------------------------

# 🔮 Future Improvements

-   Resume Upload
-   PDF-based Interview Preparation
-   Retrieval-Augmented Generation (RAG)
-   Voice Input
-   Export Chat History
-   Multiple AI Model Selection
-   Live Coding Interview Mode
-   Interview Performance Analytics
-   Dark/Light Theme
-   Cloud Deployment

------------------------------------------------------------------------

# 🤝 Contributing

Contributions are welcome!

1.  Fork the repository.
2.  Create a new branch.
3.  Commit your changes.
4.  Push your branch.
5.  Open a Pull Request.

------------------------------------------------------------------------

# 📄 License

This project is licensed under the MIT License.

------------------------------------------------------------------------

# 👨‍💻 Author

**Venkata Dhiraj Reddy Uppada**

GitHub: https://github.com/uppadadhiraj

Repository: https://github.com/uppadadhiraj/AI-Interview-Coach-ollama

------------------------------------------------------------------------

If you found this project useful, consider giving it a ⭐ on GitHub!
