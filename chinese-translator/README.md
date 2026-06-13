# Chinese Translator

A Python translator program that reads English-to-Chinese word pairs from a text file, translates user-entered sentences, and tracks word frequency during the session.

The project uses an external dictionary file instead of hardcoding every translation directly into the program.

## Features

- Loads translations from `english_chinese_dict.txt`
- Stores translation pairs in a Python dictionary
- Translates each recognized English word into Chinese
- Uses `?` for words that are not found in the dictionary
- Tracks word frequency across entered sentences
- Lets the user translate multiple sentences in one run

## Concepts Practiced

- Python dictionaries
- File handling
- String parsing
- User input validation
- Loops
- Functions
- Word frequency counting

## How to Run

Make sure `chinese_translator.py` and `english_chinese_dict.txt` are in the same folder, then run:

```bash
python chinese_translator.py
```

## What I Learned

This project helped me understand how programs can read external data, store it in memory, and use it to create more flexible behavior than a hardcoded script.