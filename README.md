# Music-Management-System
This Spotify-style music management system is built for clean execution and efficiency. It integrates user signup and sign-in for controlled access, supports full song database management including add, edit, modify, and delete operations, and maintains structured storage for reliability. On top of that, it delivers fast, case-insensitive search by song title or artist through a simple menu-driven interface.

# User Signup & Sign-in & Authentication

Overview :
This module implements a basic user authentication system with signup and sign-in functionality using an in-memory dictionary.

Features :
Preloaded user accounts,
New user registration (Signup),
Existing user login (Sign-in),
Email-based user identificatio,n
Input validation for age,

# Songs Management System 1 

Overview :
This module is designed for developers to manage a song database.

Features :
Load song data from a file,
View the complete songs database,
Delete a song by artist and title,
Modify album, genre, or duration of a song,
Uses nested dictionary structure (Artist → Songs),

# Songs Management System 2

Overview :
This module allows users to search songs from a text-based song database by song title or artist name.

Features :
Loads song data from songs_database.txt,
Search song by exact title,
Search all songs by a specific artist,
Case-insensitive search,
User-friendly menu-driven interface,

# Project Structure
- User Signup & Sign-in & Authentication.py  :
  Handles user registration, login, and validation
- Songs Management System 1.py :  
  Admin CRUD operations for managing the song database
- Songs Management System 2.py  :
  User-facing song search functionality

# Branches
- The whole project is maintained under a single repository.
- The song management systems and the user sign-in & signup & authentication was created and the pulled to the main code using the pull request.

# Usage Guide
- Run the application to start the program.
- Users are prompted to sign up or sign in.
- Access is role-based:

  **Developers/Admins**
  - Add, view, modify, and delete songs in the database.
  
  **Users**
  - Search songs by title or artist name.
- All searches are case-insensitive.
- The application uses a clear, menu-driven interface.

