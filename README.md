# Blog Website


This is a dynamic and user-friendly blog website built with the Django web framework. It includes features such as responsive design, user authentication, and a content management system, providing an interactive experience for users to create, read, and engage with blog posts.

#      Features
- **User Authentication:** Users can sign up, log in, and manage their accounts.
- **Responsive Design**: Optimized for both desktop and mobile devices to ensure accessibility and usability.
- **Content Management**: Users can create, edit, and delete their own blog posts.
- **Comments Section:** Allows readers to comment on blog posts, fostering engagement and interaction.
- **Search Functionality:** Users can search for posts by keywords.

**Tech Stack**
Backend: Django
Frontend: HTML, CSS, JavaScript (for interactive elements)
Database: SQLite (can be upgraded to PostgreSQL for production)


**Installation**
Clone the Repository
bash
Copy code
git clone https://github.com/your-username/blog-website.git

cd blog-website

Create a Virtual Environment

bash
Copy code
python -m venv env

source env/bin/activate 

# On Windows use `env\Scripts\activate`

Install Dependencies

bash
Copy code
pip install -r requirements.txt
Set Up Database

bash
Copy code
python manage.py migrate
Create a Superuser

bash
Copy code
python manage.py createsuperuser
Run the Development Server

bash
Copy code
python manage.py runserver
Visit http://127.0.0.1:8000/ to see the application.

**Usage**
Admin Panel: Access the Django admin panel at /admin/ to manage users, posts, and comments.
Creating Posts: Users can create and publish posts after logging in.
Commenting: Registered users can comment on posts to engage with content.
Testing
Run the following command to test the application:

bash
Copy code
python manage.py test
Contributing
Fork the repository
Create a new branch (git checkout -b feature-branch)
Make your changes and commit (git commit -m "Added feature XYZ")
Push to the branch (git push origin feature-branch)
Create a Pull Request
License
This project is licensed under the MIT License.
