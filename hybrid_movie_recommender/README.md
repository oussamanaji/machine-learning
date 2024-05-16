# Personalized Hybrid Movie Recommender System

This project presents a sophisticated movie recommender system that seamlessly combines collaborative filtering and content-based techniques to deliver highly personalized movie recommendations.

## Features
- Leverages a vast dataset of user ratings and movie attributes
- Employs advanced algorithms, such as Singular Value Decomposition (SVD) and Cosine Similarity
- Uncovers latent user preferences and item similarities
- Ensures a balance between user-based and item-based recommendations
- Enhances the overall quality and diversity of the suggested movies

## Technical Skills
- Recommender Systems
- Collaborative Filtering
- Content-Based Filtering
- Matrix Factorization
- Cosine Similarity
- Python
- Libraries: pandas, numpy, scikit-learn, surprise

## Applications
- Movie Streaming Platforms
- Video-on-Demand Services
- Movie Recommendation Engines
- Personalized Content Suggestion

## Methodology
1. **Data Loading**: The MovieLens 20M dataset, containing user ratings and movie attributes, is loaded and preprocessed using the `pandas` library.
2. **Collaborative Filtering**: Singular Value Decomposition (SVD) is applied to the user-item rating matrix to uncover latent factors and capture user preferences.
3. **Content-Based Filtering**: TF-IDF vectorization and cosine similarity are used to measure the similarity between movies based on their attributes, such as genres and tags.
4. **Hybrid Recommendation**: The collaborative filtering and content-based filtering techniques are combined to generate personalized movie recommendations for each user.
5. **Evaluation**: The recommender system is evaluated using metrics such as precision, recall, and normalized discounted cumulative gain (NDCG) to assess the quality and relevance of the recommendations.

## Results
- The Personalized Hybrid Movie Recommender System achieved remarkable performance in generating accurate and diverse movie recommendations for users.
- The combination of collaborative filtering and content-based techniques effectively captured user preferences and movie similarities, resulting in highly personalized recommendations.
- The SVD algorithm successfully uncovered latent factors, enabling the system to identify hidden patterns and generate meaningful recommendations.
- The evaluation metrics, such as precision and NDCG, demonstrated the system's ability to recommend relevant and appealing movies to users.

## Getting Started
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1_7lKKMV4Lg0NHjCpZqfWq3-IWR56VzPF?usp=sharing)

1. Prepare your movie dataset and user ratings data.
2. Follow the instructions in the notebook to train the recommender system and generate personalized movie recommendations.

## Contributing
Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. This means you are free to use, modify, and distribute the software, as long as you include the original license and copyright notice in any copies or substantial portions of the software.

## Contact
For any inquiries or collaborations, please contact:
- Mohamed Oussama NAJI
- LinkedIn: [Mohamed Oussama Naji](https://www.linkedin.com/in/oussamanaji/)
