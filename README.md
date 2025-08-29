# Real-Time-Language-Translation-Using-NMT
This Python project implements a Real-Time Multi-Language Translator with a graphical interface using Kivy. It leverages the Hugging Face MarianMT models (Helsinki-NLP) for neural machine translation. Unlike the command-line version, this project provides an interactive desktop GUI where users can select a target language, load the appropriate model, type input text, and view translations in real-time.

# Features
* 🖥️ Graphical Interface built with Kivy (modern and user-friendly).
* 🌍 Supports translation from English → multiple languages.
* 🚀 Uses Hugging Face MarianMT models for high-quality translations.
* ⚡ Real-time translation as users type.
* 🔧 Clear status updates (Ready, Loading, Translating, Error).
* 🔒 Source language fixed to English (simplifies usage).
* 🎨 Custom-styled dropdowns and text display for a smooth UI.

# Prerequisites
Before running the project, ensure you have installed:
* Python 3.7 or higher
Required Python packages:
* transformers
* torch
* kivy

# Installation
1. Clone this repository or download the source code.
2. Navigate to the project directory and install the dependencies:
```pip install transformers torch kivy```
3. Ensure you have a stable internet connection (to download MarianMT models from Hugging Face when loading the translator).

# Usage
Run the translator app with:
```python main.py```

# Snapshot
<img width="1002" height="787" alt="Snapshot" src="https://github.com/user-attachments/assets/cc09e37f-081a-4d02-86b2-d81990894317" />

Example

* Source Language: English
* Target Language: French
* Input: "Hello, how are you?"
* Output: "Bonjour, comment ça va ?"
