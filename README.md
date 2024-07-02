# AI-ChatBot
Multi-Functional Chatbot with Real-Time Data Retrieval

This Python-based chatbot offers a range of functionalities, utilizing natural language processing (NLP) techniques and external APIs to provide dynamic responses and real-time data retrieval. The chatbot enhances user interaction by responding to queries related to time, weather, and general information based on geographic locations.
Features:

    Natural Language Processing (NLP): Employs NLTK library for pattern matching and responding to various user queries in a conversational manner.
    Real-Time Time Information: Utilizes the TimezoneDB API to fetch and display current time data for any specified location worldwide.
    Weather Information: Integrates weather data retrieval based on location using a weather API (like OpenWeatherMap), providing current weather conditions and forecasts.
    Geocoding API: Incorporates a geocoding API (e.g., Google Geocoding API) to convert location names into latitude and longitude coordinates for accurate data retrieval.
    Interactive Prompts: Engages users interactively, prompting for location details until provided, ensuring precise time and weather information retrieval.
    Modular Architecture: Organized Python script with modular functions for chatbot interaction, data retrieval from APIs, and error handling.
    Educational Example: Demonstrates practical application of APIs and NLP in developing a functional chatbot for real-time data interaction.

Usage:

    Clone the repository and execute the Python script.
    Interact with the chatbot by typing queries such as "What's the time in New York?" or "What's the weather like in London?" to receive real-time responses.

Requirements:

    Python 3.x
    NLTK library for natural language processing
    Requests library for HTTP requests
    Valid API keys for TimezoneDB, weather API (e.g., OpenWeatherMap), and a geocoding API (e.g., Google Geocoding API)

Future Enhancements:

    Enhanced multi-language support for global user interaction.
    Integration with additional APIs for expanding functionality (e.g., news updates, traffic information).
    User interface (UI) development for improved user experience (UX) in chatbot interaction.

This project serves as a comprehensive example of integrating multiple external APIs with Python to create an interactive chatbot capable of fetching real-time data and providing informative responses based on user queries.
