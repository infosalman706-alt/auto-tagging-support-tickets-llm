# Auto Tagging Support Tickets Using LLM

## 📌 Project Overview

This project automatically classifies free-text support tickets into predefined categories using Large Language Models (LLMs). It demonstrates **Zero-Shot Learning**, **Few-Shot Learning**, and compares their performance while predicting the **Top 3 most probable tags** for each support ticket.

---

## 🎯 Objective

The goal of this project is to automate the tagging of customer support tickets using LLMs, reducing manual effort and improving the efficiency of support teams.

---

## 🚀 Features

- Zero-Shot Classification using Hugging Face Transformers
- Few-Shot Prompt Engineering
- Top 3 Predicted Tags for each support ticket
- Performance Comparison (Zero-Shot vs Few-Shot)
- Accuracy Evaluation
- Export Predictions to CSV

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- Facebook BART Large MNLI
- Pandas
- Scikit-learn
- PyTorch

---

## 📂 Project Structure

```
auto-tagging-support-tickets-llm/
│
├── Task5_Auto_Tagging_Support_Tickets.ipynb
├── support_tickets.csv
├── zero_shot_results.csv
├── few_shot_results.csv
├── requirements.txt
├── README.md
└── images/
```

---

## 📊 Dataset

The project uses a free-text support ticket dataset containing customer support requests and their corresponding categories.

Example:

| Ticket | Category |
|---------|----------|
| Cannot login to my account | Login Issue |
| Forgot my password | Password Reset |
| Printer is offline | Printer Issue |
| Internet is not working | Network Problem |

---

## 🔍 Workflow

1. Install required libraries
2. Load the support ticket dataset
3. Define candidate labels
4. Perform Zero-Shot Classification
5. Apply Few-Shot Prompting
6. Predict the Top 3 Tags
7. Evaluate model performance
8. Export results

---

## 📈 Results

The model predicts:

- Top 1 Tag
- Top 2 Tag
- Top 3 Tag

Performance is evaluated using:

- Accuracy Score
- Classification Report

---

## 💻 Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/auto-tagging-support-tickets-llm.git
```

Move into the project directory:

```bash
cd auto-tagging-support-tickets-llm
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Open the notebook in **Google Colab** or **Jupyter Notebook** and execute all cells in sequence.

---

## 📷 Sample Output

| Ticket | Top 1 | Top 2 | Top 3 |
|---------|-------|-------|-------|
| Forgot password | Password Reset | Login Issue | Account Issue |
| WiFi is not working | Network Problem | Hardware | Other |
| Printer offline | Printer Issue | Hardware | Software |

---

## 📚 Skills Demonstrated

- Prompt Engineering
- Large Language Models (LLMs)
- Zero-Shot Learning
- Few-Shot Learning
- Text Classification
- Multi-Class Prediction
- Model Evaluation
- Natural Language Processing (NLP)

---

## 📌 Future Improvements

- Fine-tune BERT or DistilBERT on a labeled support ticket dataset.
- Deploy the model using Streamlit or Flask.
- Integrate with a real-time helpdesk system.
- Add confidence score visualization.

---

## 👨‍💻 Author

**Salman Khan**

AI & Machine Learning Enthusiast

GitHub: https://github.com/infosalman706-alt

---

## ⭐ Acknowledgements

- Hugging Face Transformers
- Facebook BART Large MNLI
- Scikit-learn
- Google Colab
