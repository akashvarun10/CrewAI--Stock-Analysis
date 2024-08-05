# AI Crew for Stock Analysis
## Introduction
This project is an example using the CrewAI framework to automate the process of analyzing a stock. CrewAI orchestrates autonomous AI agents, enabling them to collaborate and execute complex tasks efficiently.

## CrewAI Framework
CrewAI is designed to facilitate the collaboration of role-playing AI agents. In this example, these agents work together to give a complete stock analysis and investment recommendation

## Running the Script
It uses GPT-4 by default so you should have access to that to run it.

***Disclaimer:** This will use gpt-4 unless you changed it 
not to, and by doing so it will cost you money.*

- **Configure Environment**: Copy ``.env.example` and set up the environment variables for [Browseless](https://www.browserless.io/), [Serper](https://serper.dev/), [SEC-API](https://sec-api.io) and [OpenAI](https://platform.openai.com/api-keys)
- **Install Dependencies**: Run `poetry install --no-root`.
- **Execute the Script**: Run `python main.py` and input your idea.

## Details & Explanation
- **Running the Script**: Execute `python main.py`` and input the company to be analyzed when prompted. The script will leverage the CrewAI framework to analyze the company and generate a detailed report.
- **Key Components**:
  - `./main.py`: Main script file.
  - `./stock_analysis_tasks.py`: Main file with the tasks prompts.
  - `./stock_analysis_agents.py`: Main file with the agents creation.
  - `./tools`: Contains tool classes used by the agents.

