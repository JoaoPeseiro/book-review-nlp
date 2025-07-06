# 📚 Book Review NLP

An end-to-end NLP project that analyzes 100,000 Amazon book reviews to extract insights, including sentiment classification, thematic clustering, and text summarization.

## 🔍 Objectives

- Classify the **sentiment** of user reviews (positive, neutral, negative)
- Group similar reviews by **themes or topics** using clustering and embeddings
- Normalize categories with **zero-shot/few-shot GPT prompting**
- Generate **summaries** per category using Hugging Face pipelines
- Output a list of **book recommendations** based on review clusters

## 🛠 Technologies Used

- Python
- Hugging Face Transformers (`pipeline`, `sentence-transformers`)
- scikit-learn (clustering & evaluation)
- Pandas & NumPy
- Seaborn & Matplotlib
- OpenAI GPT (zero-shot & few-shot)
- tqdm

## 📁 Project Structure
book-review-nlp/
├── data/ # Raw data (Amazon reviews)
├── notebooks/ # Jupyter Notebooks
├── outputs/ # Final predictions or summaries
├── requirements.txt # Project dependencies
├── README.md # Project overview
└── .gitignore # Ignored files

bash
Copiar
Editar

## 📦 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/teu-utilizador/book-review-nlp.git
   cd book-review-nlp
Create a virtual environment (optional but recommended):

bash
Copiar
Editar
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
Install dependencies:

bash
Copiar
Editar
pip install -r requirements.txt
Run the notebook:
Open notebooks/final_project_notebook.ipynb in Jupyter or VSCode.

🧠 Results
Final categories: ~8–10 well-defined clusters

Sentiment classifier with balanced metrics

GPT-enhanced summaries by category

CSV output with best-rated books per theme

✍️ Author
João Peseiro