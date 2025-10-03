# 🎬 Movie Recommendation Based on Emotion (IMDb Scraper)

## 📌 Overview  
This project is a **Movie Recommendation System** that suggests movies from **IMDb** based on the user’s selected emotion (mapped to genres).  
It uses **web scraping with BeautifulSoup** to fetch the latest movie titles dynamically from IMDb.  

---

## 🚀 Features  
- 🔍 **Fetches movies directly from IMDb** in real-time.  
- 🎭 **Emotion-to-Genre Mapping** (e.g., Sad → Drama, Happy → Comedy, Angry → Action).  
- 📜 **Displays top movie recommendations** for the chosen emotion.  
- 🛠️ **Simple CLI-based interface** (run in terminal).  

---

## 🛠️ Tech Stack  
- **Python 3.x**  
- **Libraries Used**:  
  - `requests` – for fetching IMDb data  
  - `BeautifulSoup4` – for parsing HTML content  
  - `re` – for extracting movie titles using regex  

---

## 📂 Project Structure  
```
movie-emotion-recommender/
│── movie_recommender.py    # Main script
│── requirements.txt        # Dependencies
│── README.md               # Documentation
```

---

## ⚙️ Installation & Usage  

### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/movie-emotion-recommender.git
cd movie-emotion-recommender
```

### 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Program  
```bash
python movie_recommender.py
```

### 4️⃣ Example Output  
```
Enter the emotion: Comedy
ok https://www.imdb.com/search/title/?title_type=feature&genres=comedy
The Hangover
Superbad
21 Jump Street
...
```

---

## 🎭 Supported Emotions (Genres)  
| Emotion  | Genre (IMDb) |
|----------|--------------|
| Drama    | Drama        |
| Action   | Action       |
| Comedy   | Comedy       |
| Horror   | Horror       |
| Crime    | Crime        |

---

## 🔮 Future Improvements  
- 🌐 Build a **Flask/Streamlit web app** for interactive UI.  
- 🎤 Integrate **emotion detection (text/speech/face)** instead of manual input.  
- 📱 Extend recommendations with **TMDB API integration**.  

---

## 🤝 Contribution  
Feel free to contribute by improving scraping logic, adding new features, or enhancing UI.  
1. Fork the repo  
2. Create a new branch (`feature-xyz`)  
3. Commit changes and push  
4. Open a Pull Request  

---

## 📜 License  
This project is licensed under the **MIT License** – free to use and modify.  
