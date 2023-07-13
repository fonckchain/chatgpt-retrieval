# GameStop ChatGPT Retrieval

Simple script to use ChatGPT to interact with GameStop phenomenon data, including resources from the SupersStonk community, GameStop's blockchain ventures and GameStop's financial data.

Here's the [Original YouTube Guide](https://youtu.be/9AXP7tCI9PI).

## Installation

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.

```
pip install langchain openai chromadb tiktoken unstructured
```

Modify `constants.py.default` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys), and rename it to `constants.py`.

Place your own additional data into `data`.

## Example usage

```
> python chatgpt.py "what is my dog's name"
Your dog's name is Lilia.
```

```
> python chatgpt.py "Prompt: What were the net sales of GameStop for Q4 2022? "
The net sales of GameStop for Q4 2022 were $2.261 billion.
```
