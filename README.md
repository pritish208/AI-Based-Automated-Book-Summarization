  # 📚 AI-Based Automated Book Summarization
This project provides an AI-powered system that automatically summarizes large text documents such as books, articles, or reports. Built using Python and NLP libraries, the summarizer helps readers quickly understand the key ideas and essential points without reading the entire content.

## 🚀 Features
📄 Load and process large text files (PDFs, EPUBs, TXT)
🧠 Extractive and/or Abstractive Summarization using NLP models
🔍 Text Preprocessing (tokenization, stopword removal, etc.)
📊 Summary Length Control
💬 Simple interface for input and output

## 🛠️ Technologies Used
Python 3.x
Jupyter Notebook
Natural Language Toolkit (NLTK)
spaCy
Hugging Face Transformers (for abstractive summarization)
Sumy / Gensim (for extractive summarization)
PyMuPDF / PDFPlumber (for PDF handling)
## 🧰 Installation
### 1. Clone the repository:

git clone https://github.com/yourusername/ai-book-summarizer.git
cd ai-book-summarizer

### 2.Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows

### 3.Install the required packages:
pip install -r requirements.txt


## 📝 Usage
### 1.Open the Jupyter Notebook:
jupyter notebook "Book Summerization.ipynb"
### 2.Upload a text file or paste the text into the input cell.

### 3.Choose the type of summarization:

3.1.Extractive: Selects key sentences

3.2.Abstractive: Uses deep learning to paraphrase

### 4.Run the notebook to generate the summary.

## 📂 File Structure

.
├── Book Summerization.ipynb     # Main Jupyter notebook
├── requirements.txt             # Python dependencies
├── README.md                    # Project documentation
└── sample_texts/                # (Optional) Folder for sample books/articles

## 📌 Example
Input: 10,000-word document
Output: 300-word summary highlighting the core ideas and themes

## ✅ Future Improvements
GUI using Streamlit or Flask

Multi-language summarization

Support for audio book summarization (via speech-to-text)

🙋‍♀️ Author
Pritish Ranjan Mohanty
MCA | Data Analytics & Machine Learning


📜 License
This project is open-source and available under the MIT License.
