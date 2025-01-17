# Token Count

Token Count is a command-line utility that counts the number of tokens in a text string, file, or directory, similar to the Unix `wc` utility. It uses the OpenAI `tiktoken` library for tokenization and is compatible with GPT-3.5-turbo token counts.

## Installation

To install Token Count, run the following command in your terminal:

```bash
pip install token-count
```

## Usage

Token Count has three main options:

Count tokens in a text string:
```bash
token-count --text "Your text here"
```
Count tokens in a file:
```bash
token-count --file path/to/your/file.txt
```

Count tokens in a directory (recursively):
```bash
token-count --directory path/to/your/directory
```

You can provide any combination of these options. Token Count will print the token count for each input type.

## License

This project is licensed under the MIT License.