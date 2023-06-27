# GPT-PromptOptimizer

GPT-PromptOptimizer is a Python-based Text Stemming Tool designed to help users optimize their prompts for large language models (LLMs) like OpenAI's GPT-3 and GPT-4. The tool performs stemming, stopwords removal, and punctuation cleaning, thereby reducing the number of tokens used in the prompts. This makes it particularly useful when working with APIs where tokens are limited.

## Features

- Text Stemming using the PorterStemmer from the NLTK library
- Stopwords and punctuation removal
- Display of optimized text and the reduction size percentage
- Option to copy the optimized text directly to clipboard
- GUI built with tkinter for ease of use

## Installation

The repository doesn't require explicit installation. However, you must have Python installed in your environment and the code installs necessary dependencies such as `nltk` and `pyperclip`.

## Usage

1. Clone this repository or download the code.
2. Run the script in your local environment.
3. The GUI will open where you can enter your text, and click on "Stem Text" to perform the optimization.
4. The optimized text and the reduction size will be displayed.
5. You can copy the optimized text to clipboard or clear the fields for new text entry.

## Dependencies

- NLTK: Used for tokenizing and stemming operations.
- pyperclip: Used for copying the output text to clipboard.

## Contributing

Feel free to contribute to this project by opening issues or submitting a pull request with improvements or fixes.

## License

[MIT](LICENSE)

*Please note: This tool is designed to aid in reducing the number of tokens used by prompts, however, the usability and comprehension of the prompts by the model may vary based on the nature and complexity of the text.*
