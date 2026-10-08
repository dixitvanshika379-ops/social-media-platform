SOCIAL MEDIA PLATFORM

Overview

Social Media Platform is a mini social networking website developed using Django. The platform allows users to create accounts, share posts, like posts, comment on posts, follow other users, and manage their profiles.

Objective

The main objective of this project is to develop a simple social media platform where users can connect and interact with each other through posts, comments, likes, and follows.

Features

- User Registration
- User Login and Logout
- User Profiles
- Edit Profile
- Bio and Profile Image
- Create Posts
- Like and Unlike Posts
- Add Comments
- Follow and Unfollow Users
- Followers and Following Count
- Django Admin Panel

Technologies Used

- Python
- Django
- SQLite
- HTML
- CSS
- Django Templates

Database Models

The project uses the following database entities:

- User
- Profile
- Post
- Comment
- Follow

Likes are implemented using a Many-to-Many relationship between Posts and Users.

Main Functionalities

User Authentication

Users can register for an account and securely log in and log out.

Posts

Logged-in users can create posts and view posts shared by other users.

Likes

Users can like or unlike posts.

Comments

Users can add comments to posts and view existing comments.

Follow System

Users can follow or unfollow other users.

Profile Management

Users can view their profile and update their bio and profile image.

Project Structure

social-media-platform/
    socialmedia/
        settings.py
        urls.py
    socialapp/
        migrations/
        templates/
            socialapp/
                home.html
                login.html
                register.html
                profile.html
                edit_profile.html
        static/
            socialapp/
                style.css
        models.py
        views.py
        admin.py
    db.sqlite3
    manage.py
    README.md

How to Run the Project

1. Activate Virtual Environment

.\venv\Scripts\Activate.ps1

2. Apply Migrations

python manage.py migrate

3. Start Django Server

python manage.py runserver

4. Open the Website

http://127.0.0.1:8000/

Django Admin

The Django administration panel can be accessed at:

http://127.0.0.1:8000/admin/

The admin panel allows management of users, profiles, posts, comments, and follows.

Future Scope

The project can be further improved by adding:

- Image upload for posts
- Real-time notifications
- Direct messaging
- Search functionality
- News feed based on followed users
- Improved responsive design
- JavaScript-based interactive features

Conclusion

This project demonstrates the development of a basic social networking platform using Django. It provides essential social media functionalities such as authentication, profiles, posts, likes, comments, and a follow system.