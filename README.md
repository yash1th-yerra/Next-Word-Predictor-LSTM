# Next-Word-Predictor-LSTM
Based on the content of the Jupyter notebook, here is a draft for the `README.md` file for the repository:

```
# Next Word Predictor using LSTM

## Introduction
This repository contains a project for predicting the next word in a given sequence of words using a Long Short-Term Memory (LSTM) neural network. The model is trained on a sample corpus and can generate the next word based on the input sequence.

## Demo
Input: `hi my name ____________`

Output: `hi my name is xyz`

## Strategy
1. Create a supervised learning model.
2. Convert the input data (text) into input-output pairs for training.
   - Example:
     - Input: `hi` -> Output: `my`
     - Input: `hi my` -> Output: `name`
     - Input: `hi my name` -> Output: `is`
     - Input: `hi my name is` -> Output: `xyz`
3. Train the model on these pairs.
4. Convert text into numbers (vector of real values) using tokenization.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yash1th-yerra/Next-Word-Predictor-LSTM.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Next-Word-Predictor-LSTM
   ```
3. Install the required dependencies:
   ```bash
   pip install tensorflow
   ```

## Usage
1. Open the Jupyter notebook `Next_Word_Predictor_LSTM.ipynb`.
2. Execute the cells to preprocess the text data, train the LSTM model, and make predictions.
3. Modify the `faqs` variable to use your own text data for training and prediction.

## Sample Corpus
The sample corpus used in this project is a collection of frequently asked questions (FAQs) about a Data Science Mentorship Program. The text is tokenized and converted into input-output pairs for training the model.

## Tokenization
The text data is tokenized using the `Tokenizer` class from `tensorflow.keras.preprocessing.text`. The tokenized sequences are then used to train the LSTM model.

## Model Training
The LSTM model is trained on the tokenized sequences to learn the patterns in the text data and make accurate predictions for the next word in a sequence.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For any questions or issues, please contact [nitish.campusx@gmail.com](mailto:nitish.campusx@gmail.com).
```

Would you like to make any modifications or additions to this draft?
