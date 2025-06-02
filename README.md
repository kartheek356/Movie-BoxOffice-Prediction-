# Movie-BoxOffice-Prediction-

Movies.csv is the initial dataste.

Movies_final is the processed final dataset.

API Data : https://developer.themoviedb.org/reference/movie-popular-list

Website Link : https://sites.google.com/view/movie-boxoffice-prediction/introduction?authuser=0


Here’s a polished, professional `README.md` for your **Movie Box Office Prediction** project, modeled after the format you provided earlier:

---

# 🎬💰 Movie Box Office Prediction – Forecasting Revenue Before Release

Welcome! This project builds a machine learning-based system to **predict a movie’s box office revenue before release** using historical data and pre-release attributes — helping producers, investors, and distributors make informed financial decisions.

---

## 🚀 Project Mission

The film industry is notoriously unpredictable. Our goal is to build a **data-driven predictive model** that uses key factors — such as budget, cast, genre, director reputation, and audience anticipation — to estimate a film’s revenue before its theatrical release.

This empowers stakeholders across the entertainment industry to:

* Reduce investment risk
* Allocate marketing budgets wisely
* Optimize release windows
* Make data-backed acquisition and distribution decisions

---

## 🛠 Tech Stack

### ML Frameworks:

* Python, Pandas, NumPy, Matplotlib, Seaborn
* Scikit-Learn, XGBoost, Keras/TensorFlow

### Data & Sources:

* TMDb (The Movie Database) APIs
* IMDb Ratings and YouTube trailer stats
* Historical box office data

### Models Explored:

* Linear Regression
* Random Forest
* XGBoost
* Deep Neural Networks

---

## 📊 Modeling Pipeline

1. **Data Collection**

   * Aggregated structured metadata: budget, genre, cast, release date, etc.
   * Augmented with social/media engagement stats and user voting patterns.

2. **EDA & Feature Engineering**

   * Created synthetic features (e.g., ROI, franchise flag, hype index)
   * Encoded categorical variables (genre, language)
   * Performed correlation and multicollinearity checks

3. **Model Training**

   * Multiple regression algorithms tested
   * Metrics: R², MAE, RMSE
   * Best performance achieved using XGBoost (with hyperparameter tuning)

4. **Evaluation**

   * Validated model on recent unreleased films
   * Assessed predictive accuracy and generalizability

---

## 💡 Research Questions

* 🎯 What are the most important **pre-release indicators** of box office success?
* 🎥 Does **genre** or **franchise status** influence revenue patterns?
* 📆 How do **release month or season** impact performance?
* 📣 How does **pre-release buzz** (trailers, votes, ratings) correlate with financial outcomes?
* 💸 Do **higher budgets** always equate to more revenue?
* 🔁 What’s the **return on investment (ROI)** across various budget categories?
* 🌍 How do **external factors** (competition, events) skew outcomes?

---

## ✅ Key Takeaways

* A combination of **budget, genre, director, vote count, and pre-release popularity** forms the strongest predictor of revenue.
* **Audience anticipation** and **release timing** have statistically significant influence.
* **Franchise films** outperform standalones consistently.
* XGBoost achieved **the highest R² and lowest error rates** across test sets.

---

## 🌐 Future Work

* Package the model into a **REST API** for real-time predictions.
* Build a **dashboard UI** for “what-if” scenario testing.
* Integrate **dynamic features** like social media buzz in real-time.
* Extend model to **predict ROI**, not just revenue.

---

## 📁 Project Structure

| File / Folder                    | Purpose                                     |
| -------------------------------- | ------------------------------------------- |
| `data/`                          | Contains raw and processed datasets         |
| `notebooks/EDA.ipynb`            | Exploratory data analysis and visualization |
| `models/`                        | Scripts and saved ML models                 |
| `notebooks/model_training.ipynb` | Model training and evaluation               |
| `app/`                           | (Planned) Deployment-ready API scripts      |

---

