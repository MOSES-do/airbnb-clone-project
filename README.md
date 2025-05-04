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


 Feature Breakdown
    User Management:  A secure system for user registration, authentication, and profile management.
    Property Management: This feature makes property listing creation, updates, and retrieval possible ensuring users can browse various           categories of properties both available and soldout
    Booking System: Allows for users to reserve properties and manage booking details.


 API Security
 Authentication/Authorization: Users authentication will be implemented using the conventional username/password and Oauth2.0/social login and  RBAC (role based authroization)
 Rate limiting: This technique will be used to monitor how many requests a user or system can make to a server within a certain time period.
 Input Validation & Sanitization: All user inputs will be sanitized to prevent sql injection and cross-site scripting
 Encryption: Ensure server is SSL/TLS compliant to encrypt all data in transit and redirect all HTTP traffic to HTTPS.
 Password Security: Passwords will be stored using hashing technique such as bcrypt

 Security is essential to prevent breach of user privacy and protect the business from running at a loss by way of funds/sensitive data, compliance with laws and standards and downtimes.

 CI/CD Pipeline:
 CI/CD pipelines are automated workflows that help streamline and improve the software development process by automating code integration,    testing, and deployment.

 Tools for CI/CD
 Jenkins, GitHub Actions, GitLab CI/CD and AWS CodePipeline
   

