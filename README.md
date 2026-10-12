# Machine Learning Practical Work 6

## Text Classification of Russian-Language Reviews

### Objective
To implement a text preprocessing pipeline, vectorize reviews using TF-IDF, train a Naive Bayes classifier, and evaluate its performance.

### Dataset
Russian-language reviews with labeled classes.

The dataset is stored in the `data/` directory. See the notebook for dataset details and preprocessing.

### Methods
- Lowercasing and text normalization
- Removal of punctuation, digits, and stop words
- Tokenization
- TF-IDF vectorization
- Multinomial Naive Bayes
- Train/test split: 80/20
- Evaluation using Accuracy, Precision, Recall, F1-score, and a confusion matrix
- Analysis of five misclassified reviews

### Project Structure

```text
ml-practice-6/
├── data/
├── notebooks/
│   └── analysis.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

### How to Run

1. Create and activate a Python virtual environment.
2. Install dependencies:

   `pip install -r requirements.txt`

3. Open `notebooks/analysis.ipynb` in VS Code.
4. Select the project's Python environment and run the notebook cells.

### Results

- Number of processed reviews: [value]
- Number of TF-IDF features: [value]
- Accuracy: [value]
- Macro F1-score: [value]

### Conclusion
The notebook contains the complete text classification pipeline, evaluation results, and analysis of model errors.