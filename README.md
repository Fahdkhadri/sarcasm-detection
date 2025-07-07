📁 Datasets
This folder contains the dataset(s) used for training and evaluating the sarcasm detection models.

Dataset Description
Name: News Headlines Dataset for Sarcasm Detection

Source: [Kaggle / JSON file or any relevant source link]

Format: JSON / CSV

Size: Approx. [X MB], containing [N] records

Structure
Each data point typically contains the following fields:

headline: The news headline (text input)

is_sarcastic: Label (1 for sarcastic, 0 for not sarcastic)

(Optional) article_link: Link to the full article (if available)

Example:

json
Copy
Edit
{
  "headline": "thirtysomething scientists unveil doomsday clock of hair loss",
  "is_sarcastic": 1,
  "article_link": "https://www.theonion.com/article-link"
}
Usage
The dataset is used for:

Training supervised machine learning models

Evaluating model performance on sarcasm detection

Preprocessing tasks like tokenization, stopword removal, etc.

Notes
Ensure data is cleaned and shuffled before training

For deep learning models (e.g., LSTM), consider limiting headline length or using padding

If using your own dataset, please ensure it follows the same format or update the preprocessing scripts accordingly

License & Credits
Please refer to the original dataset license or attribution here. If you're using the Kaggle dataset, make sure to follow their usage guidelines.
