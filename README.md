🎬 Movie Review REST API

A RESTful backend application built using Spring Boot and MongoDB Atlas that allows users to retrieve movies and post reviews.

🚀 Features

📌 Get all movies

🔍 Get movie by IMDb ID

✍️ Add review to a movie

🔗 MongoDB document relationship using @DocumentReference

🧱 Layered architecture (Controller → Service → Repository)

🌍 Environment-based configuration

☁️ Cloud-ready (can be deployed independently without frontend)


🛠 Tech Stack
Java 17

Spring Boot 2.7.x

Spring Data MongoDB

MongoDB Atlas

Maven

Lombok

Postman (API Testing)


📂 Project Structure
src/main/java/dev/sneha/movies
│
├── controller
│   ├── MovieController.java
│   └── ReviewController.java
│
├── service
│   ├── MovieService.java
│   └── ReviewService.java
│
├── repository
│   ├── MovieRepository.java
│   └── ReviewRepository.java
│
└── model
    ├── Movie.java
    └── Review.java


    
