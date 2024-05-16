# SMS Spam Detection with Naive Bayes

This repository contains the code and documentation for a machine learning project focused on detecting spam messages within SMS text data. The project utilizes the SMS Spam Collection v.1 dataset and implements Naive Bayes classifiers with Bag-of-Words (BoW) and TF-IDF vectorization.

## Dataset

The SMS Spam Collection v.1 dataset includes 5,574 English text messages, labeled as 'ham' (legitimate) or 'spam'. It is a public set of messages compiled from various sources for the purpose of spam research.

## Project Structure

The project is organized as follows:

- `SpamDS.xlsx`: The dataset file in Excel format.
- `spam_detector.ipynb`: Jupyter notebook containing the code and analysis.
- `requirements.txt`: A list of Python dependencies necessary to run the project.

## Installation

To set up the project environment, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/Vaquita-AI/SMS-Spam-Detection.git
   ```
2. Navigate to the project directory:
   ```
   cd sms-spam-detection
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

Open the `spam_detector.ipynb` notebook in a Jupyter environment to view the code and analysis. The notebook is annotated with comments for clarity and understanding.

## Methodology

The project includes the following steps:

1. Data Preprocessing: Tokenization, lowercasing, removing stop words, and stemming.
2. Feature Extraction: Vectorization using BoW and TF-IDF methods.
3. Model Training: Training Naive Bayes classifiers with the extracted features.
4. Model Evaluation: Assessing performance using accuracy, precision, recall, and F1 score.
5. Prediction: Using the trained models to classify new text messages.

## Results

The BoW model achieved an accuracy of 98%, with precision, recall, and F1 score all above 94%. The TF-IDF model showed slightly lower performance, particularly in recall. The BoW model was found to be more reliable for spam detection in this dataset.

## Contributions

Contributions to this project are welcome. Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

## Contact

For any queries or discussions regarding this project, please open an issue in the repository or contact the maintainers directly.

## Acknowledgments

- The creators of the SMS Spam Collection v.1 dataset.
Vaquita-AI on GitHub
- Contributors to the Python libraries used in this project.
