# Smart-Market-Intelligence
It is an AI‑driven workflow designed to compare products across competing platforms such as Flipkart and Amazon. It automates the collection of product data, including prices, specifications, and customer reviews, and transforms this raw information into structured, goal‑aware reports. The system highlights pricing differences, identifies recurring customer complaints, and applies accurate sentiment analysis even for long and complex review texts.
To support decision‑makers, the agent provides interactive filtering, enabling dynamic exploration of insights tailored to specific business objectives like growth, margins, or customer retention. Reports are generated with citations to ensure transparency and credibility. Built with Python and integrated with TinyFish’s Web Agent API, the solution combines web automation, sentiment analysis, and modular reporting into a scalable decision‑support tool.
This project demonstrates how AI agents can bridge technical depth with business impact, empowering enterprises to act decisively in competitive market

Methods Used


1. Data Collection & Integration
  - Automated extraction of product listings, prices, and reviews from Flipkart and Amazon using web agent APIs.
  - Structured JSON responses stored and processed with Python libraries (pandas, numpy).
2. Data Preprocessing
  - Cleaning large review datasets (removing duplicates, normalizing text, handling emojis and special characters).
  - Tokenization and stop‑word removal for efficient text analysis.
3. Sentiment Analysis
  - Applied NLP pipelines to classify reviews into positive, negative, or neutral sentiment.
  - Special handling for long texts using transformer‑based models to preserve context.
4. Competitive Gap Analysis
  - Price comparison algorithms to detect gaps and opportunities.
  - Frequency analysis of recurring complaints to highlight product weaknesses.
5. Interactive Reporting
  - Modular reporting with filters for growth, margins, and retention objectives.
  - Goal‑aware outputs with citations for transparency.

🤖 Models Used


1. Pretrained Transformer Models (e.g., BERT, DistilBERT, RoBERTa)
  - For sentiment analysis and contextual understanding of long reviews.
2. Text Classification Models
  - Logistic Regression / SVM baselines for quick comparisons.
3. Clustering Models (e.g., K‑Means)
  - To group recurring complaints and detect common themes.
4. Rule‑based Price Comparison
  - Lightweight algorithms to highlight pricing differences across platforms.



