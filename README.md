# Foundry IQ - Agentic retrieval solution

An intelligent, MCP-enabled solution that integrates Azure AI Search with Foundry Agent Service for agentic retrieval

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## 📋Blog post
You can read my blog post [where I am walking through the end-to-end solution](https://360agileweb.dev/2026/01/20/foundry-iq-agentic-retrieval-solution-part-1/)

## 🛠️ Creating and Using a Virtual Environment
We'll use `venv`, the tool that comes built-in with Python.

- Step 1: Create the Environment: Navigate in your terminal to the folder where you want your project to live. Then, run the following command to create a new folder that will contain your private Python setup. We'll call it `ai-env`.
`python3 -m venv ai-env` You will see a new folder named ai-env appear.

- Step 2: Activate the Environment: This is the magic step. Activating the environment means you are "sitting down at your private desk."
    -  For macOS / Linux (in Terminal)
`source ai-env/bin/activate`

    -  For Windows (in Command Prompt or PowerShell):
`.\ai-env\Scripts\activate`
    - You'll know it worked because your terminal prompt will change to show the name of your environment, like this: `(ai-env) C:\Users\YourName\Desktop\MyProject>`.

- Step 3: Work in the Environment: Now that your environment is active, any pip command you run will install libraries on your "private bookshelf," not in the global "public library." This is where you'll install NumPy, Pandas, etc.

- Step 4: Deactivate the Environment: When you're done working on your project, you can "leave your private desk" by simply typing:

    ```deactivate```

- Your terminal prompt will return to normal.

## 🚀 Setting up Jupyter Notebook workspace
1. Activate your virtual environment first! (`source ai-env/bin/activate`)
2. With the environment active, install JupyterLab:

    ```
    Bash
    pip3 install jupyterlab
    ```

3. To start the application, type:

    ```
    Bash
    jupyter-lab
    ```
- If successful, you will have JupyterLab launcher accessible on your browser. For example, on `http://localhost:8888/lab`

4. Create a New Notebook: In the JupyterLab launcher, click on the "Python 3 (ipykernel)" icon to create a new notebook named `ai-agentic-retrieval`.

5. Write and Run the Code: Click inside the first empty cell, type the following code, and press Shift + Enter to run it.
```
print(f"Welcome to Foundry IQ - Agentic retrieval solution")
```
The output will appear directly below the cell. You've just run code using in your private virtual environment!
