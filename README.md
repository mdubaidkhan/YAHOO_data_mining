# 📌 Yahoo Answers NLP Project

This project focuses on **large-scale topic classification** using natural language processing (NLP), developed as part of a **Data Mining & Analysis course**.  
The primary dataset is the **Yahoo Answers Topic Classification Dataset** from Kaggle, and the project combines classical text mining approaches with modern techniques like transformer-based models and advanced representation learning beyond the course curriculum.

---

## 🚀 Project Overview

The Yahoo Answers dataset contains millions of question–answer pairs labeled by topic. This project aims to:

- Select a dataset that supports both course-aligned techniques and advanced NLP methods  
- Conduct thorough **Exploratory Data Analysis (EDA)**  
- Identify real-world data challenges such as noise, missingness, and class imbalance  
- Generate insights and research questions for modeling  
- Build a **scalable and reproducible NLP pipeline**  
- Present work professionally for both academic and industry audiences

---

## 📊 Dataset Details

**Dataset Name:** Yahoo Answers Topic Classification Dataset  
**Source:** [Kaggle Dataset](https://www.kaggle.com/datasets/yacharki/yahoo-answers-10-categories-for-nlp-csv)  

**Type:** Large-scale labeled text classification dataset

### Structure
Each record contains:  
- `question`: User-submitted question text  
- `answer`: Corresponding answer text  
- `label`: Topic category (integer class ID)

### Size
- Training set: ~1.4 million samples  
- Test set: ~60,000 samples  
- Classes: 10 topic categories  
- Vocabulary: Large, sparse, and long-tail distribution

### Characteristics
- Unstructured natural language text  
- Multi-class classification  
- Noisy user-generated content (typos, abbreviations, informal grammar)  
- High lexical diversity with semantic overlap between categories

### Key Challenges
- Overlapping class semantics  
- Vocabulary sparsity and long-tail token distribution  
- Noise from informal text  
- Variable document lengths

---

## 🛠 Getting Started

### Prerequisites
- Python 3.8 or higher  
- pip or conda environment

### Installation

```bash
git clone https://github.com/mdubaidkhan/YAHOO_data_mining.git
cd YAHOO_data_mining
pip install -r requirements.txt
# YAHOO_data_mining