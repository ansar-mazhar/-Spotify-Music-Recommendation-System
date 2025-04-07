🎧 Spotify Music Recommendation System

A simple content-based recommendation system built with Python that suggests similar songs based on their attributes like artist, duration, and popularity.  

This project is a part of my Machine Learning internship task and demonstrates how to preprocess data, calculate similarity, and generate music recommendations using machine learning techniques.

📌 Features

- ✅ Content-based recommendations using cosine similarity  
- ✅ Preprocessing and normalization of features  
- ✅ One-Hot Encoding of categorical features  
- ✅ Scalable to more features and tracks  
- ✅ Built and tested in Google Colab  

📂 Dataset

The dataset contains the following key features:

- 🎤 `Artist`  
- 🎶 `Track Name`  
- 🕒 `Duration (ms)`  
- 🌟 `Popularity`  
- 🔗 `Track ID`  

> Note: The dataset used was cleaned to remove null values and irrelevant columns.

 🛠️ Technologies Used

- Python 🐍  
- Pandas  
- Scikit-learn  
- NumPy  

🚀 How It Works

1. Preprocessing 
   - Normalize popularity using MinMaxScaler  
   - One-hot encode artist column  
   - Drop unnecessary columns  

2. Similarity Computation 
   - Use cosine similarity on numeric features  

3. Recommendation Function  
   - Input a track name  
   - Return top N most similar tracks  

 📈 Example Output

recommend_tracks("Here Comes The Sun - Remastered 2009", df, similarity_matrix)
