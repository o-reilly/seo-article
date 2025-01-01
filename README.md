# SEO Article Writer with ChatGPT

This project is a Streamlit application that generates SEO-optimized articles using OpenAI's GPT-3.5-turbo model.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/o-reilly/seo-article.git
    cd seo-article
    ```

2. Install Streamlit:
    ```sh
    pip install streamlit
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Create a `.env` file and insert your OpenAI API key:
    ```sh
    echo "OPENAI_API_KEY=your_openai_api_key" > .env
    ```

## Usage

1. Run the Streamlit application:
    ```sh
    streamlit run main.py
    ```

2. Open your web browser and go to:
    ```
    http://localhost:8501/
    ```

3. Enter a keyword, select a writing style, and choose the word count. Click the "Generate Article" button to generate an SEO-optimized article.

## License

This project is licensed under the GNU General Public License v3.0. See the [LICENSE](http://_vscodecontentref_/1) file for details.
