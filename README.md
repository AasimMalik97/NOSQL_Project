# README for GitHub Repository

## MongoDB, Neo4j, and Redis Integration for Movie Recommendation System

### Description:
This project demonstrates the integration of three NoSQL databases—MongoDB, Neo4j, and Redis—to build a movie recommendation system. The system recommends movies to users based on genres of movies they like and their relationships with other users.

### Features:
- Store and retrieve detailed movie data with MongoDB.
- Model and query user-movie relationships using Neo4j.
- Cache frequently accessed data with Redis for enhanced performance.

### Prerequisites:
- Python 3.7+
- MongoDB
- Neo4j
- Redis
- Libraries: `pymongo`, `neo4j`, `redis`

### Setup:
1. Install required libraries:
   ```bash
   pip install pymongo neo4j redis
   ```

2. Start the MongoDB, Neo4j, and Redis servers locally or on your preferred cloud service.

3. Populate the databases with sample data:
   - MongoDB: Use the provided script to insert movie data.
   - Neo4j: Use Cypher queries to create user and movie nodes with relationships.
   - Redis: Cache sample user preferences and recommendations.

### How to Run:
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Execute the scripts to interact with each database and see the integration in action.

3. Query examples:
   - MongoDB: Retrieve all Sci-Fi movies.
   - Neo4j: Recommend movies based on user relationships and genres.
   - Redis: Access cached recommendations for a user.

### Example Use Case:
- User 104 likes a movie of genres Action and Drama.
- Neo4j recommends movies with similar genres that User 104 hasn’t liked yet.
- MongoDB retrieves detailed information about these recommendations.
- Redis caches these recommendations for quick future access.

### License:
This project is licensed under the MIT License.

### Contributors:
- Joe khater
- Aasim malik
