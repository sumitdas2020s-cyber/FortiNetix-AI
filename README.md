# Agents Lab Notebook v1.0.0

![image](https://raw.githubusercontent.com/IBM/watson-machine-learning-samples/master/cloud/notebooks/headers/watsonx-Prompt_Lab-Notebook.png) This notebook contains steps and code to demonstrate the use of agents configured in Agent Lab in watsonx.ai. It introduces Python API commands for authentication using API key and invoking a LangGraph agent with a watsonx chat model. **Note:** Notebook code generated using Agent Lab will execute successfully. If code is modified or reordered, there is no guarantee it will successfully execute. For details, see: <a href="/docs/content/wsj/analyze-data/fm-prompt-save.html?context=wx" target="_blank">Saving your work in Agent Lab as a notebook.</a> Some familiarity with Python is helpful. This notebook uses Python 3.11. The learning goals of this notebook are: * Defining a Python function for obtaining credentials from the IBM Cloud personal API key * Creating an agent with a set of tools using a specified model and parameters * Invoking the agent to generate a response

<!-- Add CI, license, or Python version badges here -->

## Features

- End-to-end workflow in a Jupyter notebook
- Clear, step-by-step cells with comments
- Reproducible environment suggestions

## Notebook Outline

- Agents Lab Notebook v1.0.0
- Notebook goals
- Setup
- watsonx API connection
- Using the agent
- Defining the model id
- Defining the model parameters
- Defining the project id or space id
- Creating the agent
- Invoking the agent
- Next steps
- Copyrights

## Data

Provide your dataset paths where indicated in the notebook.

## Requirements

Install dependencies (best-effort inference):

```bash
pip install langchain_core ibm_watsonx_ai langgraph langchain_ibm requests getpass ast IPython
```

## Quickstart

1. Create and activate a virtual environment (recommended).
2. Install dependencies (see above).
3. Open the notebook:

```bash
jupyter lab FortiNetix Ai.ipynb
```

4. Run cells from top to bottom, configuring any paths or credentials as noted in the markdown.

## Convert Notebook to Script (optional)

```bash
jupyter nbconvert --to script "FortiNetix Ai.ipynb"
```

## Repository Structure

```
.
├── FortiNetix Ai.ipynb  # main notebook
├── README.md                  # you are here
└── data/                      # put input data here (optional)
```

## Configuration & Secrets

- If the notebook interacts with external APIs or systems, set API keys via environment variables (e.g., `export API_KEY=...`).
- Do **not** commit secrets into version control.

## Results

Document key results, charts, and metrics here. You can also export figures from the notebook to `reports/`.

## Domain Notes

Tailor this section to your domain (e.g., finance, security, NLP). Provide context, assumptions, and limitations.

## License

Add a license (e.g., MIT) to clarify usage rights.

## Citation

If you use this project in academic work, include a proper citation.
