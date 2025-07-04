# 🎬 Movie Recommendation System

A content-based movie recommendation system built using **Machine Learning** techniques including **TF-IDF Vectorizer**, **Cosine Similarity**, and **difflib** for string matching.

This project helps users discover movies similar to their favorites by analyzing textual features from the dataset — just like how Netflix or IMDB makes recommendations!

---

## 🚀 Features

- Recommends movies based on **plot summaries and genres**
- Uses **TF-IDF** to convert text data into numerical vectors
- Calculates **Cosine Similarity** between movies for recommendation
- Smart **string matching** using `difflib` to handle input errors
- Simple and interactive CLI-based interface for user input

---

## 🧠 Tech Stack

- Python
- Pandas
- scikit-learn (`TfidfVectorizer`)
- difflib
- Cosine Similarity (from sklearn.metrics.pairwise)
- Jupyter Notebook

---

## 📂 Dataset

The dataset used contains:
- Movie titles
- Plot summaries
- Genre/category information

> You can use datasets from sources like [Kaggle](https://www.kaggle.com/datasets) or scrape IMDB for customized data.

---

## ⚙️ How It Works

1. Load the dataset and clean the text data (e.g., lowercasing, removing special characters).
2. Use `TfidfVectorizer` to convert movie descriptions into feature vectors.
3. Compute the cosine similarity matrix between all movie vectors.
4. Take user input for a movie title.
5. Use `difflib.get_close_matches()` to find the closest match from the dataset.
6. Display the top N similar movies based on cosine similarity.

---

## 🖥️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
Install the required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Run the notebook or script:

Open Movie_Recommendation.ipynb in Jupyter Notebook

OR run the script from terminal:

bash
Copy
Edit
python movie_recommendation.py
Enter a movie name when prompted, and get your recommendations!

📌 Example Output
markdown
Copy
Edit
Enter a movie name: Avatar

Top 5 movie recommendations:
1. Aliens
2. Star Wars: Episode IV - A New Hope
3. Guardians of the Galaxy
4. Interstellar
5. The Matrix
📈 Future Enhancements
Add a web interface using Flask or Streamlit

Combine with collaborative filtering

Deploy as an API or web app

Use a larger, dynamic dataset (IMDB or TMDb)

🤝 Contributing
Pull requests are welcome! If you have suggestions or improvements, feel free to fork the repo and submit a PR.

📜 License
This project is licensed under the MIT License.

📬 Contact
Moddannagari Yoganand
📧 Email: your-email@example.com
🔗 LinkedIn | Portfolio

⭐ Show Your Support
If you found this helpful, give it a ⭐ and share it with your peers!

yaml
Copy
Edit

---

Let me know if you'd like me to generate a sample `requirements.txt`, Python script version, or Jupyter notebook template too!







Do
