# Mood Across Days

## Overview
This project analyzes the positivity and negativity of diary entries using sentiment analysis. It utilizes the NLTK library's SentimentIntensityAnalyzer to calculate sentiment scores for each entry. The visualization generated with Plotly Express showcases the trends of positivity and negativity over time.

## Dependencies
The project relies on the following Python libraries:
- [Streamlit](https://streamlit.io/) - for building interactive web applications
- [Plotly Express](https://plotly.com/python/plotly-express/) - for creating interactive plots
- [NLTK](https://www.nltk.org/) - for natural language processing tasks

## Setup
To run the project, follow these steps:
1. Clone the repository: `git clone https://github.com/tur14cus/mood-across-days.git`
2. Install dependencies: `pip install streamlit plotly nltk`
3. Ensure you have NLTK's Vader lexicon downloaded by running the following Python script:
   ```python
   import nltk
   nltk.download('vader_lexicon')
   ```
4. Place your diary text files in a folder named `diary` within the project directory.
5. Run the Streamlit application: `streamlit run main.py`

## Usage
The Streamlit application displays the trends of positivity and negativity over time based on the diary entries provided. Users can visualize how the sentiment of the diary entries evolves over time.

## Structure
The project consists of the following files:
- `main.py`: Contains the Streamlit application code for analyzing diary tone and generating visualizations.
- `diary/`: Directory containing diary text files.
- `README.md`: This readme file providing an overview of the project.

## Contributions
Contributions are welcome. Feel free to fork the repository, make improvements, and submit pull requests.

## License
This project is licensed under the [MIT License](LICENSE).
