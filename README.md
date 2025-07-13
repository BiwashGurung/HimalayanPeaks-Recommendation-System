# 🏔️ Himalayan Peaks Recommendation System

This project is a machine learning-based recommendation system designed to help adventurers discover Himalayan peaks based on their preferences. It leverages clustering and similarity metrics to suggest similar peaks, considering factors like height, location, difficulty level, and popularity.

## 📊 Features

- Loads and explores a dataset of Himalayan peaks
- Adds synthetic features like **Difficulty Level** and **Popularity**
- Normalizes and encodes data for processing
- Applies **K-Means Clustering** to categorize peaks
- Uses **Cosine Similarity** to recommend similar peaks
- Provides interactive **menu-based CLI** for user-friendly recommendations
- Visualizations:
  - Peak height distribution
  - Pairplot of features
  - Cluster scatter plot
  - Top 10 highest peaks bar chart
  - Cosine similarity heatmap

---

## 📁 Dataset

The system uses a dataset named `Himalayan_Peaks.csv` which includes:
- Peak names
- Heights (in meters)
- Locations (Himal ranges)
- Synthetic or real values for:
  - `Difficulty_Level` (1–5 scale)
  - `Popularity` (1–100 scale)

---

## ⚙️ Technologies Used

- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Jupyter Notebook**
- **Tabulate** (for pretty CLI tables)
- **Machine Learning**: K-Means clustering, Cosine similarity

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/HimalayanPeaks-Recommendation-System.git
cd HimalayanPeaks-Recommendation-System
