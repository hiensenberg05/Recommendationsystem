# 📊 Machine Learning Based Recommendation Systems

This repository showcases multiple machine learning techniques for building recommendation systems using real-world data. It explores both **content-based filtering** and **collaborative filtering** approaches to suggest items to users based on their preferences or similarity to other users.

---

## 📌 Project Highlights

- 🧠 **Recommendation Models Implemented:**
  - Content-Based Filtering using cosine similarity
  - User-User Collaborative Filtering
  - Item-Item Collaborative Filtering
  - Popularity-Based Recommendation
  - SVD (Singular Value Decomposition) using `Surprise` library

- 📚 **Dataset Used:**
  - [MovieLens 100k Dataset](https://grouplens.org/datasets/movielens/100k/): Contains 100,000 ratings from 943 users on 1682 movies.

- 🔧 **Tools and Libraries:**
  - Python, Pandas, NumPy, Scikit-learn, Surprise, Matplotlib, Seaborn

---

## 🗂️ Repository Structure

```
recommendation-systems-ml/
├── recommendationsystems.ipynb   # Core notebook with models and visualizations
├── README.md                     # Project overview and instructions
└── data/                         # (Optional) Place to store dataset files
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/recommendation-systems-ml.git
cd recommendation-systems-ml
```

### 2. Install Dependencies

Use pip to install the required packages:

```bash
pip install -r requirements.txt
```

> If `requirements.txt` isn't available, manually install:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn scikit-surprise
```

---

## 📈 Models & Evaluation

### ✅ Content-Based Filtering

- Uses TF-IDF or CountVectorizer (e.g., on genres or titles).
- Computes cosine similarity between items.
- Recommends similar movies to a given movie.

### 👥 User-User Collaborative Filtering

- Based on user similarity (cosine or Pearson correlation).
- Predicts how a user might rate an unseen movie by looking at similar users' ratings.

### 🎬 Item-Item Collaborative Filtering

- Looks for similarities between items instead of users.
- Typically more stable as user preferences vary more than items.

### 📊 Popularity-Based Recommendation

- Recommends the most watched or highly rated movies.

### 🔍 Matrix Factorization with SVD

- Leverages the `Surprise` library to implement SVD.
- Efficient in dealing with sparse rating matrices.

---

## 📊 Sample Results

- Top-5 movie recommendations for selected users.
- RMSE and MAE values for collaborative models.
- Heatmaps and similarity matrices visualized.

---

## 🧠 Learnings and Challenges

- Handling sparse datasets using pivot tables.
- Balancing exploration (popular items) and personalization.
- Understanding trade-offs between different recommender models.

---

## 🙌 Acknowledgements

- [MovieLens](https://grouplens.org/datasets/movielens/)
- [Surprise Library](http://surpriselib.com/)

---

## 📬 Contact

For questions or collaborations:

**Uttkarsh Solanki**  
📧 uttkarsh2003.solanki@gmail.com 
📌 GitHub: [@hiensenberg05](https://github.com/hiensenberg05)

---

## 🏷️ License

This project is open-sourced under the MIT License.

