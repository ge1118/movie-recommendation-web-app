# Movie Recommender System
## Project Overview
This project presents a web-based movie recommender system that utilizes a collaborative filtering approach, built with Flask and JavaScript. Users can search for movies, receive personalized recommendations, and manage their favorites. The system employs a Single Value Decomposition (SVD) / Matrix Factorization technique to generate movie recommendations.

## Key Features
- Movie Recommendation: Offers recommendations as users type in the search bar.
- Movie Suggestion: Offers alternative movie suggestions for users when their initial search doesn't match any titles in the database.
- Personalized Recommendations: Utilizes collaborative filtering for tailored movie suggestions.
- User Authentication: Secure login and registration functionality.
- Favorite Movies Management: Users can add or remove movies from their favorites list.

## Technologies
- Frontend: HTML, CSS, JavaScript
- Backend: Flask (Python)
- Database: SQLite
- Data Analysis: NumPy, Pandas
- Machine Learning: Implementation of SVD for recommendation

## Installation
### Prerequisites
- Python 3.x
- Pip (Python package manager)

### Setup
1. Clone the repository:
   ```git clone https://github.com/ge1118/movie-recommendation-web-app.git```
2. Navigate to the project directory:
   ```cd <project-directory>```
3. Install dependencies:
   ```pip install -r requirements.txt```

### Running the Application
Execute the following command to start the Flask server: 
```python app.py```

## Usage
-	Log In/Register: Access the system with user credentials.
-	Searching Movies: Search bar for finding movies.
-	Viewing Recommendations: Receive movie suggestions based on preferences.
-	Managing Favorites: Add or remove movies from the favorites list.

## Dataset
The system uses the ml-100k dataset from the [GroupLens Research Project](https://grouplens.org/datasets/movielens/100k/). Instructions for downloading and utilizing the dataset are provided within the application.

## Algorithm
The recommender system employs SVD / Matrix Factorization for generating movie suggestions. It normalizes user rating data and computes similarities to suggest movies similar to a user's preferences. The script SoftwareProject_MovieRecommender_SVD.py contains the implementation details.

## Deployment
This project is deployed on Heroku and is accessible online. You can interact with the live version of the application here: [Movie Recommender Web App](https://movie-recommendation-webapp-225db83e8b75.herokuapp.com/)

Deploying on Heroku offers a convenient and efficient hosting solution. However, it's important to note that applications hosted on Heroku's free tier may experience a delay when loading for the first time or after periods of inactivity. This happens because Heroku puts the application to sleep to conserve resources, leading to a cold start upon the next visit. Once the app is awakened, subsequent interactions should be faster until it goes into sleep mode again after a period of inactivity.

## Contributing
I welcome contributions! Please feel free to fork the repository, make changes, and submit pull requests.

## Contact
For questions or feedback, reach out at [leah.kim0118@gmail.com](mailto:leah.kim0118@gmail.com).

## Acknowledgments
GroupLens Research for providing the ml-100k dataset.
Flask community for their invaluable resources.
