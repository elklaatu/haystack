# Haystack Exploration

## Description
This project explores the capabilities of Haystack, focusing on building robust NLP pipelines. Version control and dependency management are handled using Poetry based on their DeepLearning.AI course.

## Repository Structure
- **data/**: Source texts for document indexing and processing.
- **helper.py**: Utility functions for assisting in notebook operations.
- **Notebooks**:
  - **nb1_haystack_building_blocks.ipynb**: Explores the building blocks of Haystack.
  - **nb2_build_customized_rag.ipynb**: Demonstrates how to create a customized RAG model.
  - **nb3_news_summarizer.ipynb**: Implements a news summarizer using Haystack.
  - **nb4_fallback_with_branching_pipelines.ipynb**: Integrates SerperDevWebSearch functions.
  - **nb5_self_reflecting_agents_with_loops.ipynb**: Introduces self-reflecting loops in agents.
  - **nb6_chatagent_with_function_calling.ipynb**: Enhances chat agents with function calling.
- **poetry.lock** & **pyproject.toml**: Manage dependencies and project setup via Poetry.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/elklaatu/haystack
   ```
2. Install dependencies using Poetry:
   ```bash
   poetry install --no-root
## Usage
- Open and execute the notebooks in a Jupyter environment.
  ```bash
   poetry run jupyter lab --no-browser
- Follow the instructions in each notebook to replicate the experiments and analyses.

## Contributing
Please follow these steps to contribute:
1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add YourFeature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.
