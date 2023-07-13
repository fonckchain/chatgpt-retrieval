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
> Please explain the house of cards thesis in detail by attobit and it's possible implications"
The "House of Cards" thesis, as presented by u/ATOBITT, suggests that there may be significant discrepancies and inaccuracies in the reporting of short interest data by the SEC (Securities and Exchange Commission). The thesis is based on the information shared by Wes Christian during an AMA (Ask Me Anything) session.

According to Wes Christian, there have been instances where the actual short interest in a particular stock is much higher than what is officially reported by the SEC. He claims that his firm obtained data for legal proceedings that indicate the real short interest can be 50% to 150% more than the reported figures.

Short interest refers to the number of shares of a stock that have been sold short by investors. It is a measure of market sentiment and can impact the stock's price. If the short interest is higher than what is officially reported, it implies that there might be more investors betting against a particular stock than initially thought.

The possible implications of this "House of Cards" thesis are significant. If the reported short interest is understated, it can lead to a false perception of market sentiment and potentially influence trading decisions. It could also affect the ability of investors to accurately gauge the level of risk associated with a particular stock.

However, it is important to note that this thesis is based on the claims made by Wes Christian during the AMA session. It would require further investigation and verification to determine the validity and
extent of the alleged discrepancies in short interest reporting by the SEC.
```

```
> python chatgpt.py "Prompt: What were the net sales of GameStop for Q4 2022? "
The net sales of GameStop for Q4 2022 were $2.261 billion.
```
