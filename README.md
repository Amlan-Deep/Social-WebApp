# Social-WebApp

This repository contains the source code for a Social WebApp, a web application that allows users to connect and interact with each other. The Social WebApp provides a platform for users to create profiles, share posts, like and comment on posts, and engage in various social activities.

## Features
User Registration and Authentication: Users can create accounts and log in securely to the Social WebApp.

User Profiles: Each user has a profile page where they can provide information about themselves, such as a profile picture, bio, and other details.

Post Creation and Sharing: Users can create posts and share them with their friends or the public. Posts can include text, images, or videos.

Like and Comment System: Users can like posts and leave comments on them, enabling interaction and engagement among users.

Friends and Followers: Users can connect with other users by sending friend requests and following each other's profiles.

Notifications: Users receive notifications for activities related to their posts, comments, and friend requests.

Search Functionality: Users can search for other users, posts, or specific content within the Social WebApp.

Installation
To set up the Social WebApp locally, follow these steps:

## Clone the repository:
bash
Copy code
git clone https://github.com/Amlan-Deep/Social-WebApp.git
Install the required dependencies. It is recommended to use a virtual environment:
bash
Copy code
cd Social-WebApp
python -m venv env
source env/bin/activate  # On macOS/Linux
.\env\Scripts\activate  # On Windows
pip install -r requirements.txt
Set up the database. By default, the Social WebApp uses SQLite as the database. Apply migrations to create the necessary tables:
bash
Copy code
python manage.py migrate
Run the development server:
bash
Copy code
python manage.py runserver
Open your web browser and navigate to http://localhost:8000 to access the Social WebApp.
Contributing
Contributions to the Social WebApp are welcome! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the established coding style and conventions.

License
The Social WebApp is licensed under the MIT License. You are free to use, modify, and distribute the code for personal or commercial purposes.
