# Sentiment Analysis of Product Reviews

## Project Description

This project performs sentiment analysis on product reviews to classify customer feedback as **Positive**, **Negative**, or **Neutral** using the VADER sentiment analyzer. The goal is to uncover overall sentiment trends, identify common themes in complaints via topic modeling, and provide actionable insights to improve product quality and marketing strategies.

---

## Dataset Overview

- **Source:** Product reviews dataset containing text feedback from customers.  
- **Key Columns:**  
  - `ReviewText`: The actual text of the review  
  - `SentimentCategory`: Sentiment label assigned by the analyzer (Positive/Negative/Neutral)  
  - `ProductID`: Identifier for each product  
  - `ReviewDate`: Date when the review was posted  

---

## Step-by-Step Project Workflow

1. **Data Loading and Exploration**  
   - Imported dataset using pandas.  
   - Checked for missing or duplicate values and cleaned data as needed.  

2. **Text Preprocessing**  
   - Lowercased text, removed punctuation and stopwords.  
   - Applied tokenization and lemmatization for normalization.  

3. **Sentiment Analysis**  
   - Used VADER sentiment analyzer to calculate polarity scores.  
   - Classified reviews into Positive, Negative, or Neutral based on compound score thresholds.  

4. **Exploratory Data Analysis (EDA)**  
   - Visualized sentiment distribution via bar charts.  
   - Generated word clouds for positive and negative reviews to highlight frequent terms.  
   - Analyzed sentiment trends over time and across products.  

5. **Topic Modeling (Optional but Recommended)**  
   - Applied Latent Dirichlet Allocation (LDA) on negative reviews to discover common complaint themes.  
   - Extracted 5 main topics with keywords indicating issues like product quality, pricing, and customer service.  

6. **Insight Generation and Reporting**  
   - Summarized sentiment distribution and key themes.  
   - Highlighted major pain points and strengths from customer feedback.  
   - Provided actionable recommendations for product and marketing teams.  

---

## Project Deliverables

- **Jupyter Notebook:** Complete pipeline covering preprocessing, sentiment analysis, EDA, and topic modeling.  
- **Report:** Summary of sentiment distribution, key themes, word clouds, and actionable insights.  
- **Presentation:** Slides summarizing methodology, findings, and recommendations.  

---

## Technologies Used

- Python libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk` (VADER), `gensim` (LDA), `wordcloud`  
- Jupyter Notebook for development and analysis  
- Git and GitHub for version control and sharing  



#Contact
Mohsin Khan
Email: mohsinkhanmk0085@gmail.com
GitHub: Mohsin97-hub

