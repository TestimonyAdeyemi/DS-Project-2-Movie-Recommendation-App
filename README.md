
[You can find the deployed app here](https://testimonyadeyemi-movie-recommendation-app-app-q1no5a.streamlit.app/)
---

## Introduction

The purpose of this project is to deploy a movie recommendation model on the web using Streamlit. The app suggests movies to users based on their preferences and utilizes content-based filtering techniques to make movie recommendations.

## Project Overview

The movie recommendation web app is designed to help users discover new movies that align with their interests and preferences. It takes advantage of the previously developed content-based recommendation model. Users can input a movie title they like, and the app will provide recommendations for similar movies.

## Deployment

The movie recommendation web app is deployed on a web server and can be accessed by users through a web browser. The app is hosted on a cloud platform, and users can interact with it without needing to install any software locally.

## Setup Instructions

To set up and run the movie recommendation web app, follow these steps:

1. Clone the project repository to your local machine.

2. Ensure you have Python installed on your system. You can download Python from the official website (https://www.python.org/downloads/).

3. Install the required Python packages using pip:

   ```bash
   pip install streamlit pandas requests
   ```

4. Run the Streamlit app using the following command:

   ```bash
   streamlit run app.py
   ```

5. The app will start, and you will be provided with a local URL (e.g., http://localhost:8501) that you can open in your web browser to access the app.

## Web App Features

- **Movie Selection**: Users can select a movie they liked from a dropdown list of available movies.

- **Recommendation**: When the user clicks the "Recommend" button, the app generates and displays a list of recommended movies based on the selected movie.

- **Movie Posters**: Along with movie titles, the app also displays movie posters for the recommended films.



## Conclusion

The movie recommendation web app is an excellent tool for movie enthusiasts looking to discover new films aligned with their tastes. By leveraging the content-based recommendation model, the app provides personalized movie suggestions. Users can access the app through their web browsers, making it convenient and user-friendly.

Follow the setup instructions provided in this README/report to run the app locally and explore movie recommendations. Enjoy using the movie recommendation web app!
