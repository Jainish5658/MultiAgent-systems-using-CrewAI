### 📜 **README.md**

### **Multi-AI Agent Systems with CrewAI**

This repository contains the Jupyter notebooks for the `deeplearning.ai` short course, "Multi-AI Agent Systems with CrewAI." Follow the instructions below to get the notebooks running locally.

-----

### **1. Clone the Repository**

First, you need to clone this GitHub repository to your local machine. Open your terminal or command prompt and run the following command:

```
git clone https://github.com/ksm26/Multi-AI-Agent-Systems-with-crewAI.git
cd Multi-AI-Agent-Systems-with-crewAI
```

-----

### **2. Set up Your Environment**

You will need Python 3.10 or later installed. It is highly recommended to use a virtual environment to manage dependencies.

1.  **Create and activate a virtual environment:**

    ```
    python -m venv venv
    # On macOS/Linux:
    source venv/bin/activate
    # On Windows:
    venv\Scripts\activate
    ```

2.  **Install the required libraries:**

    ```
    pip install -r requirements.txt
    ```

-----

### **3. Configure API Keys**

To use the notebooks, you will need to set up your API keys for the language model and the search tool. The course examples use `OpenAI` and `Serper` for web search.

1.  Create a file named `.env` in the root directory of the cloned repository.

2.  Add your API keys to the `.env` file in the following format:

    ```
    OPENAI_API_KEY="your_openai_api_key_here"
    SERPER_API_KEY="your_serper_api_key_here"
    ```

-----

### **4. Run the Jupyter Notebooks**

Once your environment is set up and your API keys are configured, you can launch Jupyter Notebook to run the files.

1.  **Launch Jupyter Notebook from the terminal:**

    ```
    jupyter notebook
    ```

    This command will open a browser window displaying the contents of the directory.

2.  **Navigate and run the notebooks:**
    Click on the `notebooks` folder, and then select the notebook file you wish to open (e.g., `01_research_and_write_article.ipynb`). You can now run the cells and complete the exercises from the course.
