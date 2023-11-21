# Countrynator - Your Interactive Geography Tutor

Welcome to Countrynator, an all-in-one web application designed to boost your geography knowledge through engaging quizzes, informative resources, and personalized user experiences. Developed using Flask, SQLite, and cutting-edge web development technologies, Countrynator offers a user-friendly platform for users to explore and challenge their geography knowledge.

## Features

### Learn Tab
The Learn tab allows users to search for specific countries and access comprehensive information, including capital cities, currencies, and populations. The platform optimizes data retrieval by loading a JSON dataset during initialization.

### Play Tab
The Play tab offers an interactive quiz experience. Users can choose a continent and answer 10 random questions. The quiz algorithm generates diverse questions about the capital or currency of randomly selected countries, ensuring a unique quiz every time.

### User Tab
Countrynator provides a personalized experience with user accounts. Users can register and log in to save quiz results and monitor their progress. Quiz results are stored in an SQLite database, enabling users to review past quizzes and sort them based on date or score.

## Technology Stack
- **Flask**: A Python web framework for efficient web development.
- **SQLite**: A lightweight, serverless database engine for storing user data and quiz results.
- **SQLAlchemy ORM**: A flexible Object-Relational Mapping library for seamless database operations.
- **Werkzeug Security**: Ensures password hashing for enhanced user data privacy.

## Getting Started
1. Clone the repository: `git clone https://github.com/your-username/countrynator.git`
2. Navigate to the project directory: `cd countrynator`
3. Install dependencies: `pip install -r requirements.txt`
4. Run the application: `python app.py`
5. Access the application at http://localhost:5000 in your web browser.

## Contributing
We welcome contributions to the project. Feel free to open issues or create pull requests. Your feedback and improvements are highly appreciated.

## License
This project is licensed under the MIT License. Please see the LICENSE file for details.