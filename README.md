# Grisel_Barrera_FE_ITAI_2373
# 📰 NewsBot Intelligence System 2.0  
**Advanced NLP Integration and Analysis Platform**  
Final Project – ITAI 2373 | Houston Community College  

---

## 📌 Overview  
The **NewsBot Intelligence System 2.0** is an advanced, production-ready **news analysis platform** built using state-of-the-art **Natural Language Processing (NLP)** techniques.  
It expands upon the Midterm NewsBot by integrating **topic modeling**, **multilingual capabilities**, **language model-powered summarization**, and **a conversational query interface** — creating a system ready for real-world applications.  

---

## 🎯 Key Features  
### **Module A – Advanced Content Analysis Engine**  
- Multi-level **article classification** with confidence scores  
- **Topic modeling & trend tracking** using LDA and NMF  
- **Sentiment evolution** over time  
- **Entity relationship mapping** between people, organizations, and events  

### **Module B – Language Understanding & Generation**  
- **Intelligent summarization** of articles  
- **Contextual content enrichment**  
- **Semantic search** using embeddings  
- **Query expansion** for improved search results  

### **Module C – Multilingual Intelligence**  
- Automatic **language detection**  
- **Translation integration** for cross-language access  
- **Cross-lingual analysis** of news coverage  
- Cultural context understanding for global events  

### **Module D – Conversational Interface**  
- **Intent classification** for natural language queries  
- Multi-turn conversation support with **context management**  
- Personalized insights based on user preferences  
- Export capabilities for **reports and visualizations**  

---

## 📂 Repository Structure  
ITAI2373-NewsBot-Final/
├── README.md
├── requirements.txt
├── config/
│ ├── settings.py
│ └── api_keys_template.txt
├── src/
│ ├── data_processing/
│ │ ├── text_preprocessor.py
│ │ ├── feature_extractor.py
│ │ └── data_validator.py
│ ├── analysis/
│ │ ├── classifier.py
│ │ ├── sentiment_analyzer.py
│ │ ├── ner_extractor.py
│ │ └── topic_modeler.py
│ ├── language_models/
│ │ ├── summarizer.py
│ │ ├── generator.py
│ │ └── embeddings.py
│ ├── multilingual/
│ │ ├── translator.py
│ │ ├── language_detector.py
│ │ └── cross_lingual_analyzer.py
│ ├── conversation/
│ │ ├── query_processor.py
│ │ ├── intent_classifier.py
│ │ └── response_generator.py
│ ├── utils/
│ │ └── visualization.py
│ └── evaluation.py
├── notebooks/
│ ├── 01_Data_Exploration.ipynb
│ ├── 02_Advanced_Classification.ipynb
│ ├── 03_Topic_Modeling.ipynb
│ ├── 04_Language_Models.ipynb
│ ├── 05_Multilingual_Analysis.ipynb
│ ├── 06_Conversational_Interface.ipynb
│ └── 07_System_Integration.ipynb
├── tests/
│ ├── test_preprocessing.py
│ ├── test_classification.py
│ ├── test_topic_modeling.py
│ └── test_integration.py
├── data/
│ ├── raw/
│ ├── processed/
│ ├── models/
│ └── results/
├── docs/
│ ├── technical_documentation.md
│ ├── user_guide.md
│ ├── api_reference.md
│ └── deployment_guide.md
└── reports/
├── executive_summary.pdf
├── technical_report.pdf
└── presentation_slides.pdf

---

## 🛠️ Installation & Setup  
### 1️⃣ Clone Repository  
```bash
git clone https://github.com/<YourUsername>/ITAI2373-NewsBot-Final.git
cd ITAI2373-NewsBot-Final
python -m venv venv
source venv/bin/activate    # macOS/Linux
venv\Scripts\activate       # Windows
pip install -r requirements.txt
python src/analysis/topic_modeler.py --input data/processed/articles.csv
python src/language_models/summarizer.py --text "Your article text here"
python src/conversation/query_processor.py --query "Show me positive tech news from this week"
 Technologies Used
Python 3.9+

scikit-learn, gensim – topic modeling, classification

transformers (Hugging Face) – summarization, embeddings

langdetect / fasttext – language detection

googletrans / MarianMT – translation

Flask / Streamlit (optional bonus) – web app interface

matplotlib / seaborn / pyLDAvis – visualizations

📄 Documentation
📂 See the docs/ folder for:

Technical Documentation – architecture, API reference

User Guide – non-technical usage instructions

Deployment Guide – production setup instructions

📈 Business Value
The NewsBot 2.0 platform enables:

Journalists to track breaking trends across languages

Businesses to monitor industry sentiment

Researchers to analyze topic evolution over time

General users to interact with news using natural language

👤 Author
Name: Grisel Barrera 
Course: ITAI 2373 – NLP 
Institution: Houston Community College

