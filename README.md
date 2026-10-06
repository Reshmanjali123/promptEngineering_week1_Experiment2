# promptEngineering_week1_Experiment2
# LLM Prompt Engineering Experiments

This repository contains experiments demonstrating **LLM connectivity and prompt engineering using Python**.

## Experiments

### Experiment 1 – LLM Connectivity

The first experiment demonstrates how to connect a Python program to a Large Language Model (LLM) using an API.

**Task:**
- Connect to the LLM using an API key.
- Send a simple prompt.
- Receive and display the model response.
- Handle API and connection errors.

### Experiment 2 – Prompt Engineering

The second experiment demonstrates how prompt engineering can improve the quality and structure of an LLM response.

The experiment compares:

- **Baseline Prompt:** A simple question with minimal instructions.
- **Enhanced Prompt:** A prompt containing a role, target audience, constraints, and output requirements.

**Task used:**

> What is a prime number?

The enhanced prompt asks the model to act as a math tutor for 5th graders, use simple language, provide a definition and two examples, and keep the answer under 50 words.

## Repository Structure

```text
LLM-Experiments/
│
├── experiment-1/
│   ├── experiment1.py
│   └── experiment1.ipynb
│
├── experiment-2/
│   ├── experiment2.py
│   └── experiment2.ipynb
│
├── outputs/
│   ├── output_1.png
│   └── output_2.png
│
├── .env.example
├── .gitignore
└── README.md
```

## Technologies Used

- Python
- Google Colab
- OpenAI API
- Git
- GitHub

## How to Run

1. Open the required `.ipynb` file in Google Colab.
2. Install the required Python package.
3. Configure the API key securely.
4. Run the notebook cells in order.
5. Observe the baseline and enhanced prompt responses.

## API Key Security

The API key should **never be uploaded to GitHub**.

Use an environment variable such as:

```text
OPENAI_API_KEY
```

The `.env` file is excluded using `.gitignore`.

The repository contains only `.env.example` as a reference.

## Result

The experiments demonstrate how an LLM can be connected through an API and how a carefully designed prompt can produce a more specific, structured, and readable response.

## Output

Execution screenshots are stored in the `outputs` folder as required for the lab manual.
