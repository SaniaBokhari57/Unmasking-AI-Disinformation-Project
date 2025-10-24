# Unmasking-AI-Disinformation-Project

**Sentiment and Theme Analysis from the AI Incident Database**

### By Syeda Sania Bokhari 

---

## Business Context
The project investigates **AI-driven disinformation incidents**  including misuse of chatbots, deepfakes, and automated propaganda using the **AI Incident Database (AIID)**.  
With rising governance and accountability concerns, this study aims to uncover **how narratives around AI misuse evolve over time** and **which entities drive public sentiment**.

---

## Research Objectives
1. **Extract Sentiment:** Classify incident narratives as positive, neutral, or negative.  
2. **Identify Themes:** Apply **BERTopic** to uncover recurring disinformation patterns.  
3. **Analyze Trends:** Track how sentiment and topics evolve across years and entities (e.g., governments, platforms, media).  

---

## Dataset
- **Source:** AI Incident Database (AIID)  
- **Period Covered:** 2014–2024  
- **Filtered Subset:** Incidents explicitly linked to misinformation or manipulation  
- **Key Entities:** AI, Google, Meta, Microsoft, Russia, U.S.  

---

## Methodology
1. **Data Cleaning & Filtering** – Remove irrelevant cases; tokenize and lemmatize text.  
2. **Sentiment Analysis** – Compute polarity using VADER/TextBlob.  
3. **Topic Modeling** – Use **BERTopic** for interpretable theme extraction.  
4. **Predictive Modeling** – Build a **TF-IDF + Logistic Regression** classifier to predict sentiment.  
5. **Visualization** – Word clouds, entity frequency plots, and sentiment-over-time charts.  

---

## Key Findings
- **Sentiment skew:** Slightly negative overall (avg polarity ≈ −0.05).  
- **Peaks:** Optimistic tone in **2016 & 2021**; drop in **2019–2020** during misinformation scandals.  
- **Themes identified:**
  - Chatbots & platform misuse  
  - Voice & content manipulation  
  - AI-generated misinformation  
  - Surveillance & robotics criticism  
- **Model accuracy:** 0.625 (baseline TF-IDF + Logistic Regression)

---

## Managerial Insights
- **Drivers of concern:** Social bots, data misuse, and reputational risk.  
- **Action Plan:** Periodic text-mining of AI incident logs for early risk alerts.  
- **Governance Takeaway:** Transparent and standardized incident reporting taxonomy.  
- **Policy Focus:** Encourage audits, transparency initiatives, and early detection systems.  

---

## Technologies Used
- Python (Pandas, NumPy, scikit-learn, BERTopic, NLTK, TextBlob, Matplotlib, Seaborn)
- Jupyter Notebook  
- Excel Dataset

---


