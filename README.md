# Resume Ranking System

This project implements a Resume Ranking System that scores resumes based on a given job description using Natural Language Processing (NLP) techniques and a Random Forest Regressor.

## Project Overview

The Resume Ranking System analyzes resumes and scores them based on their relevance to a provided job description. It employs NLP techniques for text preprocessing and utilizes a Random Forest Regressor to predict scores.

## Dataset

The dataset consists of resumes and corresponding job descriptions. The resumes were preprocessed to extract key features, and each resume was assigned a score indicating its relevance to the job description.

## Technologies Used

- Python
- Natural Language Toolkit (nltk)
- Scikit-learn
- Pandas
- NumPy
- Matplotlib (for visualization)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mmanikandan281/resume-ranking-system.git
   cd resume-ranking-system
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare the dataset and ensure it is in the correct format.
2. Run the script to preprocess the data, train the model, and evaluate the performance:
   ```bash
   python resume_ranking.py
   ```
3. The model will output resume scores and evaluation metrics.

## Model Training and Evaluation

- **Text Preprocessing:** Tokenization, stop word removal, and TF-IDF vectorization.
- **Model:** Random Forest Regressor.
- **Evaluation:** The model was evaluated using metrics such as Mean Squared Error (MSE) and R-squared (R2) score.

## Results

The model achieved satisfactory performance with the following metrics:

- Mean Squared Error: *value*
- R-squared: *value*

##If Working in collab
2. Collab Link:
   ```bash
   https://colab.research.google.com/drive/1d7qfvbN5utqV-IzdfnmQ95_tsl8rUF28?usp=sharing
   ```
## Future Work

- Experimenting with other models like Gradient Boosting or Neural Networks.
- Enhancing feature extraction by using BERT or GPT embeddings.
- Deploying the system as a web application.

## Contributors

- Manikandan M (@mmanikandan281)

## License

This project is licensed under the MIT License.

---

Feel free to modify the content and add any missing details. 🚀 Let me know if you want to add more sections or refine any part!

Thank You By Manikandan M
