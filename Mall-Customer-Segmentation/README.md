# Project: Customer Segmentation & Behavioral Strategy 🛍️

## 📌 Business Case
In modern retail, a "one-size-fits-all" marketing approach is a primary cause of wasted ad spend. A high-income customer who hunts for bargains requires a vastly different marketing approach than a low-income impulse buyer. This project utilizes **Unsupervised Machine Learning** to uncover hidden purchasing patterns and segment customers into actionable business personas.

## 🎯 Objective
- **Goal:** Segment a retail customer base using purchasing behavior and income data to design highly targeted marketing strategies.
- **Problem Type:** Unsupervised Learning (Clustering).
- **Dataset:** Mall Customers Dataset.

## 🛠️ Technical Workflow
1. **Data Engineering:** Sanitized raw text features into Standard Case for executive-level reporting.
2. **Mathematical Segmentation:** Deployed the **Elbow Method** to mathematically define the optimal number of clusters (K=5), followed by **K-Means Clustering**.
3. **Strategic Mapping (PCA):** Leveraged **Principal Component Analysis (PCA)** to distill a multi-dimensional feature space into an interpretable 2D strategic landscape.
4. **High-Fidelity Visualization:** Used `Plotly` to build interactive 3D cluster visualizations and integrated a custom Python automation script to generate 360-degree rotating GIFs for stakeholder presentations.

## 📊 Strategic Insights & Personas
The algorithm successfully isolated 5 distinct behavioral segments:
- **Whales (High Income, High Spend):** Prime targets for VIP loyalty programs and luxury marketing.
- **Careful Spenders (High Income, Low Spend):** The biggest hidden opportunity. Highly resistant to cheap discounts; require marketing built on brand trust, durability, and premium value.
- **Impulse Buyers (Low Income, High Spend):** Best audience for flash sales, BOGO offers, and high-urgency social media campaigns.
- **Average Joes & Budget Conscious:** Core audience for standard newsletters and clearance events, ensuring customer acquisition costs (CAC) remain low.

## 💻 Tech Stack
- **Languages:** Python
- **Libraries:** Scikit-Learn (K-Means, PCA), Plotly (Interactive 3D Visuals), Pandas, Seaborn
- **Extras:** Pillow (`PIL`) & `io` for automated GIF generation.
