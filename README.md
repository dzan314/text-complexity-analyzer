# Text complexity analyzer
This project is a simple and small Python-based tool for analyzing the linguistic complexity of input text.
It computes several linguistic metrics, such as avarage sentence and word length, hapax legomena, entropy, Guiraud's R, etc. The program produces a final score (0-100 scale) of text complexity.
Additional text metrics are displayed and a histogram of the most frequent words is displayed.

## Features
- tokenization (using custom regex pattern) 
- word count & sentence count  
- average word length  
- average sentence length  
- Type-token ratio corrected for text length - Guiraud's R
- Entropy-based lexical diversity  
- Hapax legomena count  
- Rare word ratio  
- A weighted complexity score  
- Word frequency histogram (Top N words)

Formulas and more information can be found in the second "readme" file (pdf)

## Usage
Run the script and enter input when asked:

```bash
python text_analyzer.py
```

Example output:
This text contains 3 sentences and 13 words with an avarage lenghth of 3.38 letters. (...)
complexity score of this text is 37.1
(...)

A histogram of the most frequent words will be displayed.

## Requirements
- Python 3.x
- matplotlib

## Future work
- multi-language/character support
- additional readability formulas
- CLI flags
- GUI/web interface
- better sentence segmentation

## License
MIT License 
