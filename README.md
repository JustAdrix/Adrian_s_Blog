# Prerequisites

To run the application, you need python 3.12, venv and pip to be installed.

# Python 3.12
You need to have Python installed, at least the version 3.12 . Check if you already have Python installed running the Terminal command: python --version. If the result shows a version number, Python is already installed. If not, you can download it here: https://www.python.org/downloads/

# GIT
It helps you download the project from GitHub, you can download it here: https://git-scm.com/downloads

# venv (Virtual Environment)
You need to create a virtual environment (venv) before running the application. For more information on how you create one, follow this link: https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment


## Adrian_s_Blog Setup
I. Create a folder in your computer where you'd like to store the code to run the app.

II. Download Adrian_s_Blog project in tht folder.
```commandline
git clone https://github.com/JustAdrix/Adrian_s_Blog.git
```
III. Start your favorite IDE ( my is PyCharm https://www.jetbrains.com/pycharm/download/?section=windows#section=windows )

IV. Open Adrian_s_Blog project.

V. Ceate your vitrual enviroment ( is optional but is BEST PRACTICE ) 
```commandline
python -m venv venv
```
VI. Activate the virtual environment.
```commandline
venv\Scripts\activate
```
VII. The libraries used are Django 5.0.1 and Pillow 10.2.0. 
  To install them, run in terminal follow command.
```commandline
pip install -r requirements.txt
```
VIII. Start the development server.
```commandline
python manage.py runserver
```
IX. Access the application at http://127.0.0.1:8000/

#
# Adrian`s Blog 
#

Welcome to Adrian_s_Blog, a platform where Adrian, the blog owner, shares insightful posts, and visitors can engage through comments. This dynamic blog, powered by Python's Django framework, offers a seamless experience for both content creation and interaction.

# Homepage:

Displays Adrian's latest 3 posts, showcasing titles, brief summaries, and associated images.
Visitors can click on each post to access its detailed content.

# Post Details Page:

Features the full content of the post, including image, titles, text, and the date of the last update.
An option for visitors to save posts for later reading.
Visitors can leave comments, fostering a vibrant community discussion.

# Commenting Section:

Provides a user-friendly form for visitors to leave comments, including fields for name, email address, and the comment text.
Robust validation ensures data integrity, and error messages are displayed if needed.

# Saved for Later Page:

Lists posts saved by visitors for future reading.
Visitors can remove posts from their saved list when they're done reading.
New Post Creation Page (Owner's Access):

An authenticated owner can create new posts using a form with fields for title, content, and image upload.
Data validation ensures accurate and meaningful posts.
A straightforward publishing process for sharing content with the audience.

# User Authentication and Authorization:

Secure authentication for the owner to create, edit, and delete their posts.
The owner can view a list of all their posts and perform actions like editing or deleting.
Backend Data Management (SQLite3):

Utilizes the SQLite3 database to store data, including posts, comments, and user information.

# Image Handling (Pillow):

Pillow is employed for efficient image manipulation and management associated with blog posts.

# Responsive User Interface:

Adopts a responsive design for an optimal user experience across various devices.

# Security Measures:

Implements secure authentication practices and data validation to prevent potential vulnerabilities.

# Comment and Post Moderation:

Enables the owner to moderate and manage comments, edit or delete existing posts.


Allows filtering of posts based on tags or relevant categories.
Adrian_s_Blog provides an engaging and secure platform for content creation, user interaction, and community building, all developed with the power and flexibility of Python, Django, Pillow, and SQLite3. Explore, share, and join the conversation!
