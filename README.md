# SocialScale-Platform

## Project Description: 
You have been tasked with designing a scalable and fault-tolerant social media platform that allows users to create and share posts. The platform should be able to handle a large number of concurrent users and support real-time notifications and messaging. You will use a combination of MongoDB, Redis, Nginx Load Balancer, and queuing technologies like Kafka and RabbitMQ or Redis to implement this platform.
## Requirements:
Your solution should include the following components:</br>
● A MongoDB database to store information about the system.</br>
● A Redis cache to store frequently accessed data and improve performance.</br>
● An Nginx Load Balancer to distribute incoming requests to multiple servers and improve
availability.</br>
● A messaging system using Kafka or RabbitMQ to handle real-time notifications and
messaging between users.</br></br>
Your document-based database should include the following components:</br>
● Ability to store information about users, including their name, username, email, password, date of birth, and list of friends.</br>


● Ability to store information about posts, including their title, content, author, date of creation, and number of likes and comments.</br>
● Ability to store information about comments, including their content, author, date of creation, and number of likes.</br>
● Ability to track notifications for users, including notifications for new posts, comments, and likes.</br>
● Ability to generate reports on user activity, including posts created, comments created, and likes given and received.
Considerations:</br>
● Your solution should be containerized using Docker, and you should provide a workable Docker Compose file for easy setup and deployment.</br>
● Submit your complete project as a zip file, including all source code, configuration files, Docker files, and documentation.</br>
● Learning outcome mapping for each question is mentioned in front of each.</br>
## Tasks:</br>
1. A MongoDB database to store information about users, posts, comments, and notifications. </br>
2. A Redis cache to store frequently accessed data and improve performance. </br>
3. An Nginx Load Balancer to distribute incoming requests to multiple servers and improve
availability.</br>
4. A messaging system using Kafka, RabbitMQ, or Redis to handle real-time notifications and
messaging between users.</br>
5. Scripts to populate the database with sample data for testing and generate sample reports
on user activity. </br>
6. Scripts to perform basic CRUD operations on the database, including creating, reading,
updating, and deleting records.</br>


## (Optional: good to think about) Questions:</br>
1. What are the trade-offs between using a normalized schema versus a denormalized schema in MongoDB? Which approach would you recommend for the social media platform database and why? </br>
2. How would you design an index in MongoDB to support a query that searches for all posts with a particular tag? How would this index be impacted if the number of posts in the database grows significantly? </br>
3. Suppose you need to add a new field to the posts collection to track the location where the post was created. How would you modify the existing documents in the collection to include this new field? What are some potential issues that could arise from this modification? </br>
4. How would you use Redis as a cache for frequently accessed data in the social media platform? What are the benefits and drawbacks of this approach? How would you handle cache invalidation and cache expiration? </br>
5. How would you use Kafka or RabbitMQ to handle real-time notifications and messaging between users on the social media platform? What are the benefits and drawbacks of each messaging system? How would you ensure message persistence and replication? </br>
6. In a multi-user environment, how would you handle concurrency control and data consistency between MongoDB and Redis in the social media platform? What are the benefits and drawbacks of this approach? </br>
