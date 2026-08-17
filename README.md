# Movie Recommendation System 🎬🍿

This project is a movie recommendation engine designed to predict user ratings for unseen movies. It was built as a portfolio project during the **ALX Africa Data Science Program**.

## 📊 Dataset
The project uses the **MovieLens** dataset (10 million ratings) containing:
- **10,000,038** ratings (scale 0.5 to 5.0)
- **162,541** unique users
- **48,213** unique movies

## ⚙️ Methodology
I implemented two primary approaches to recommendation:
1. **Item-Item Collaborative Filtering:** Used Cosine Similarity on a memory-efficient `scipy.sparse.csr_matrix`.
2. **Matrix Factorization (SVD):** Implemented using the `Surprise` library to uncover latent factors and predict ratings accurately.

## 🚀 Key Features
- **Cold-Start Handling:** Implements a global mean fallback for users or movies not present in the training set.
- **Memory Optimization:** Uses sparse matrices to process 10M+ ratings without memory overflow.
- **Efficient Prediction:** Saves test predictions into a clean `submission.csv` format.

## 🛠️ Tech Stack
- Python (Pandas, NumPy)
- Scikit-learn (Cosine Similarity)
- Scipy (Sparse Matrices)
- Surprise Library (SVD Matrix Factorization)
- Jupyter Notebook

## 📂 How to Run Locally
1. Clone the repository:  
   `git clone https://github.com/samueleniola/Movie-Recommendation-System.git`
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Open the Jupyter notebook and run all cells:  
   `ALX Movie Recommendation System.ipynb`

## 🙏 Acknowledgments
This project was developed as part of the curriculum for the **ALX Africa Data Science Program**, a 13-month intensive training program that empowers Data Scientists across Africa with world-class technical skills.


*Feel free to explore the code and leave a star ⭐ if you found this helpful!*
