📁 Code
This folder contains all the source code used to build, train, evaluate, and visualize the sarcasm detection models.

Structure
bash
Copy
Edit
code/
├── data_preprocessing.py      # Cleans and preprocesses the raw dataset
├── feature_extraction.py      # Converts text into numerical features (TF-IDF, embeddings)
├── model_training.py          # Trains ML models like Logistic Regression, SVM, etc.
├── deep_learning_model.py     # Builds and trains LSTM or other deep learning models
├── evaluation.py              # Evaluates model performance using accuracy, precision, recall, F1-score
├── visualization.py           # Plots metrics and data distributions
├── utils.py                   # Common helper functions
└── config.py                  # Configuration settings and parameters
Requirements
Before running the code, install the required Python libraries:

bash
Copy
Edit
pip install -r ../requirements.txt
Usage
Preprocess Data

bash
Copy
Edit
python data_preprocessing.py
Extract Features

bash
Copy
Edit
python feature_extraction.py
Train a Model

bash
Copy
Edit
python model_training.py
Evaluate the Model

bash
Copy
Edit
python evaluation.py
(Optional) Train Deep Learning Model

bash
Copy
Edit
python deep_learning_model.py
Visualize Results

bash
Copy
Edit
python visualization.py
Notes
You can adjust model parameters and paths in config.py.

Ensure the dataset is placed in the ../datasets/ folder before running scripts.

The code is modular and can be reused or extended easily for similar NLP tasks.

License
This code is released under the MIT License. You are free to use and modify it with proper attribution.
