# chat-application-backend-in-PHP
# PHP Chat Application Backend

A basic backend for a chat application built using PHP and the Slim framework. It offers a RESTful JSON API to handle user creation, chat group management, message sending, and fetching messages within groups.

## Features

- Create and manage users
- Create and join chat groups
- Send messages within groups
- Retrieve messages from groups

## Technologies Used

- PHP
- Slim Framework
- Eloquent ORM (Illuminate Database)
- SQLite (for development)
- Composer
- PHPUnit (Testing Framework)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/dhanushprakash/chat-application-backend-in-PHP
   cd php-slim-chat-backed
2. **Install dependencies:**

   ```bash
   composer install
3. **Set up the database:**

   ```bash
    mkdir -p database
    touch database/database.sqlite
    php database/create_tables.php

4. **Start the application:**

   ```bash
   php -S localhost:8080 -t public

## API Endpoints
 - POST /users - Create a new user
 - GET /users/{id} - Get user details
 - POST /groups - Create a new group
 - POST /groups/{groupId}/join - Join a group
 - POST /groups/{groupId}/messages - Send a message in a group
 - GET /groups/{groupId}/messages - List messages in a group

## Contact

 - Author: Dhanush Prakash
 - Email: dhanushprakash08@gmail.com
 - contact: 07428735299
