# Movie Recommendation System

This is a simple **Movie Recommendation System** built using the **TMDB API** and **Streamlit**. It recommends 5 movies based on user preferences.

## Features

- Fetches data from the TMDB API.
- Displays detailed movie recommendations.
- User-friendly interface powered by Streamlit.

## How It Works

1. The user provides input (e.g., favorite genre, movie name, or preferences).
2. The application interacts with the TMDB API to fetch movie data.
3. Recommends the top 5 movies matching the input criteria.

## Tech Stack

- **Backend**: Python
- **Frontend**: Streamlit
- **API**: TMDB API

## Setup and Installation

Follow the steps below to run the project on your local machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/SadabAli/Movie-Recomment-System.git
   cd Movie-Recomment-System
   ```

2. Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate # For Windows: env\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Add your TMDB API key:
   - Create a `.env` file in the root directory.
   - Add your API key to the file:
     ```env
     TMDB_API_KEY=your_tmdb_api_key_here
     ```

5. Run the Streamlit application:
   ```bash
   streamlit run app.py
   ```

## Usage

1. Open the app in your browser (default: `http://localhost:8501`).
2. Enter your preferences or select a movie.
3. View the top 5 recommended movies with details like title, description, and rating.

## Screenshots

![Screenshot 2025-01-16 141659](https://github.com/user-attachments/assets/efd30f2a-b018-4bc6-99b2-cb9c854af750)


## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue.

## License

This project is licensed under the MIT License.

## Acknowledgments

- **TMDB API** for providing movie data.
- **Streamlit** for making the UI development simple and intuitive.
