# Log-Analysis-using-GenAI

Developed an AI system that uses Generative AI to detect anomalies, extract insights, and summarize log data. Implemented data preprocessing, log parsing, and AI-driven pattern recognition to enhance monitoring and troubleshooting efficiency. Utilized technologies like Python, NLP, LLM (LLaMA), ChromaDb, Streamlit, LangChain(Framework) for scalable log processing.

**Key Features:**

* **Chat:** Ask questions and get answers directly from your documents.
* **Local LLM Support:** Leverage the capabilities of local LLMs for offline document interaction.
* **ChromaDB Support:** Store and manage document metadata efficiently with ChromaDB.
* **LangChain Integration:** Streamline information extraction from documents through LangChain.

## Installation

**Prerequisites:**

* Python >=3.9 (https://www.python.org/downloads/)
* pip (usually comes pre-installed with Python)
* Ollama (https://ollama.com/)

**Installation Steps:**

1. **Clone the repository:**

   ```
   git clone https://github.com/gagangupta12/Log-Analysis-using-GenAI
   ```
2. **Navigate to the project directory:**

   ```
   cd Log-Analysis-using-GenAI
   ```

3. Open project directory in VSCode

   ```
   code .
   ```
or any other code editor

4. Install dependencies from requirements.txt
   ```
   pip install -r requirements.txt
   ```

5. Pull the required models from Ollama
   
   - Download & install [Ollama](https://ollama.com/) if not installed
   - Open terminal & run these command to pull the required models into local machine
     
     For `llama3`
     ```
     ollama pull llama3:latest
     ```    
     For `nomic-embed-text`
     ```
     ollama pull nomic-embed-text:latest
     ``` 
   - Insure both models are downloaded
     ```
     ollama ls
     ```