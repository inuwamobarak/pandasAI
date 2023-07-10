# pandasAI

![GitHub repo size](https://img.shields.io/github/inuwamobarak/pandasAI)
![GitHub stars](https://img.shields.io/github/stars/inuwamobarak/pandasAI?style=social)
![GitHub forks](https://img.shields.io/github/forks/inuwamobarak/pandasAI?style=social)
![GitHub](https://img.shields.io/github/license/inuwamobarak/pandasAI)

This repository showcases the application of artificial intelligence directly to the traditional Pandas library. pandasAI enables data analysis with Python by utilizing text-based, human-like conversations. This is made possible using GenAI, allowing users to perform data analysis tasks with simple text prompts, eliminating the need for traditional code-based workflows.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)
- [GitHub Repository](#github-repository)

## Introduction
PandasAI revolutionizes the way data analysis is performed using the Pandas library. By leveraging artificial intelligence and natural language processing techniques, pandasAI enables users to interact with data through text-based conversations. This simplifies the data analysis process and makes it more accessible to a wider audience, eliminating the need for writing complex code.

## Installation
To use the PandasAI library, follow these steps:
1. Install pandasAI using pip: `pip install pandasAI`
2. Import the library in your Python script: `import pandasAI as pdai`
3. Ensure you have the required dependencies installed, such as Pandas and GenAI.

## Usage
1. Import the PandasAI library: `import pandasAI as pdai`
2. Load your dataset using Pandas: `df = pdai.read_csv('dataset.csv')`
3. Perform data analysis tasks by interacting with the data using text prompts and commands.
4. Utilize available functions and methods provided by PandasAI for data manipulation, exploration, visualization, and more.

# Getting Started with Pandas AI

This guide will walk you through the process of getting started with PandasAI. There are two approaches you can take to use PandasAI: using LangChain models and a direct implementation.

## Using LangChain Models

To use LangChain models, you first need to install the Langchain package:

```shell
pip install langchain
```

Once installed, you can instantiate a LangChain object in your code:

```python
from pandasai import PandasAI
from langchain.llms import OpenAI

langchain_llm = OpenAI(openai_api_key="my-openai-api-key")
pandasai = PandasAI(llm=langchain_llm)
```

With these steps, your environment is now ready, and PandasAI will automatically utilize the LangChain llm and convert it to a PandasAI llm.

## Direct Implementation (Without LangChain)

If you prefer a direct implementation without using LangChain, follow these steps:

1. Start by installing PandasAI as it may not be preinstalled like Pandas:

```shell
pip install pandasai
```

2. Another crucial requirement is an OpenAI API key to use PandasAI. You can create an API key with an account on the OpenAI platform. Visit [OpenAI Account API Keys](https://platform.openai.com/account/api-keys) to create a key.

Make sure to keep your API key secure and follow best practices for handling API keys.

Once you have completed these steps, you can start using PandasAI for your data analysis tasks.

## Example Output
The following examples demonstrate how pandasAI simplifies data analysis tasks:

![download (14)](https://github.com/inuwamobarak/pandasAI/assets/65142149/04effe01-ac26-4074-bf05-fc957ddc38a2)

![download (12)](https://github.com/inuwamobarak/pandasAI/assets/65142149/88f76576-5ed8-41d6-92f5-25440abfd30c)


## Contributing
Contributions to pandasAI are welcome. To contribute, follow these steps:
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes and commit them: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

## GitHub Repository
The official GitHub repository for pandasAI can be found at: [https://github.com/gventuri/pandas-ai](https://github.com/gventuri/pandas-ai)
