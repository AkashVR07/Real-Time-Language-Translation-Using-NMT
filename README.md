# Real-Time-Language-Translation-Using-NMT
This Python project implements a simple Multi-Language Translator using the Hugging Face transformers library and the MarianMT model from Helsinki-NLP. It supports translation between multiple languages, including English, Spanish, French, German, Italian, Dutch, Russian, Chinese, Japanese, and Korean. The translator allows users to input text in a source language and translate it into a target language of their choice.

# Features
* Supports translation between 10 languages: English, Spanish, French, German, Italian, Dutch, Russian, Chinese, Japanese, and Korean.
* Uses the state-of-the-art MarianMT model for high-quality translations.
* Simple command-line interface for user interaction.
* Configurable source and target languages from a predefined list.

# Prerequisites
Before running the project, ensure you have the following installed:
* Python 3.6 or higher
* Required Python packages: transformers, torch

# Installation
1. Clone this repository or download the source code.
2. Navigate to the project directory and install the dependencies:
3. Ensure you have a stable internet connection to download the pre-trained models from Hugging Face.

# Usage
Run the translator script (translator.py) from the command line:
python translator.py

Follow the on-screen prompts:
1. The program will display a list of available languages and their corresponding language codes.
2. Enter the source language (e.g., "English") and the target language (e.g., "Spanish").
3. Input the text you want to translate. Type 'exit' to quit the program.
4. View the translated text output.

Example
text
Welcome to the Real-Time-Language-Translator!
Available languages:
- English (en)
- Spanish (es)
- French (fr)
- German (de)
- Italian (it)
- Dutch (nl)
- Russian (ru)
- Chinese (zh)
- Japanese (ja)
- Korean (ko)
Enter source language: English
Enter target language: Spanish
Enter text to translate from English to Spanish (or type 'exit' to quit): Hello, how are you?
Translated Text: Hola, ¿cómo estás?

# Supported Languages
The translator supports the following languages:

* English (en)
* Spanish (es)
* French (fr)
* German (de)
* Italian (it)
* Dutch (nl)
* Russian (ru)
* Chinese (zh)
* Japanese (ja)
* Korean (ko)

# Contributing
Contributions are welcome! If you'd like to enhance this project, please fork the repository and submit a pull request. You can contribute by:

* Adding support for more languages.
* Improving the translation accuracy or speed.
* Enhancing the user interface.
* Fixing bugs or improving documentation.

# License
This project is licensed under the [MIT License](https://opensource.org/license/MIT).

# Acknowledgments
The project utilizes the transformers library by Hugging Face and the pre-trained MarianMT models by Helsinki-NLP.
Special thanks to the open-source community for their tools and resources.

# Author
[Akash VR](https://github.com/AkashVR07)
