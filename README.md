# ToDo List 
======================

## Overview
------------

This project is a microservice for creating, reading, updating, and deleting (CRUD) notes. It is built using Spring IoC, Spring Boot, JPA, and Kotlin's Data Classes.

## Features
------------

* Create notes with title, content, and tags
* Read notes by ID, title, or tags
* Update notes with new title, content, or tags
* Delete notes by ID
* Uses Spring IoC for dependency injection
* Uses Spring Boot for auto-configuration and embedded Tomcat server
* Uses JPA for database persistence
* Uses Kotlin's Data Classes for concise and expressive data modeling

## Technical Details
--------------------

* **Backend**: Spring Boot 2.x, Spring IoC, JPA (Hibernate)
* **Database**: H2 in-memory database for development, MySQL for production
* **Language**: Kotlin 1.6.x
* **Build Tool**: Gradle 6.x

## API Endpoints
----------------

### Note Controller

* **POST /notes**: Create a new note
* **GET /notes**: Get all notes
* **GET /notes/{id}**: Get a note by ID
* **PUT /notes/{id}**: Update a note
* **DELETE /notes/{id}**: Delete a note

### Note Model

* **id**: Unique identifier for the note (Long)
* **title**: Title of the note (String)
* **content**: Content of the note (String)
* **tags**: List of tags for the note (List<String>)

## Getting Started
-------------------

1. Clone the repository: `git clone https://github.com/your-username/notes-microservice.git`
2. Build the project: `./gradlew build`
3. Run the application: `./gradlew bootRun`
4. Access the API endpoints using a tool like Postman or cURL

## Contributing
---------------

Contributions are welcome! Please submit a pull request with a clear description of the changes.

## License
------------

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
------------------

* Spring Boot and Spring IoC for making Java development easier and more enjoyable
* Kotlin for its concise and expressive syntax
* JPA and Hibernate for simplifying database persistence
