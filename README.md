# SMS-Spam-Classifier
This project is an SMS spam classifier that uses Natural Language Processing (NLP) techniques to detect spam messages. It includes a comprehensive comparison of various machine learning models to determine the best-performing algorithm, ultimately selecting Naive Bayes for its simplicity and effectiveness

## Features
- **Natural Language Processing (NLP)**: The project preprocesses SMS data, including tokenization, stopword removal, and TF-IDF vectorization.
- **Model Comparison**: We compared multiple machine learning models, including Naive Bayes, Decision Trees, and Support Vector Machines (SVM), and chose Naive Bayes for its simplicity and effectiveness.
- **Streamlit Deployment**: The project includes a Streamlit-based web application for easy interaction with the spam classifier.

## Project Structure
- `spam.csv`: Contains the dataset used for training and testing the classifier.
- `sms-spam-classifier.ipynb`: Contains Jupyter Notebook with code for data preprocessing, model training, and model comparison.
- `app.py`: The Streamlit application script for deploying the spam classifier.
- `requirements.txt`: Lists the dependencies needed to run the project.

## Setup Instructions
To set up the project on your local machine, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
2. Create virtual environment:
   
   python -m venv venv
   source venv/bin/activate  # For Linux/macOS
   venv\Scripts\activate  # For Windows
4. Install required packages:
   pip install -r requirements.txt
5. Launch Streamlit app:
   streamlit run app.py

## Usage
Once the Streamlit application is running, you can use the web interface to input an SMS message and get a prediction on whether it's spam or not. The classifier will output "Spam" or "Not Spam" based on the trained model's prediction.

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please open an issue or submit a pull request. Make sure to follow the existing code style and include appropriate documentation with your changes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
