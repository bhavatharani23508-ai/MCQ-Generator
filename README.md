# AI MCQ Generator

AI MCQ Generator is a Streamlit-based application that automatically creates multiple-choice questions from study material using a Hugging Face AI model.

## Features

* Generate MCQs from study material
* Upload PDF documents
* Paste text directly
* Choose the number of questions (1–50)
* Four options for each question
* Automatic answer key generation
* PDF text preview
* Powered by Hugging Face GPT-OSS-120B

## Technologies Used

* Python
* Streamlit
* Hugging Face Inference API
* GPT-OSS-120B
* PyPDF
* python-dotenv

## Project Structure

```text
AI-MCQ-Generator/
│
├── mcqgenerator.py
├── pdf_utils.py
├── requirements.txt
├── .env
└── .gitignore
```

## Installation

Clone the repository and install the required packages:

```bash
pip install -r requirements.txt
```

Create a `.env` file and add your Hugging Face API token:

```env
HF_TOKEN=your_huggingface_token
```

Run the application:

```bash
streamlit run mcqgenerator.py
```

## How It Works

1. Enter study material or upload a PDF.
2. Select the required number of questions.
3. Click Generate MCQs.
4. The AI generates questions with four options.
5. The generated answer key is displayed along with the questions.

## Purpose

This project helps students quickly create practice questions from their study materials, making revision and self-assessment easier.
