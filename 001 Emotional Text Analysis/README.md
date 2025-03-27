# **Emotional Text Analysis: Natural Language Preprocessing**

<div align="center">  

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  [![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://python.org)  [![NLP](https://img.shields.io/badge/Natural%20Language%20Processing-Text%20Analysis-green)](https://en.wikipedia.org/wiki/Natural_language_processing)  [![Sentiment Analysis](https://img.shields.io/badge/Sentiment%20Analysis-VADER-orange)](https://github.com/cjhutto/vaderSentiment)  [![Text Mining](https://img.shields.io/badge/Text%20Mining-Emotion%20Detection-blue)](https://en.wikipedia.org/wiki/Text_mining)  [![Pandas](https://img.shields.io/badge/Pandas-2.0-darkblue?logo=pandas)](https://pandas.pydata.org)  [![NumPy](https://img.shields.io/badge/NumPy-1.20%2B-blue?logo=numpy)](https://numpy.org)  [![NLTK](https://img.shields.io/badge/NLTK-3.8%2B-green?logo=nltk)](https://www.nltk.org)  [![spaCy](https://img.shields.io/badge/spaCy-3.0%2B-lightblue?logo=spacy)](https://spacy.io)  [![Matplotlib](https://img.shields.io/badge/Matplotlib-3.0%2B-blue?logo=matplotlib)](https://matplotlib.org)  [![Seaborn](https://img.shields.io/badge/Seaborn-0.12%2B-darkred?logo=seaborn)](https://seaborn.pydata.org)  [![WordCloud](https://img.shields.io/badge/WordCloud-1.8%2B-yellow)](https://github.com/amueller/word_cloud)  [![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-1.2+-orange?logo=scikit-learn)](https://scikit-learn.org)  [![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange?logo=tensorflow)](https://tensorflow.org)  [![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org) [![GitHub](https://img.shields.io/badge/GitHub-Jabulente-black?logo=github)](https://github.com/Jabulente)  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Jabulente-blue?logo=linkedin)](https://linkedin.com/in/jabulente-208019349)  [![X (Twitter)](https://img.shields.io/badge/X-@Jabulente-black?logo=x)](https://x.com/Jabulente)  [![Instagram](https://img.shields.io/badge/Instagram-@Jabulente-purple?logo=instagram)](https://instagram.com/Jabulente)  [![Threads](https://img.shields.io/badge/Threads-@Jabulente-black?logo=threads)](https://threads.net/@Jabulente) [![TikTok](https://img.shields.io/badge/TikTok-@Jabulente-teal?logo=tiktok)](https://tiktok.com/@Jabulente)  [![Email](https://img.shields.io/badge/Email-jabulente@hotmail.com-red?logo=gmail)](mailto:Jabulente@hotmail.com)  

</div>

<hr>

## Overview
This repository provides an **exploratory analysis and sentiment classification** of user comments. The project focuses on **performing sentiment analysis across different emotional categories**, identifying patterns in textual data, and visualizing the distribution of sentiments. By leveraging **VADER Sentiment Analysis** and text preprocessing techniques, this project aims to extract insights into how users express different emotions and the sentiment polarity (positive, neutral, negative) of their comments.


![Sentiment Analysis Chart](Resources/plot.png)

---

## Features

- **Exploratory Data Analysis (EDA)**: Analyze trends and distributions in the dataset.
- **Text Preprocessing**: Clean, tokenize, and normalize text for accurate sentiment analysis.
- **Sentiment Classification**: Categorize comments as **positive, neutral, or negative** using **VADER**.
- **Emotion-Based Sentiment Analysis**: Compare sentiment scores across different emotion classes (e.g., anger, joy, sadness).
- **Visualizations**:
  - **Bar charts** for sentiment distribution.
  - **Word clouds** for commonly used words within sentiment categories.
  - **Phrase frequency analysis** for detecting key terms.
- **Adaptable Pipeline**: Easily apply the workflow to different comment-based datasets.

---

## Applications
This project is useful for:

- **Social Media Monitoring**: Identify sentiment trends in online comments.
- **Customer Feedback Analysis**: Evaluate customer sentiments towards products or services.
- **Public Opinion Analysis**: Assess sentiment variations across topics and user-generated content.
- **General Text-Based Sentiment Exploration**: Explore sentiment tendencies in any collection of comments.

---

## Technologies Used
- **Python**
- **NLTK (Natural Language Toolkit)** for text processing
- **VADER (Valence Aware Dictionary and sEntiment Reasoner)** for sentiment classification
- **Matplotlib & Seaborn** for visualizations
- **Pandas & NumPy** for data handling
- **WordCloud** for text-based visual representation

---

## Installation & Setup
To run this project, follow these steps:

### Prerequisites
Ensure you have **Python 3.7+** and install the required libraries:
```bash
pip install -r requirements.txt
```

Here's a more concise and action-oriented version:

---

### Running the Analysis

1. Clone the repository:
   ```bash
   [git clone https://github.com/your-username/sentiment-analysis.git](https://github.com/Jabulente/Natural-Language-Preprocessing-.git)
   cd 001-Emotional-Text-Analysis
   ```

2. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```

3. **Open the Analysis Notebook**:
   - Open `Emotional Text Analysis (NLP).ipynb`

4. **Run All Cells**:
   - Use `Kernel > Restart & Run All` to execute the full pipeline

4. **View Results**:
   - Interactive visualizations will render in the notebook
   - Exported charts save to `Visualizations/`
  

## Dataset
The dataset consists of user comments with the following columns:
- **Text**: The user-generated comment.
- **Emotion Label**: The general emotional category of the comment.

A sample dataset is included, but you can use your own dataset for custom analysis.

---

## Future Enhancements
- **Real-Time Sentiment Tracking** for live comment analysis.
- **Advanced NLP Models** (e.g., Transformer-based models for improved sentiment classification).
- **Multi-Language Support** to expand beyond English text analysis.

---

## Contributing
Contributions are welcome! Feel free to fork the repository, create feature branches, and submit pull requests. For major changes, open an issue to discuss proposed modifications.

---

## License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## Contact

This analysis was performed by **Jabulente**, a passionate and dedicated data scientist with a strong commitment to using data to drive meaningful insights and solutions. For inquiries, collaborations, or further discussions, please feel free to reach out via.  

    
<div align="center"> 
  
[![GitHub](https://img.shields.io/badge/GitHub-Jabulente-black?logo=github)](https://github.com/Jabulente)  [![LinkedIn](https://img.shields.io/badge/LinkedIn-Jabulente-blue?logo=linkedin)](https://linkedin.com/in/jabulente-208019349)  [![X (Twitter)](https://img.shields.io/badge/X-@Jabulente-black?logo=x)](https://x.com/Jabulente)  [![Instagram](https://img.shields.io/badge/Instagram-@Jabulente-purple?logo=instagram)](https://instagram.com/Jabulente)  [![Threads](https://img.shields.io/badge/Threads-@Jabulente-black?logo=threads)](https://threads.net/@Jabulente) [![TikTok](https://img.shields.io/badge/TikTok-@Jabulente-teal?logo=tiktok)](https://tiktok.com/@Jabulente)  [![Email](https://img.shields.io/badge/Email-jabulente@hotmail.com-red?logo=gmail)](mailto:Jabulente@hotmail.com)  
</div>
<hr>
