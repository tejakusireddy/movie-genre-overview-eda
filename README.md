# 🎬 Movie Genre & Overview EDA

This project performs an **Exploratory Data Analysis (EDA)** on a movie dataset containing overview text and associated genre labels. The main objective is to identify trends in genre co-occurrence, analyze text patterns, and explore features that could be used for downstream tasks such as content recommendation or genre prediction.

---

## 📁 Dataset

The project uses two CSV files provided in an archive:

- `movies_overview.csv` – Contains movie titles, overviews, and genre IDs
- `movies_genres.csv` – Maps genre IDs to genre names

After merging the datasets, new features such as the **number of genres** per movie and the **word count of overviews** are added for deeper analysis.

---

## 🧠 Project Highlights

- ✅ Cleaned and merged genre and overview data using `genre_ids`
- ✅ Created `overview_length` (number of words) and `num_genres` (count per movie)
- ✅ Visualized top genres, overview distributions, and outlier boxplots
- ✅ Built a **genre co-occurrence matrix** to explore common genre pairs
- ✅ Simulated churn-like genre activity trends using monthly data
- ✅ Detected outliers using IQR method

---

## 📊 Visualizations

| Plot | Description |
|------|-------------|
| 📦 Bar Plot | Top 10 Most Common Genres |
| 📉 Histogram | Overview Length Distribution |
| 📊 Count Plot | Number of Genres per Movie |
| 🔥 Heatmap | Genre Co-occurrence Matrix |
| 📈 Line Chart | Simulated Churn Trend Over Time |
| 🧪 Boxplots | Outlier Detection for Genres and Text Length |

---

## 🧾 Insights & Takeaways

- 🎭 **Drama**, **Comedy**, and **Action** are the most frequent genres.
- 📚 Most movie overviews are between 50–150 words.
- 🎬 Most movies belong to **2–3 genres**; rare cases have 5+.
- 💞 **Drama + Romance** and **Action + Adventure** are highly co-occurring pairs.
- 📏 Overview length is not highly correlated with genre count.

---

## 📎 Files in This Repo

| File | Description |
|------|-------------|
| `Midterm.ipynb` | Jupyter notebook with full EDA |
| `Movie_Genre_Overview_EDA_Presentation.pptx` | PowerPoint deck with results & insights |
---

## 🧪 Tools & Libraries

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (for binary matrix and co-occurrence)
- Google Colab / Jupyter Notebook

---

## ✅ Future Work

- Use NLP to **predict genres** from overview text (e.g., using BERT)
- Add release year column to explore **genre trends over time**
- Apply clustering on overview embeddings to find hidden movie themes

---

## 📌 License

This project is open-source under the [MIT License](LICENSE).  
(You can add a `LICENSE` file or change it if needed)

---

## 🙌 Acknowledgments

- Dataset inspired by CS 661 coursework
- Built using guidance from NVIDIA EDA presentation format
- Thanks to open-source libraries and contributors!

