Friends Character Similarity
This project is part of an NLP assignment focusing on vector space semantics to distinguish characters from the "Friends" TV show script. The goal is to create and improve vector representations for character lines to enhance classification accuracy based on similarity measures.

Project Overview
In this assignment, we create vector representations of documents containing lines spoken by characters from the Friends script. The task is to improve these representations to distinguish each character from others more effectively.

Key Objectives
Create initial vector representations for each character.
Enhance vector representations using pre-processing, feature extraction, and transformation techniques.
Evaluate the effectiveness of the representations using similarity-based information retrieval methods.

Data
The project uses script data from Friends provided in the following CSV files:

training.csv: Contains lines for training the model.
val.csv: Used for validation.
test.csv: Used for testing the model's performance.
Each file includes:

Episode and scene identifiers.
Character names.
Lines spoken by characters.
Gender of the speakers.


Requirements
To run the notebook, ensure you have the following Python packages installed:
nltk
pandas
numpy
matplotlib
scikit-learn

You can install these dependencies using pip:
pip install nltk pandas numpy matplotlib scikit-learn


Usage
Clone the repository and navigate to the project directory.
Open the Jupyter Notebook NLP_Assignment_wtf.ipynb.
Follow the notebook steps to load data, preprocess, and evaluate the vector representations.
Experiment with the questions and tasks to improve the character vector representations.

Evaluation
The project evaluates the vector representations using:

Mean Rank:
The mean rank of the target document in terms of similarity.
Mean Cosine Similarity: The average cosine similarity score for the target document vs. the test document of the same class.
Accuracy: The proportion of test documents correctly classified.
Visualization
The project includes a heatmap visualization of the similarity matrix, providing insights into the relationships between character vector representations.

Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

