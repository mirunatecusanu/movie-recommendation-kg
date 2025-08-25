# movie-recommendation-kg

## Overview

**movie-recommendation-kg** is an exploratory project focused on leveraging knowledge graphs and advanced recommendation systems to provide personalised movie recommendations. The goal is to create a smart, user-friendly system that helps users discover movies from their 
watchlists based on various factors such as mood, available time, company (solo, friends, family), and past viewing experiences.

## Problem Statement

Managing an extensive list of movies can be overwhelming, especially when you're looking for something specific or simply want to avoid the stress of choosing. This project aims to address this issue by providing tailored recommendations that consider your current mood, available time, movie length, and preferences—whether solo watching or with others.

## Key Features

1. **Knowledge Graphs**: Utilise knowledge graphs to represent and understand complex relationships between movies, actors, directors, 
genres, and user preferences.
2. **Recommender Systems**: Implement advanced recommendation algorithms to suggest movies based on comprehensive data analysis.
3. **RAG (Retrieval-Augmented Generation)**: Integrate RAG models to enhance the recommendation process by retrieving relevant information from the knowledge graph.
4. **LLMs for Chatbot**: Develop a chatbot using Large Language Models (LLMs) to interact with users, gather preferences, and provide 
recommendations in a conversational manner.

## Use Cases

- **Mood-Based Recommendations**: Suggest movies based on your current mood (e.g., happy, sad, relaxed).
- **Time Availability**: Recommend movies that fit the time you have available.
- **Movie Length Preferences**: Filter recommendations for short or long movies.
- **Company and Preferences**: Tailor suggestions based on who you're watching with and their preferences.
- **Actor and Genre Interests**: Incorporate favourite actors and genres into the recommendation process.
- **Past Viewing Experience**: Use past watch history to refine future recommendations.

## Technologies

- **Knowledge Graphs**: Building and querying knowledge graphs using tools like Neo4j.
- **Recommender Systems**: Implementing collaborative filtering, content-based filtering, and hybrid approaches.
- **RAG Models**: Utilising Retrieval-Augmented Generation models to enhance recommendation quality.
- **LLMs for Chatbot**: Developing chatbots using frameworks like Hugging Face Transformers and LangChain.

## Goals

- Explore the integration of knowledge graphs in recommendation systems.
- Develop a user-friendly interface for movie recommendations.
- Enhance recommendation accuracy through advanced algorithms and natural language processing.
- Provide an intuitive way to discover movies from personal watchlists without extensive browsing.

## Getting Started

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/yourusername/MovieKG-RecommendationSystem.git
   ```
2. **Set Up Environment**:
   - Install dependencies using `pip install -r requirements.txt`.
   - Configure knowledge graph databases and LLM models as needed.
3. **Explore the Code**:
   - Dive into the codebase to understand how different components work together.
   - Modify and extend functionalities based on your needs.

## Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or suggest improvements.
