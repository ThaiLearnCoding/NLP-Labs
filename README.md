# NLP Labs

A hands-on Natural Language Processing (NLP) lab collection covering the full workflow from text collection and preprocessing to language modeling, embeddings, classical machine learning, and neural networks.

This repository is organized by weekly labs and includes Jupyter notebooks, datasets, and practical exercises.

## Project Goals

- Practice core NLP pipelines end-to-end.
- Learn and compare classical and modern NLP methods.
- Build intuition through experiments on real-world text datasets.
- Develop reproducible notebook-based workflows.

## Repository Structure

```text
NLP Labs/
├── Lab 1 - Web scraping/
│   ├── data.json
│   ├── HEX_lab1.ipynb
│   └── Web_scraping.ipynb
├── Lab 2 - Exploring and preprocessing text data/
│   ├── HEX-Lab2.ipynb
│   ├── In-class-Lab2.ipynb
│   └── wiki.txt
├── Lab 3 - Language Models/
│   ├── Home_Exercise.ipynb
│   ├── Inclass.ipynb
│   ├── Self_experiement.ipynb
│   └── tedtalk.txt
├── Lab 4 - Vector Semantic and Embeddings/
│   ├── Home_Lab4.ipynb
│   └── In-class-Lab4.ipynb
├── Lab 5 - Word Embedding/
│   ├── Plagiarism Detection.ipynb
│   └── Sentiment Analysis.ipynb
├── Lab 6 + 7 - ML and Linear Model/
│   ├── data/
│   │   ├── House Price/
│   │   └── Titanic/
│   └── notebooks/
│       ├── Housing Prices Competition.ipynb
│       └── Titanic - Machine Learning from Disaster.ipynb
├── Lab 8 - Neural Network/
│   ├── data/
│   │   └── sample_submission.csv
│   └── notebooks/
│       ├── Digit Recognizer.ipynb
│       └── Math Lab Visualization.ipynb
└── Lab 9 - Recurrent Neural Networks/
    ├── Named Entity Recognition.ipynb
    └── Text classification.ipynb
```

## Lab Overview

1. **Lab 1 - Web Scraping**
   - Collect and structure raw text data from web sources.
2. **Lab 2 - Text Exploration and Preprocessing**
   - Clean, normalize, and inspect textual corpora.
3. **Lab 3 - Language Models**
   - Work with statistical/probabilistic language modeling concepts.
4. **Lab 4 - Vector Semantics and Embeddings**
   - Represent words/documents in vector space.
5. **Lab 5 - Word Embeddings Applications**
   - Apply embeddings to sentiment analysis and plagiarism detection.
6. **Lab 6 + 7 - Classical ML and Linear Models**
   - Solve prediction tasks on tabular datasets (e.g., Titanic, House Prices).
7. **Lab 8 - Neural Networks**
   - Build and evaluate neural-network-based models.
8. **Lab 9 - Recurrent Neural Networks**
   - Sequence modeling tasks such as NER and text classification.

## Requirements

Recommended environment:

- Python 3.9+
- Jupyter Notebook or JupyterLab

Common Python packages used in these labs (varies by notebook):

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- nltk
- gensim
- tensorflow or pytorch

Install core dependencies:

```bash
pip install jupyter numpy pandas matplotlib seaborn scikit-learn nltk gensim
```

If a notebook requires additional packages, install them in your active environment as needed.

## How to Run

1. Open the repository in VS Code (or your preferred IDE).
2. Start Jupyter:

```bash
jupyter notebook
```

3. Open a lab folder and run notebooks cell-by-cell.
4. For reproducibility, restart kernel and run all cells after major edits.

## Suggested Learning Path

1. Complete labs in numeric order.
2. For each lab:
   - Run the in-class notebook first.
   - Complete home exercise notebook next.
   - Record your observations and experiment results.
3. Compare model performance and document what changed and why.

## Notes

- Some datasets are included locally in the repository.
- Keep large generated outputs/checkpoints outside version control where possible.
- File names are kept as provided by the course material.

## License

This repository appears to be course/lab material. Add your preferred license if you plan to distribute it publicly.
