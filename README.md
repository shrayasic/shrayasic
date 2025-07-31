# Hi there, I'm Shraeyaa! 👋


---

## 🚀 About Me
🎓 **B.E. in Information Technology**  
Vivekanand Education Society’s Institute of Technology · CGPA: **9.06** · 2022–2026 (Expected)

💻 **Aspiring Full-Stack Developer** with skills in:  
- **Languages**: Java, Python
- - **Frameworks & Libraries**: MERN 
- **Databases**: MySQL, MongoDB.
- **Tools & DevOps**: Git, GitHub, Jenkins (Basics), Docker (Basics)
- **Industry Knowledge**: Data Structures & Algorithms, RESTful APIs.
🌱 Currently exploring **cloud technologies** and diving deeper into **backend performance optimization**.

---

## 🛠️ Projects
### 1. [TribeVibe – Community Platform](#) *(MongoDB, Express.js, React.js, Node.js)*  
A MERN stack web app enabling:  
- User posts, comments, and topic-based discussions.  
- ML-based recommendations (content-based & collaborative filtering using TF-IDF, KNN).  
- Spam detection using SVM and Random Forest algorithms.

### 2.ESG Risk Analysis & Prediction https://github.com/shrayasic/esg-risk-analysis/tree/main 📈

This repository contains my data science project focused on analyzing and predicting company-level **Total ESG Risk Scores**.

🎯 Project Goals

- **Ethical Prediction**: Build a robust and reliable predictive model for ESG risk, ensuring there is no "circularity" by excluding direct component risk scores (Environmental, Social, Governance) from the final feature set. This ensures the model is truly predictive and not just a linear combination of its inputs.
- **Deep Analytical Insights**: Go beyond simple prediction to understand the underlying drivers of ESG risk, including industry-specific trends, high-risk relationships, and company-level risk profiles.
- **Full-Stack Implementation**: Demonstrate a complete data science workflow, from data ingestion and cleaning to model training and deployment.

🚀 Methodology and Techniques

Data Pipeline & Preprocessing
- [cite_start]**Source**: Kaggle "SP 500 ESG Risk Ratings.csv" dataset[cite: 25].
- [cite_start]**Cleaning**: Handled missing values by imputing means/medians for numerical scores and dropping rows for critical categorical data[cite: 168, 210, 212].
- [cite_start]**Data Storage**: Ingested and stored cleaned data in a MySQL database, showcasing a structured approach to data management[cite: 235, 253].

Feature Engineering
- [cite_start]**Ethical Feature Set**: Created a unique set of non-circular features to predict `total_esg_risk_score`[cite: 1651, 1655].
- [cite_start]**Risk Indicators**: Developed binary flags for high-risk scores (`env_high`, `soc_high`, etc.) and outliers (`env_outlier`, `soc_outlier`, etc.)[cite: 1442, 1589].
- [cite_start]**Contextual Features**: Engineered industry-level features like average controversy scores and risk-based volatility flags to provide a comparative context for each company[cite: 1721, 1726, 1731, 1736].
- [cite_start]**Composite Metrics**: Designed new features like `governance_deficit_ratio` and `controversy_flag_combo` to capture complex risk interactions[cite: 1787, 1792].

Analytical & Machine Learning
- [cite_start]**Exploratory Data Analysis (EDA)**: Utilized a wide range of plots (histograms, heatmaps, box plots) to analyze data distributions, correlations, and outliers[cite: 986, 1004, 1015]. [cite_start]Found strong correlations between `total_esg_risk_score` and individual components (`environment_risk_score` and `social_risk_score`)[cite: 904, 905].
- **Dimensionality Reduction & Clustering**: Applied **PCA** to standardize and reduce the dimensionality of numerical features. [cite_start]Used a **Scree Plot** to determine that the first two principal components explain a significant portion of the variance[cite: 1305, 1310, 1313]. [cite_start]Subsequently, used **K-Means clustering** with a **Silhouette Score** to identify **3 optimal clusters** of companies with similar ESG risk profiles[cite: 1381, 1386, 1395].
- [cite_start]**Association Rule Mining**: Employed the **Apriori algorithm** to discover relationships between high-risk flags, finding rules like `(controversy_high) => (soc_high)` with high confidence[cite: 1446, 1447].
- [cite_start]**Predictive Modeling**: Trained an **XGBoost Regressor** model, leveraging the engineered features to predict the `total_esg_risk_score`[cite: 1661, 1662].

📈 Results and Conclusions

- [cite_start]The XGBoost model achieved a strong performance with an **R² score of 0.8685** and a **Mean Absolute Error (MAE) of 1.8064** on the test set, demonstrating high predictive accuracy[cite: 1881, 1882, 1883, 1884].
- [cite_start]Feature importance analysis highlighted `controversy_social_product`, `governance_deficit_ratio`, and `controversy_env_product` as the most influential features, proving the value of custom-engineered metrics[cite: 1930, 1931, 1932].
- The project successfully demonstrated a robust, ethical, and insightful approach to ESG risk analysis, providing a foundation for a powerful and interpretable predictive tool.

### 2. CineRate – Movie & Cinephile App *(Flutter, Firebase)*  
A cross-platform app with:  
- Firebase Auth and Firestore for user login and review storage.  
- Real-time movie data integration via TMDB and RapidAPI.  
- Curated cinema-related video feeds and engaging UI/UX.

### 3. Resourcify – Resource Management System (Flask, React, MongoDB)
A web app for managing topics and resources with:
- Secure user authentication via JWT tokens.
- Topic and subtopic creation, update, and deletion.
- File uploads to Cloudinary for resource management.
- Responsive UI built with React and Tailwind CSS.
Technologies Used
- **Backend**: Flask, Flask-CORS, Flask-PyMongo, Flask-Bcrypt, Flask-JWT-Extended, MongoDB, Cloudinary, dotenv.
- **Frontend**: React, Vite, Tailwind CSS, Axios.


### 4. InvestHub – Stock Market Analysis Platform *(Python, Tkinter, MySQL)*  
A GUI-based platform offering:  
- Stock analysis, charting, comparison, and real-time notifications.  
- News aggregation and educational modules for enhanced user engagement.  

---

## 👨‍💻 Work Experience
### **Web Development Intern** – *Unwind NGO* *(Jan 2025 – Feb 2025)*  
- Built a MERN stack platform for role-based access for therapy session booking and therapist profile management.
- Designed a clean, user-friendly UI/UX with efficient state management and routing logic.

---

## 🌟 Activities and Achievements
- **Finalist – Syrus Hackathon**  
  Ranked among the top 18 teams out of 160+ participants. Built an AI-powered Trade Risk and Finance Profiler with features like HS code extraction, supplier data retrieval, tariff & sanction analysis, and AI-driven insights.  

- **SIH Participant**  
  Participated in the Smart India Hackathon, showcasing innovative solutions to national challenges.

---

## 📫 Let's Connect
- **Email**: [shrayasic@example.com](mailto:shrayasic@example.com)
- **LinkedIn**: [LinkedIn Profile](https://www.linkedin.com/in/shraeyaa-dhaigude-1a572021b/)


---

### 🖤 Fun Fact
When I'm not coding, you'll find me reading books, rescuing animals or watching mundane shows.

---

Feel free to explore my repositories and let's collaborate on exciting projects 🚀.
