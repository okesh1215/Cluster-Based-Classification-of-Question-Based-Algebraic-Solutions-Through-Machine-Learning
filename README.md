Project Title:Cluster Based Classification of Question Based Algebraic Solutions Through Machine Learning

Description:

This project focuses on predicting correct answers and questions using clustering and cosine similarity techniques. The dataset comprises 6 questions, each with 26 answers. The training dataset includes 126 answers for both latex and mathematical solutions, alongside corresponding key answers (keylatex and keymathematical). Additionally, there are 26 answers available for testing purposes. MathBERT embeddings are provided for mathematical solutions to enhance model performance.

Files Included:

train_latex.csv: Training data containing latex solution answers.
train_mathematical.csv: Training data containing mathematical solution answers.
test.csv: Testing data for evaluation.
keylatex.csv: Key answers for latex solutions.
keymathematical.csv: Key answers for mathematical solutions.
mathbert_embeddings.npy: Embeddings generated using MathBERT for mathematical solutions.
Methodology:

Data Preparation: Preprocess the training data and key answers for model training.
Model Training: Utilize clustering and cosine similarity techniques for answer and question prediction.
Evaluation: Evaluate the trained models using the testing dataset to assess accuracy and performance.
Comparison: Compare the effectiveness of clustering and cosine similarity for answer and question prediction tasks.
Conclusion: Draw conclusions based on the performance comparison and identify potential areas for improvement.
Dependencies:

Python 3.x
pandas
scikit-learn
numpy
MathBERT embeddings (for mathematical solutions)
Author: Okesh Reddy, Arella Mouhitha, Saranya

Contact: bl.en.u4aie22044@bl.students.amrita.edu
