# Project Overview

This project implements a LangChain model using the Groq Llama3 model within a Jupyter Notebook. The notebook guides users through the process of setting up the environment, defining tools, creating prompts, and running an agent to fetch information.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Setup Instructions](#setup-instructions)
3. [Usage Examples](#usage-examples)
4. [License](#license)

## Setup Instructions

To get started with this project, follow these steps:

1. **Clone the Repository**: 
   Clone this repository to your local machine using the following command:
   ```
   git clone <repository-url>
   ```

2. **Install Dependencies**: 
   Ensure you have the required libraries installed. You can install them using pip:
   ```
   pip install langchain langchain_groq langchain_community
   ```

3. **Set Up Environment Variables**: 
   You will need to set up your API keys for Groq and Tavily. Add the following lines to your environment variables:
   ```
   export GROQ_API_KEY="your_groq_api_key"
   export TAVILY_API_KEY="your_tavily_api_key"
   ```

## Usage Examples

Once the setup is complete, you can start using the Jupyter Notebook:

1. Open the `langchain_model1.ipynb` file in Jupyter Notebook.
2. Follow the steps outlined in the notebook to initialize the model, define tools, and create prompts.
3. Run the agent to fetch information by executing the provided code cells.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.