# StreamlitRNN-Sentiment

![Streamlit](https://streamlit.io/images/brand/streamlit-mark-color.png)

## Overview
**StreamlitRNN-Sentiment** is an interactive web application designed for analyzing the sentiment of IMDb movie reviews using Recurrent Neural Networks (RNN). Built with the powerful Streamlit framework, this application provides a user-friendly interface where users can input movie reviews and receive instant sentiment predictions.

## Features
- **Real-Time Sentiment Analysis**: Enter any IMDb movie review, and the model will classify the sentiment as Positive, Negative, or Neutral in real-time.
- **RNN-Based Model**: The sentiment prediction is powered by a Recurrent Neural Network, which excels in processing sequential data and understanding context in text.
- **Intuitive User Interface**: The app features an easy-to-navigate layout, making it accessible for users of all backgrounds.
- **Data Visualization**: Users can see sentiment distribution and predictions in a visually appealing format.

## Use Cases
- **Movie Enthusiasts**: Quickly gauge the sentiment of movie reviews to decide what to watch next.
- **Developers and Researchers**: Explore the implementation of RNN for natural language processing and sentiment analysis.
- **Educational Purposes**: Learn about sentiment analysis techniques and machine learning with a practical application.

## Technologies Used
- [Python](https://www.python.org/) - Programming language.
- [Streamlit](https://streamlit.io/) - Web framework for building interactive applications.
- [TensorFlow/Keras](https://www.tensorflow.org/) - Framework for building and training RNN models.
- [Pandas](https://pandas.pydata.org/) - Data manipulation and analysis library.
- [NumPy](https://numpy.org/) - Fundamental package for scientific computing.

## Installation

### Prerequisites
- Python 3.7 or higher
- pip

### Clone the Repository
```bash
git clone https://github.com/yourusername/StreamlitRNN-Sentiment.git
cd StreamlitRNN-Sentiment
```

### Create a Virtual Environment
```bash
python -m venv venv
```
### Activate the Virtual Environment

### On Windows:
```bash
venv\Scripts\activate
```
### On macOS/Linux:
```bash
source venv/bin/activate
```
### Install Required Packages
```bash
pip install -r requirements.txt
```
### Usage
1-Run the Streamlit app:
```bash
streamlit run main.py
```
2-Open your web browser and go to http://localhost:8501.

3-Input your movie review and click the "Predict Sentiment" button to see the results.







