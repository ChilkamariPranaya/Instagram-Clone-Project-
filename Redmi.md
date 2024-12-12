# INSTAGRAM DATABASE PROJECT

## DESCRIPTION
This repository contains the SQL script `Instagram.sql` to create and manage a relational database inspired by Instagram.
It includes tables, relationships, and possibly queries to handle core functionalities like user management, posts, likes, comments, and more.

## FEATURES

- USER MANAGEMENT: Users, their profiles, and authentication.
- POST HANDLING: Create, edit, delete, and retrieve posts.
- ENGAGEMENTS: Likes and comments functionality.
- RELATIONSHIPS: Follow/unfollow system.
- DATA STRUCTURE: Efficient table relationships and indexing.

## INSTALLATION

1. Clone the repository:
   ```bash
   git clone https://github.com/PAVITRA1919/Instagram_database_clone.git
   ```

2. Set up a MySQL database server on your machine or use a remote database service.

3. Open the SQL script file `Instagram.sql` in a database client (e.g., MySQL Workbench) or a command-line interface.

4. Run the script to create the database and its tables:
   ```sql
   SOURCE /path/to/Instagram.sql;
   ```

5. Verify the database structure and relationships.

## USAGE

1. Connect your application to the database using your preferred programming language (e.g., Python, Node.js, Java).

2. Use the database to:
   - Add, update, or retrieve user data.
   - Handle user posts and interactions.
   - Implement follow/unfollow functionality.

3. Extend the SQL script as needed to accommodate additional features.

## DATABASE DESIGN

The database includes the following key tables (assumptions based on functionality):

- USERS: Stores user details such as username, email, password, and profile information.
- POSTS: Contains details of user posts, including captions, media, timestamps, etc.
- LIKES: Tracks which users liked which posts.
- COMMENTS: Stores comments made on posts.
- FOLLOWERS: Tracks user follow/unfollow relationships.




