# Build a Semantic Book Recommender (Python, OpenAI, LangChain, Gradio)

This project is a book recommender system that uses semantic search to find books with similar descriptions. It's built with Python and leverages powerful libraries like LangChain, OpenAI, and ChromaDB for the core recommendation logic.

## Technologies Used

- Python
- Pandas
- Jupyter
- LangChain
- OpenAI
- ChromaDB
- Hugging Face Transformers

## Project Structure

- `data_exploration.ipynb`: Jupyter notebook for initial exploration and cleaning of the book dataset.
- `sentiment_analysis.ipynb`: Notebook for performing sentiment analysis on book descriptions to extract emotional context.
- `vector-search.ipynb`: The core of the recommender system, this notebook handles the creation of vector embeddings for book descriptions and performs semantic search.
- `requirements.txt`: A list of all the Python packages required to run the project.

## Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd semantic-book-recommender
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Set up your OpenAI API Key:**
    You will need an OpenAI API key to generate embeddings. Make sure to set it as an environment variable.

## Usage

The project is developed through a series of Jupyter notebooks. To understand the workflow and run the recommender, you can execute the cells in the notebooks in the following order:

1.  `data_exploration.ipynb`
2.  `sentiment_analysis.ipynb`
3.  `vector-search.ipynb`
