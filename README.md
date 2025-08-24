# 🎶 Spotify Song Recommendation System  

Discover new music with an AI-powered recommendation system!  
This project uses **content-based filtering** to suggest songs similar to the one you select, all wrapped in an interactive **Streamlit web app**.  

---

## ✨ What’s Inside?  

- 🎧 **Song Recommender** → Select a song and get **Top 5 similar tracks** instantly.  
- ⚡ **Fast & Lightweight** → Uses precomputed **cosine similarity matrix** for quick recommendations.  
- 🖥️ **Interactive UI** → Built with **Streamlit** for a smooth, web-based experience.  
- 📝 **Logging System** → Tracks data loading, recommendations, and errors for debugging.  

---

## 📂 Project Overview  

```

spotify\_song\_recommendation/
│── main.py             # Streamlit app (frontend/UI)
│── recommend.py        # Core recommendation logic
│── df\_cleaned.pkl     # Preprocessed dataset
│── cosine\_sim.pkl     # Precomputed similarity matrix
│── recommend.log       # Log file for events/errors
│── README.md           # Project documentation
│── code.ipynb          # recommendation sysytem in jupyter
│── spotify_song.csv    # csv file

````

---

## ⚙️ How It Works  

1. Load the cleaned dataset and cosine similarity matrix (`joblib`).  
2. User selects a song from the dropdown in Streamlit.  
3. System finds the most similar songs based on cosine similarity.  
4. Display results in a neat, numbered table.  

---

## 🛠️ Tech Stack & Libraries  

This project was built with:  

- **Python 3.12**  
- **Streamlit** → UI framework for interactive apps  
- **Pandas** → Data manipulation & cleaning  
- **NumPy** → Numerical computations  
- **Scikit-learn** → Cosine similarity computation (during preprocessing)  
- **Joblib** → Loading pre-trained dataset & similarity matrix  
- **Logging** → Event tracking and debugging  

*(Streamlit also brings in dependencies like Altair, PyDeck, Protobuf, Watchdog, etc., for smooth visualization & app handling.)*  

---

## 🚀 Getting Started  

###  Run the App

```bash
python -m streamlit run main.py
```

Then open the local URL (usually [http://localhost:8501](http://localhost:8501)) in your browser.

---

## 🎯 Example Usage

1. Select a song from the dropdown.
2. Click **Recommend Similar Songs**.
3. Instantly see your top 5 recommended tracks in a table.

---

---

✨ This one reads more like a **portfolio project showcase** — good for **GitHub, LinkedIn, or job applications**.  

Would you like me to also generate the **requirements.txt** automatically from your files so that the README and repo look complete?
```
