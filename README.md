# 🏡 Apartment Recommender System

Welcome to the Apartment Recommender System project! This project is designed to help users discover similar properties based on advanced text embeddings using BERT and cosine similarity. The system is built using Streamlit for the user interface, making it easy for users to interact with the model and find their next dream home.

## 🚀 Project Overview

This project leverages BERT embeddings to capture the nuanced features of apartments and uses cosine similarity to recommend the top 5 most similar properties to any selected apartment. The main goal is to provide personalized property recommendations in a user-friendly interface.

### 🔍 Key Features
- **Streamlit Interface**: A simple, clean, and intuitive interface for users to interact with the recommender system.
- **BERT Embeddings**: Uses BERT to generate 768-dimensional embeddings of property descriptions, capturing detailed semantics.
- **Cosine Similarity**: Calculates the similarity between apartments using cosine similarity on the BERT embeddings.
- **Top 5 Recommendations**: For any selected apartment, the system recommends the five most similar properties.

## 📂 Project Structure

- `datasets/`: Contains the dataset used for the project.
- `streamlit_app.py`: The main Streamlit app that runs the recommender system.
- `requirements.txt`: Lists the Python packages required to run the project.
- `README.md`: This file.

## 📦 Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/apartment-recommender-system.git
   cd apartment-recommender-system
