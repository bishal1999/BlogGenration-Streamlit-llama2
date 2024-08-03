# Blog Generation with Streamlit and LLaMa 2 Model

This project demonstrates how to generate blog posts using the LLaMa 2 model with a Streamlit frontend. Users can input a blog topic, specify the number of words, and choose the target audience to generate a blog.

## Features

- Generate blog posts based on a given topic.
- Customize the blog for different job profiles (Researchers, Data Scientist, Common People).
- Set the desired number of words for the blog.

## Installation

1. **Clone the Repository:**
    ```bash
    git clone <repository_url>
    cd <repository_name>
    ```

2. **Create a Virtual Environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate    # On Windows, use `venv\Scripts\activate`
    ```

3. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Dependencies

- `sentence-transformers`
- `uvicorn`
- `ctransformers`
- `langchain`
- `python-box`
- `streamlit`
- `langchain-community`

## Running the Application

To run the Streamlit application, use the following command:

```bash
streamlit run app.py
