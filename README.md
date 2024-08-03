# 🌍 Relocation Analyst: City Recommendations and Details

This Streamlit application helps users find the best city based on their preferences for weather, temperature, humidity, air quality, and cost of living. It also provides detailed information about specific cities and allows users to interact with a chatbot for city-related queries.

## ✨ Features

- 🏙️ **City Recommendations**: Use the sidebar to select your preferences for weather, temperature, humidity, air quality, and cost of living. The app will display a list of recommended cities based on these preferences.
- 📊 **City Details**: Type the name of a city in the text input field to get detailed information about that city.
- 🤖 **Chatbot**:Click on the "Chat with our bot" button and select a question to interact with the chatbot.

## 🚀 Installation

To run this application locally, follow these steps:

1. 📥 **Clone the repository**:
    ```bash
    git clone https://github.com/SriPhaniDeepthimai/relocation-analyst.git
    cd relocation-analyst
    ```

2. 🔧 **Install the required dependencies**:
    Ensure you have Python 3.7+ installed. Then install the required Python packages using pip:
    ```bash
    pip install pandas streamlit
    ```

3. 📁 **Place the Dataset**:
    Ensure that the dataset (`Integrated_Dataset (1).csv`) is placed in the root directory of the project.

4. ▶️ **Run the Streamlit application**:
    ```bash
    streamlit run relocation.py
    ```

## 🗂️ File Structure

- `relocation.py`: Main script containing the Streamlit app code.
- `Integrated_Dataset (1).csv`: The dataset used for city recommendations and details.

## 📋 Requirements

- Python 3.7+
- Pandas
- Streamlit
