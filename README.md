# 🌐 Gen AI Language Translator

A multilingual **AI-powered language translation application** built using the **M2M-100 1.2B** model from Meta/Facebook. The application provides a simple Gradio interface where users can enter text, select a source language and target language, and generate the translated text.

## 🚀 Features

* 🌍 Multilingual text translation
* 🤖 Uses the M2M-100 1.2B transformer model
* 🧠 Powered by Hugging Face Transformers
* ⚡ Uses PyTorch for model inference
* 🖥️ Simple and interactive Gradio interface
* 🔄 Supports multiple source and target language combinations

## 🌎 Supported Languages

The project currently provides the following language options:

| Code | Language   |
| ---- | ---------- |
| `en` | English    |
| `fr` | French     |
| `de` | German     |
| `es` | Spanish    |
| `it` | Italian    |
| `pt` | Portuguese |
| `ru` | Russian    |
| `zh` | Chinese    |
| `ja` | Japanese   |
| `hi` | Hindi      |

## 🛠️ Technologies Used

* **Python**
* **PyTorch**
* **Hugging Face Transformers**
* **M2M-100 1.2B**
* **Gradio**
* **Google Colab**

## 🧠 Model

This project uses:

`facebook/m2m100_1.2B`

The model and tokenizer are loaded using Hugging Face Transformers.

M2M-100 is a multilingual sequence-to-sequence model designed for translation between multiple languages.

## ⚙️ How It Works

1. The user enters text into the Gradio interface.
2. The user selects the source language.
3. The user selects the target language.
4. The input text is tokenized.
5. The target language token is specified for generation.
6. The M2M-100 model generates the translation.
7. The generated tokens are decoded and displayed to the user.

The translation function uses the tokenizer to process the input and the model to generate the translated output.

## 📦 Installation

Install the required Python packages:

```bash
pip install transformers torch gradio
```

The notebook uses these three main packages.

## ▶️ Running the Project

### Google Colab

1. Open `Gen_AI_Language_translator.ipynb` in Google Colab.
2. Run the installation cell.
3. Load the M2M-100 model.
4. Run the translation function.
5. Launch the Gradio interface.
6. Enter text and select the source and target languages.

The notebook was configured to run with a GPU/T4 accelerator in Colab.

### 💻 Local Setup

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Gen-AI-Language-Translator.git
cd Gen-AI-Language-Translator
```

Install dependencies:

```bash
pip install transformers torch gradio
```

Then open and run the Jupyter Notebook.

## 🖥️ User Interface

The Gradio interface contains:

* Text box for input text
* Source language dropdown
* Target language dropdown
* Translated text output

These components are implemented using Gradio in the notebook.

## 📁 Project Structure

```text
Gen-AI-Language-Translator/
│
├── Gen_AI_Language_translator.ipynb
└── README.md
```

## 🎯 Example

**Input:**

```text
Hello, how are you?
```

**Source Language:**

```text
English
```

**Target Language:**

```text
French
```

**Output:**

```text
Bonjour, comment allez-vous ?
```

## 🔮 Future Improvements

* Add more languages
* Add automatic source-language detection
* Add speech-to-text translation
* Add text-to-speech output
* Improve the user interface
* Deploy the application permanently using Hugging Face Spaces
* Add translation history
* Add support for document translation

## 👩‍💻 Project

**Project:** Gen AI Language Translator
**Model:** M2M-100 1.2B
**Framework:** Hugging Face Transformers
**Interface:** Gradio
**Language:** Python

## 📜 License

This project is created for educational and learning purposes.
