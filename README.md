# MusicBase

## Overview

**MusicDBMS** is a comprehensive music catalog management system designed to organize and manage music data. The database allows users to interact with songs, playlists, creators, listeners, and other related entities, enabling efficient retrieval and manipulation of music-related data.

The system supports:
- User management for listeners and creators.
- Song metadata storage including artists, albums, and platforms.
- Playlist creation and sharing.
- Song recommendations based on user ratings and preferences.
- Integration with movie data.

## Repository Contents

This repository includes the following essential files and documentation to help set up and understand the MusicDBMS:

1. **SRS (Software Requirements Specification)**  
   Detailed documentation of the system's functional and non-functional requirements, outlining the purpose, scope, and objectives of the MusicDBMS project.

2. **DDL (Data Definition Language) Statements**  
   SQL scripts that define the schema of the database, including the creation of tables such as `users`, `songs`, `playlists`, `platforms`, `subscriptions`, and more. This script establishes the relationships between these entities via foreign keys and constraints.

3. **ER Diagram (Entity-Relationship Diagram)**  
   A graphical representation of the database structure, illustrating the relationships between entities like `users`, `songs`, `playlists`, and `platforms`. The ER diagram provides an intuitive overview of how different components interact within the system.

4. **Retrieval Queries**  
   A collection of SQL queries that allow for retrieving key information from the database. These queries can be used to:
   - Fetch songs by a specific artist.
   - Retrieve playlists created by a user.
   - Get recommendations based on song ratings.
   - List songs available on a particular platform.
   - Display all creators involved in a song.


