#  GenAI-Driven Product Feedback Miner

##  Project Overview

This project leverages Large Language Models (LLMs) and NLP techniques to mine large-scale app store reviews and extract actionable product insights.  

The system performs automated sentiment analysis, topic clustering, and review summarization to identify recurring product issues, feature requests, and user experience pain points.

The output is structured for business intelligence reporting and executive decision-making.

---

##  Business Objective

Modern product teams receive thousands of user reviews daily. Manually analyzing them is inefficient and unscalable.

This project aims to:

- Automatically detect customer sentiment
- Identify recurring themes and feature requests
- Surface high-impact product issues
- Convert unstructured review text into structured BI-ready insights

---

##  Tech Stack

- Python
- NLP & LLM-based text processing
- Sentence embeddings
- Topic modeling / clustering
- Streamlit (interactive UI)
- pandas
- Power BI (Business Intelligence layer)

---

## 📂 Repository Structure
llm-based-store-reviews-analysis
│
├── data/ # Raw review datasets
├── notebooks/ # Experimentation and modeling notebooks
├── scripts/ # Processing and clustering logic
├── tests/ # Test cases
├── app.py # Interactive Streamlit application
├── .env.example # Environment variable template
└── README.md

---

## 🧠 System Architecture

### 1️⃣ Data Ingestion
App store reviews are loaded from the dataset located in the `data/` directory.

### 2️⃣ NLP & LLM Processing
The pipeline performs:

- Text preprocessing
- Embedding generation
- Topic clustering
- Sentiment classification
- Automated summarization

### 3️⃣ Insight Extraction
The system identifies:

- Most common complaint themes
- Frequently requested features
- Sentiment distribution
- High-impact user pain points

### 4️⃣ Interactive Exploration
`app.py` provides a Streamlit interface to:

- Upload or select datasets
- View clustered topics
- Analyze sentiment distribution
- Explore summarized review themes

---

## 📊 Power BI Integration (Business Intelligence Layer)

To operationalize insights for product stakeholders:

1. Processed review outputs are exported as structured CSV files.
2. The structured dataset includes:
   - Review text
   - Topic label
   - Sentiment label
   - Rating
   - Timestamp
3. Power BI dashboard visualizes:
   - Sentiment trends over time
   - Topic frequency analysis
   - High-volume complaint clusters
   - Feature request prioritization
   - Executive KPI summaries

This enables data-driven roadmap planning and product decision-making.

---

## ▶️ Running the Application

### 1️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```
## 2️⃣ Configure Environment Variables
Create a .env file based on:

.env.example

### 📈 Key Capabilities
Scalable review mining

Automated topic discovery

LLM-enhanced summarization

Sentiment trend detection

BI-ready structured outputs

Interactive product analytics

💼 Business Impact

Reduced manual review analysis effort

Faster identification of critical product issues

Data-backed feature prioritization

Improved user experience decision-making

Executive-ready reporting via Power BI

🔮 Future Enhancements

Real-time API integration with app store data

Automated roadmap recommendation scoring

Advanced BERTopic / transformer-based topic modeling

Deployment via cloud infrastructure
