# airbnb-clone-project

Team Roles


Technology Stack
Django: A high-level Python web framework used for building the RESTful API.
Django REST Framework: Provides tools for creating and managing RESTful APIs.
PostgreSQL: A powerful relational database used for data storage.
GraphQL: Allows for flexible and efficient querying of data.
Celery: For handling asynchronous tasks such as sending notifications or processing payments.
Redis: Used for caching and session management.
Docker: Containerization tool for consistent development and deployment environments.
CI/CD Pipelines: Automated pipelines for testing and deploying code changes.

Database Design
To ensure a smooth flow from storage to accessing data. Some enities and fields required will are listed below.
 Users: id, name, email, address, phone_no
 Properties: prop_id, prop_type, prop_address, pricing
 Bookings: id, user_id, prop_type, arrival_time, departure_time
 Reviews, review_id, userid, user_review, rating
 Payments: id, user_id, card_type
