Django Social Network
Introduction

Welcome to Django Social Network, an application crafted with Django to provide a comprehensive platform for social interaction and content sharing. This project leverages Django's powerful features, including its authentication framework, to offer user registration, custom user profiles, and social media integrations. It's designed to showcase the versatility of Django in creating complex web applications.
Features

    User Authentication: Utilize Django's authentication framework for secure user registration and login functionality.
    Custom User Profiles: Extend Django's default User model to include additional profile information tailored to the social networking context.
    Social Authentication: Integration with python-social-auth module allows users to sign in using their social media accounts, streamlining the authentication process.
    Dynamic Content with AJAX: AJAX views and jQuery are used to update content dynamically, providing a seamless user experience without the need for page reloads.
    Bookmarklet Creation: Users can interact with the application from any webpage using a custom jQuery bookmarklet, promoting content sharing and engagement.
    Image Handling: Generate and manage image thumbnails with easy-thumbnail for efficient content presentation.
    Activity Stream: Track and display user activities within the network, fostering a vibrant and interactive community.
    Advanced Data Models: Employ many-to-many relationships and generic relations to model complex interactions between users and content.
    Optimized Performance: Leverage Django's QuerySet optimization and Redis caching to ensure the application scales efficiently and remains responsive under load.

Getting Started
Prerequisites

    Python 3.8 or later
    Django 3.0 or later
    Redis

Installation

    Clone the repository:

    bash

git clone https://github.com/yourusername/Django-Social-Network.git

Navigate to the bookmarks project directory:

bash

cd Django-Social-Network/bookmarks

Install the required dependencies:

bash

pip install -r requirements.txt

Set up your environment variables:

    Create a .env file in the bookmarks directory with necessary configurations.

Apply database migrations:

bash

    python manage.py migrate

Running the Server

Start the Django development server with SSL certification for development:

bash

python manage.py runserver_plus --cert-file cert.crt

This command runs the server with HTTPS, enabling secure local development testing.
