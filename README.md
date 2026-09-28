# Hiver Customer Support Conversation Analysis

This project focuses on understanding, cleaning, and structuring customer-support conversations from the AppleSupport portion of the Customer Support on Twitter dataset.

The current stage of the project focuses on **data understanding, conversation reconstruction, cleaning, and validation**.

---

## Project Objective

The goal is to transform raw customer-support tweets into a structured conversation-level dataset that can later be used for:

- Customer support conversation analysis
- Response analysis
- Customer intent classification
- Support automation
- Machine learning / NLP tasks
- Identifying customer issues and support responses

---

## Dataset

The project uses customer-support conversations involving `AppleSupport`.

The raw data contains individual tweets with information such as:

- Tweet ID
- Author ID
- Conversation ID
- Timestamp
- Inbound / outbound indicator
- Tweet text
- Response relationships

The raw tweets are reconstructed into complete conversations using their conversation and response relationships.

> The original dataset is not included in this repository. Please obtain the dataset separately and place it inside the appropriate `data/` directory.

---

## Project Structure

```text
hiver_project/
│
├── data/
│   └── raw dataset files
│
├── notebooks/
│   └── 01_data_understanding.ipynb
│
├── output/
│   └── apple_conversations_clean.csv
│
├── src/
│
├── .gitignore
└── README.md