# Machine Learning Projects 🚀

A collection of three machine learning projects demonstrating different ML techniques including regression, recommendation systems, and classification.

---

## 📁 Projects Overview

### 1. 🏠 Bangalore House Price Prediction
Predict house prices in Bangalore using machine learning regression models.

**Features:**
- Data preprocessing and exploratory data analysis
- Multiple regression algorithms implementation
- Price prediction based on house features (location, size, amenities, etc.)
- Model evaluation and comparison

**Files:**
- `House_Prediction.ipynb` - Jupyter notebook with complete implementation
- `Bengaluru_House_Data.csv` - Dataset containing house information and prices

**Technologies:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn

---

### 2. 🎬 Movie Recommendation System
An intelligent movie recommendation engine using content-based filtering and similarity metrics.

**Features:**
- Movie similarity analysis using cosine similarity
- Content-based recommendation algorithm
- Integration with TMDB API for movie posters and details
- Interactive Streamlit web application
- Real-time movie poster fetching

**Files:**
- `movie_recommendation_system.ipynb` - Jupyter notebook with model development
- `app.py` - Streamlit application for interactive recommendations
- `geetansh.py` - Supporting utility module
- `tmdb_5000_movies.csv` - Movies dataset
- `tmdb_5000_credits.csv` - Credits dataset
- `requirement.txt` - Project dependencies
- `setup.sh` - Setup script
- `ProcFile` - Procfile for deployment

**Technologies:** Python, Streamlit, Pandas, Scikit-learn, TMDB API

---

### 3. 📧 SMS-Email Spam Classifier
A classification model to detect and filter spam messages and emails.

**Features:**
- Text preprocessing and feature extraction
- Multiple classification algorithms
- Spam/Ham classification
- Model performance evaluation
- Deployment-ready Python script

**Files:**
- `Email Spam Classifier.ipynb` - Jupyter notebook with model exploration
- `Email Spam Classifier.py` - Production-ready classifier script
- `spam.csv` - Primary spam dataset
- `spam1.csv` - Additional spam dataset for testing

**Technologies:** Python, Pandas, Scikit-learn, NLTK, TF-IDF

---

## 🛠️ Installation

### Prerequisites
- Python 3.8+
- pip (Python package manager)

### Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/Geetansh124/Machine-Learning-Project-s.git
cd Machine-Learning-Project-s
```

2. **Install dependencies:**

For all projects:
```bash
pip install pandas scikit-learn matplotlib seaborn jupyter numpy nltk
```

For Movie Recommendation System (additional):
```bash
pip install streamlit requests
```

Or install from requirements file:
```bash
cd "Movie Recommendation System"
pip install -r requirement.txt
```

---

## 🚀 Usage

### Bangalore House Price Prediction
1. Open the Jupyter notebook:
```bash
jupyter notebook "Bangalore House Price Prediction/House_Prediction.ipynb"
```
2. Run all cells to see the complete analysis and predictions
3. Modify input features to predict new house prices

### Movie Recommendation System
**Option 1: Using Jupyter Notebook**
```bash
jupyter notebook "Movie Recommendation System/movie_recommendation_system.ipynb"
```

**Option 2: Using Streamlit Web App**
```bash
cd "Movie Recommendation System"
streamlit run app.py
```
- Select a movie from the dropdown
- Click "Recommend" to get 5 similar movie recommendations with posters

### SMS-Email Spam Classifier
**Option 1: Using Jupyter Notebook**
```bash
jupyter notebook "SMS-Email Spam Classifier/Email Spam Classifier.ipynb"
```

**Option 2: Using Python Script**
```bash
cd "SMS-Email Spam Classifier"
python "Email Spam Classifier.py"
```

---

## 📊 Datasets

### Bangalore House Price Dataset
- **File:** `Bengaluru_House_Data.csv`
- **Records:** Multiple house listings with prices and features
- **Features:** Location, size, price, amenities, etc.

### TMDB Movie Dataset
- **Files:** `tmdb_5000_movies.csv`, `tmdb_5000_credits.csv`
- **Records:** 5000+ movies with metadata and credits
- **Features:** Title, genres, keywords, cast, crew, ratings, etc.

### Spam Classification Dataset
- **Files:** `spam.csv`, `spam1.csv`
- **Records:** Email and SMS messages labeled as spam or ham
- **Features:** Message text, length, word frequency, etc.

---

## 📈 Technologies Used

| Technology | Purpose |
|-----------|---------|
| **Python** | Primary programming language |
| **Pandas** | Data manipulation and analysis |
| **Scikit-learn** | Machine learning algorithms |
| **Jupyter Notebook** | Interactive development and visualization |
| **Streamlit** | Web application framework |
| **Matplotlib & Seaborn** | Data visualization |
| **NLTK** | Natural language processing |
| **NumPy** | Numerical computing |
| **Requests** | API calls to TMDB |

---

## 📝 Project Structure

```
Machine Learning Project's/
├── Bangalore House Price Prediction/
│   ├── House_Prediction.ipynb
│   └── Bengaluru_House_Data.csv
│
├── Movie Recommendation System/
│   ├── app.py
│   ├── geetansh.py
│   ├── movie_recommendation_system.ipynb
│   ├── requirement.txt
│   ├── setup.sh
│   ├── ProcFile
│   ├── tmdb_5000_movies.csv
│   └── tmdb_5000_credits.csv
│
├── SMS-Email Spam Classifier/
│   ├── Email Spam Classifier.ipynb
│   ├── Email Spam Classifier.py
│   ├── spam.csv
│   └── spam1.csv
│
└── README.md
```

---

## 🔧 Model Algorithms

### Bangalore House Price Prediction
- Linear Regression
- Ridge/Lasso Regression
- Decision Trees
- Random Forest
- Gradient Boosting

### Movie Recommendation System
- Cosine Similarity
- Content-Based Filtering
- TF-IDF Vectorization

### SMS-Email Spam Classifier
- Naive Bayes
- Support Vector Machine (SVM)
- Logistic Regression
- Random Forest Classifier

---

## 📚 Key Learnings

- **Data Preprocessing:** Handling missing values, encoding categorical features, scaling numerical features
- **Feature Engineering:** Creating meaningful features for improved model performance
- **Model Selection:** Choosing appropriate algorithms for different problem types
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, ROC-AUC, MSE, R²
- **Deployment:** Converting models to production-ready applications
- **Web Integration:** Using Streamlit for interactive ML applications

---

## 💡 Future Enhancements

- [ ] Add more datasets for improved generalization
- [ ] Implement advanced deep learning models
- [ ] Deploy models to cloud platforms (AWS, GCP, Azure)
- [ ] Add real-time prediction APIs
- [ ] Implement automated retraining pipelines
- [ ] Add more comprehensive error handling
- [ ] Integrate database for predictions logging

---

## 📄 License

These projects are provided as-is for educational purposes.

---

## 👥 Author

**Geetansh**

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

---

## 📧 Contact & Support

For questions or issues:
- Open an issue on GitHub
- Contact: [Your Contact Information]

---

## ⭐ Acknowledgments

- TMDB for the movie database API
- Kaggle for datasets
- Open-source ML community

---

**Happy Learning! 🎓**
