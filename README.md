# Project Title: Cluster Based Classification of Question Based Algebraic Solutions Through Machine Learning

## Description

This project focuses on predicting correct answers and questions using clustering and cosine similarity techniques. The dataset comprises 6 questions, each with 26 answers. The training dataset includes 126 answers for both latex and mathematical solutions, alongside corresponding key answers (keylatex and keymathematical). Additionally, there are 26 answers available for testing purposes. MathBERT embeddings are provided for mathematical solutions to enhance model performance. Matpix.ai is used for converting manual scripts to latex and algebraic solutions.

## Files Included:

- **training_mathbert3latexsolutions.xlsx**: Training data containing latex solution answers.
- **training_mathbert4mathematicalsolutions.xlsx**: Training data containing mathematical solution answers.
- **training_mathbert5testinglatexsolutions.xlsx, training_mathbert6testinglatexsolutions.xlsx**: Testing data for evaluation of both latex and mathematical solutions.
- **training_mathbert1keylatexsolutions.xlsx, training_mathbert2keymathematicalsolutions.xlsx**: Key answers for latex solutions and mathematical solutions respectively.

## Methodology:

1. **Data Preparation**:  
   Preprocess the training data and key answers for model training.

2. **Model Training**:  
   Utilize clustering and cosine similarity techniques for answer and question prediction.

3. **Evaluation**:  
   Evaluate the trained models using the testing dataset to assess accuracy and performance.

4. **Comparison**:  
   Compare the effectiveness of clustering and cosine similarity for answer and question prediction tasks.

5. **Conclusion**:  
   Draw conclusions based on the performance comparison and identify potential areas for improvement.

## Dependencies:

- Python 3.x
- pandas
- scikit-learn
- numpy
- MathBERT embeddings (for mathematical solutions)

## Author:

- Okesh Reddy
- Arella Mouhitha
- Saranya

## Contact:

- Email: bl.en.u4aie22044@bl.students.amrita.edu
