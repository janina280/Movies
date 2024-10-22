# Movies

Movies Documentation
## Overview
This is a movie catalog application built using Spring Boot and React. The app allows users to browse through a collection of movies using a carousel, watch trailers, and write reviews. Future versions of the app will include user authentication (login and register features).

### Technologies Used
Spring Boot: Java-based backend framework for building the REST API.

React: Front-end JavaScript library for building user interfaces.

HTML and CSS: Used for structuring and styling the user interface.

MongoDB: NoSQL database for storing movie and user data.

Visual Studio Code (VS Code): Integrated Development Environment (IDE) used for coding and debugging.

### How to Run
1. Clone the Repository:
* How to run the program
* Step-by-step bullets
```
git clone https://github.com/janina280/Movies
cd movies
```

2. Backend (Spring Boot):
* Ensure that you have Java and Maven installed.
* Configure your MongoDB database connection in application.properties.
* Run the Spring Boot application:
```
mvn spring-boot:run
```

3. Frontend (React):
* Navigate to the frontend folder:
```
cd frontend
```

Install dependencies:
```
npm install
```

Start the development server:
```
npm start
```

4. Open your browser and navigate to:
```
http://localhost:3000
```


### Features
* Movie Carousel: Users can browse through movies in a carousel format on the homepage.
* Watch Trailers: Each movie has a trailer available for viewing.
* Write Reviews: Users can write reviews for movies, which are saved in the MongoDB database.

### Upcoming Features:
User Authentication: Login and registration functionalities to manage personalized user data.

### Development Environment

Visual Studio Code (VS Code): The primary IDE for developing and debugging the application.

MongoDB: NoSQL database system used to store movies, reviews, and user details.

Backend (Spring Boot):
The backend uses Spring Boot to provide a REST API that the React frontend interacts with.
MongoDB is used to store movie data, user reviews, and other relevant information.
Configuration is stored in the application.properties file.

For example: 
``` spring.data.mongodb.uri=mongodb://localhost:27017/moviesdb```

Frontend (React):
The frontend is built with React and communicates with the backend API to display data dynamically.
CSS is used for styling the application and ensuring a responsive layout.
