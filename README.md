# Multi-Agent AI and Generative AI Use Case Generation System

This project implements a Multi-Agent architecture to generate relevant AI and Generative AI (GenAI) use cases for companies in specific industries. The system conducts market research, understands industry trends, and identifies strategic focus areas for each company. It provides actionable use cases and resources to enhance operational efficiency and customer experience.

## Overview

This multi-agent system is designed to help companies leverage AI, ML, and GenAI technologies to improve processes, increase customer satisfaction, and boost operational efficiency. It utilizes the `CrewAI` library to create and manage multiple agents, each tasked with a specific role in the workflow, such as researching industry standards, generating use cases, and collecting relevant resources.

## Architecture

The system is built using the following agents:

1. **Industry & Company Research Agent**: Conducts industry and company research, gathering information on key offerings, strategic areas, and market standards.
2. **Market Standards & Use Case Generation Agent**: Analyzes industry trends to identify AI and ML use cases relevant to the company's strategic goals.
3. **Resource Collection Agent**: Searches for datasets and resources on platforms like Kaggle, HuggingFace, and GitHub for the proposed AI/ML use cases.
4. **Report Generation Agent**: Compiles findings into a final report, with clickable links to resources and references.

## Key Features

- **Multi-Agent Collaboration**: Agents work in collaboration to streamline research, use case generation, resource collection, and report creation.
- **Industry-Specific Use Cases**: Use cases are generated based on market standards, with a focus on customer satisfaction, operational improvements, and GenAI innovations.
- **Resource Collection**: Finds relevant datasets from trusted platforms to facilitate the implementation of proposed use cases.
- **Report Generation**: Compiles insights, use cases, and resources into a structured markdown report.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Stephenca290/Multi-Agent-Use-Case-Generator.git
   ```
2. Install the required dependencies:

```bash
pip install crewai
```
3.Set up API keys for CrewAI and Serper in the code.

4. Run the main script:

```bash
python main.py
```
The generated report will be outputted as a markdown file.

Project Files
main.py: Core script to set up agents and tasks, and to generate the use cases and final report.
README.md: Project documentation.
Agents
Industry & Company Research Agent: Researches the industry and segments the company based on offerings and strategic focus.
Market Standards & Use Case Generation Agent: Identifies AI and ML use cases aligned with industry trends.
Resource Collection Agent: Collects relevant datasets and resource links.
Report Generation Agent: Prepares a final proposal report with use cases and resource links.
Demo
A demo video explaining the architecture flowchart and generated output can be found here: [Demo Video Link].

License
This project is licensed under the MIT License - see the LICENSE file for details.

