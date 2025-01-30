# Semantic-Book-Recommendation

# Semantic Book Recommendation System

## Overview
The Semantic Book Recommendation System is an AI-powered project that suggests books based on user input. By leveraging OpenAI embeddings and Chroma vector storage, the system provides recommendations that align with the semantic meaning of the user's query. Users can further refine recommendations by selecting a book category and an emotional tone.

## Features
- **Semantic Search**: Uses OpenAI embeddings to find books with similar meanings to the user's input.
- **Emotion-Based Recommendations**: Books can be filtered based on emotional tones such as Happy, Sad, Suspenseful, etc.
- **Category Selection**: Users can filter books by genre or keep the selection broad.
- **Gradio-Powered UI**: An interactive interface for ease of use.

## Requirements
Ensure you have the following installed before running the application:
- Python 3.8+
- Required Python libraries (install using the command below)
- Numpy
- Pandas
- Dotenv
- Langchain
- Gradio


```sh
pip install pandas numpy gradio langchain-community langchain-chroma langchain-openai openai python-dotenv
```

## How to Run
1. **Edit the `.env` file**: Add your own OpenAI API key and Hugging Face API token.
2. **Run the python script**:

```sh
python gradio-dashboard.py
```

3. Open the provided Gradio link in your browser to start using the system.

## File Structure
- `gradio-dashboard.py`: Main script for running the recommendation system.
- `books_with_emotions.csv`: Dataset containing book metadata and emotional tone scores.
- `tagged_description.txt`: Text file containing tagged descriptions for book embeddings.
- `.env`: File for storing API keys securely.

## Usage
1. Enter a book description in the text box.
2. Select a category from the dropdown menu (optional).
3. Choose an emotional tone to filter recommendations (optional).
4. Click "Recommend" to generate book suggestions.
