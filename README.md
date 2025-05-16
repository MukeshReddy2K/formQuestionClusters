# Text Clustering of Form Questions using KMeans

This project applies Natural Language Processing (NLP) and unsupervised machine learning techniques to analyze and cluster form-based questions. The core objective is to group similar questions using **TF-IDF vectorization** and **KMeans clustering**.

## 📁 Project Structure

- `Text_analysis_kMeans.ipynb`: Jupyter Notebook containing the complete analysis workflow.
- `formQuestions.csv`: Dataset file containing text-based questions used for clustering.

## 📌 Key Steps

1. **Data Loading**: Load a dataset of questions from a CSV file.
2. **Preprocessing**: Clean and prepare the questions, removing null values.
3. **TF-IDF Vectorization**: Convert textual data into numerical format using scikit-learn's `TfidfVectorizer`.
4. **Clustering with KMeans**: Apply KMeans clustering to group similar questions.
5. **Results Analysis**: (Optional) Analyze clusters to understand common themes or topics.

## 🛠️ Technologies Used

- Python
- Pandas
- scikit-learn (TF-IDF & KMeans)
- NumPy
- Jupyter Notebook

## 🚀 Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.x
- Jupyter Notebook or VS Code
- pip packages: `pandas`, `numpy`, `scikit-learn`

### Run the Notebook
```bash
jupyter notebook Text_analysis_kMeans.ipynb
