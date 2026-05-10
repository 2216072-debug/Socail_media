# Social Media SQL Project

## Project Overview
This project is a Social Media Database Management System built using SQL.  
It simulates the backend structure of a social media platform including users, posts, comments, likes, followers, hashtags, notifications, media, and trending posts.

The project demonstrates:
- Database design
- Table relationships
- Primary & Foreign Keys
- SQL queries
- Data handling
- Social media analytics concepts

---

## Database Features

### User Management
- User profiles
- Followers system
- User locations

### Post Management
- Posts creation
- Media uploads
- Post locations
- Post views

### Engagement Features
- Likes
- Comments
- Shares
- Hashtags

### Analytics
- Trending posts
- Engagement tracking

---

## Tables Included

| Table Name | Description |
|------------|-------------|
| social_media_users | Stores user information |
| social_media_profiles | Stores profile details |
| social_media_posts | Stores posts |
| social_media_comments | Stores comments |
| social_media_likes | Stores likes |
| social_media_followers | Stores followers |
| social_media_hashtags | Stores hashtags |
| social_media_post_hashtags | Maps hashtags to posts |
| social_media_media | Stores media files |
| social_media_notifications | Stores notifications |
| social_media_post_views | Stores post views |
| social_media_post_location | Stores post locations |
| social_media_locations | Stores location details |
| social_media_shares | Stores post shares |
| social_media_trending_posts | Stores trending posts |

---

## Concepts Used
- CREATE TABLE
- PRIMARY KEY
- FOREIGN KEY
- JOINS
- GROUP BY
- ORDER BY
- Aggregate Functions
- Relationships
- Normalization

---

## Tools Used
- MySQL
- SQL
- GitHub

---

## Learning Outcome
Through this project, I improved my understanding of:
- Relational Database Design
- SQL Query Writing
- Real-world Database Structure
- Data Relationships
- Social Media Data Handling

---

## Future Improvements
- Add Stored Procedures
- Add Triggers
- Add Views
- Add Advanced Analytics Queries
- Build Power BI Dashboard using this database

---

## Author
Arun  
B.E Computer Science Engineering  
Aspiring Data Analyst / SQL Developer

## How to Download and Run This Project

### Step 1 — Clone the Repository

Open CMD or Git Bash and run:

git clone https://github.com/2216072-debug/Social_media.git

### Step 2 — Open Project Folder

cd Social_media

### Step 3 — Install MySQL

Download and install:
- MySQL Server
- MySQL Workbench

### Step 4 — Create Database

Run:

CREATE DATABASE social_media;

USE social_media;

### Step 5 — Execute SQL Files

Run all `.sql` files in MySQL Workbench in the correct order.

Recommended order:

1. social_media_users.sql
2. social_media_profiles.sql
3. social_media_locations.sql
4. social_media_posts.sql
5. social_media_media.sql
6. social_media_comments.sql
7. social_media_likes.sql
8. social_media_followers.sql
9. social_media_hashtags.sql
10. social_media_post_hashtags.sql
11. social_media_post_location.sql
12. social_media_notifications.sql
13. social_media_post_views.sql
14. social_media_shares.sql
15. social_media_trending_posts.sql

### Step 6 — Verify Tables

Run:

SHOW TABLES;

### Step 7 — Run Queries

Example:

SELECT * FROM social_media_users;

SELECT * FROM social_media_posts;
