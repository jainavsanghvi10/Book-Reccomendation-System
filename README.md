# Book-Reccomendation-System
BookRec is a content-based recommendation system that provides personalized recommendations for books and research papers. The system leverages advanced techniques such as Transformers and Word2Vec models to generate embeddings for text-based inputs, allowing for a deeper understanding of the underlying themes and content.

## Features
* **Customized dataset:** Utilize web-scraping techniques to extract relevant information such as book descriptions, authors, genres, popularity metrics, and research paper details. Our database is expandable as we dynamically add new books using real-time web scraping when users likes a book not present in the current database.
* **Model selection:** Implement state-of-the-art Transformers (suitable for this task) and Word2Vec models to obtain accurate vector embeddings for text-based inputs.
* **Smart modifications:** Maximize the information provided to the models by intelligently modifying the input data, enhancing the context and relevance of the recommendations. This ensures that our models make informed decisions based on enriched information.
* **Extension capabilities:** Our system is designed for seamless expansion beyond book and research paper recommendations. It can be easily adapted to recommend various content types like movies, music, and products. By incorporating relevant data columns and adjusting the pipeline, the system can accommodate diverse recommendation scenarios.
## Getting Started
* Clone the repository: git clone https://github.com/jainavsanghvi10/Book-Reccomendation-System.git
* Customize the web-scraping and data preprocessing scripts to gather the necessary information for your specific use case.
* Train and evaluate the recommendation models using the provided notebooks and scripts. The trained models and resulting embeddings are already included in the project. However, if you prefer to train your own models, uncomment the training code in the notebook and train them on your system. You can also use your own dataset as long as it follows a similar structure.
* Customize and integrate the recommendation system into your own application.
