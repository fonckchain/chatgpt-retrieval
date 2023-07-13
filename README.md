<p align="center">
  <img width="180" src="./public/logo.png" alt="ChatGPT">
  <h1 align="center">ChatGPT Retrieval</h1>
  <p align="center">Simple script to use ChatGPT on your own files</p>
</p>

Here's the [Original YouTube Guide](https://youtu.be/9AXP7tCI9PI).

## 📦 Installation

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.

```
pip install langchain openai chromadb tiktoken unstructured
```

Modify `constants.py.default` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys), and rename it to `constants.py`.

Place your own additional data into `data`.

## ✨ Example usage

Test reading `data/data.txt` file.

```
> python chatgpt.py "what is my dog's name"
Your dog's name is Lilia.
```

Test reading `data/cat.pdf` file.

```
> python chatgpt.py "what is my cat's name"
Your cat's name is Muffy.
```

## 🔄 Alternate Version

There's also an alternate version of the script that prioritizes retrieving answers from the dataset before using the OpenAI model. This can help reduce the cost of using the OpenAI API.

To use the alternate version, run the `chatgpt_reduced_cost.py` script instead of `chatgpt.py`.

```bash
> python chatgpt_alternate.py "what is my dog's name"
Your dog's name is Lilia.

```
