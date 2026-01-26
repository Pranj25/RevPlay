REVPLAY
CONSOLE BASED MUSIC STREAMING APPLICATION
========================================

PROJECT DESCRIPTION
-------------------
RevPlay is a Java console-based music streaming application that simulates the core features of a real music platform.
It allows users to search songs, manage playlists, mark favorites, and view listening history.
Artists can upload songs, create albums, and track song play statistics.

The project focuses on backend development using Core Java and JDBC with MySQL.

FEATURES
--------

USER FEATURES:
- User registration and login
- Search songs by title, genre, artist, or album
- Browse music library
- Play, pause, next (text-based simulation)
- Create public or private playlists
- Add and remove songs from playlists
- View playlists
- Mark songs as favorites
- View favorite songs
- View recently played songs
- View listening history
- Logout

ARTIST FEATURES:
- Artist registration and login
- Create and manage artist profile
- Upload songs
- Create albums and add songs
- Update or delete songs and albums
- View play count statistics
- View users who favorited songs

TECHNOLOGIES USED
-----------------
- Java (Core Java)
- MySQL
- JDBC
- JUnit
- Log4j
- Git and GitHub

NOTE:
HTML and CSS are not used because this is a console-based application.
The backend can be extended to a web-based UI in the future.

APPLICATION ARCHITECTURE
------------------------
- Controller Layer: Handles menu and user input
- Service Layer: Business logic and validations
- DAO Layer: Database operations using JDBC
- Model Layer: POJO classes
- Database Layer: MySQL

PROJECT STRUCTURE
-----------------
RevPlay
|
|-- model
|-- dao
|-- service
|-- controller
|-- util
|-- test
|
|-- MainApp.java

DATABASE DETAILS
----------------
Database Name: revplay_db

Tables:
- users
- artists
- songs
- albums
- playlists
- playlist_songs
- favorites
- history

HOW TO RUN
----------
1. Install Java JDK (8 or above)
2. Install MySQL Server
3. Import the project into Eclipse / IntelliJ / VS Code
4. Create database using the provided SQL script
5. Update database credentials in DBConnection.java
6. Run MainApp.java

TESTING
-------
JUnit is used for testing core functionalities like login and playlist creation.

LOGGING
-------
Log4j is used for logging user actions and errors.

FUTURE ENHANCEMENTS
-------------------
- Web-based UI using HTML and CSS
- REST APIs using Spring Boot
- Mobile application
- Music recommendation system

AUTHOR
------
Name: Pranjal Sanjay Palpattuwar
Email: palpattuwarpranjal@gmail.com
LinkedIn: https://www.linkedin.com/in/pranjal-palpattuwar-784874246

END OF FILE
-----------
