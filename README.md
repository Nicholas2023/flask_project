# Flask Blogging Site Project :smile:

This repository contains the code and resources for my journey in backend development using the Flask web framework to build a full-fledged blogging website. This project aims to help me enhance my skills in web development, database management, and backend programming.

## Project Overview

In this project, I will be developing a blogging website where users can:

- Create an account with a username and password.
- Log in and log out of their accounts.
- Create, edit, and delete blog posts.
- View blog posts created by other users.
- Comment on blog posts.

This project will cover various aspects of backend development, including:

- User authentication and authorization.
- Database management with SQLAlchemy.
- Routing and URL handling using Flask.
- Templating with Jinja2.
- Handling form submissions.
- Implementing user sessions.
- Managing and storing user-generated content.

## Project Structure

The project is organized as follows:

- `app.py`: The main application file where Flask is initialized and routes are defined.
- `config.py`: Configuration settings for the application (e.g., database URI, secret key).
- `models.py`: Database models defined using SQLAlchemy.
- `routes.py`: Route handlers for different parts of the application.
- `templates/`: HTML templates for rendering web pages.
- `static/`: Static files (e.g., CSS, JavaScript, images).
- `forms.py`: Form classes for handling user inputs.
- `requirements.txt`: List of required Python packages for this project.
- `README.md`: You are reading it now!

## Getting Started

Follow these steps to set up and run the Flask blogging site on your local machine:

1. Clone the repository:

   ```bash
   git clone https://github.com/Nicholas2023/flask_project.git
   ```

2. Create a virtual environment (recommended):

   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

4. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

5. Configure the application:

   - Create a `.env` file in the project root and set the following variables:

     ```
     SECRET_KEY=your_secret_key
     SQLALCHEMY_DATABASE_URI=your_database_uri
     ```

   Replace `your_secret_key` with a secret key for your application and `your_database_uri` with the URI of your database.

6. Initialize the database:

   ```bash
   flask db init
   flask db migrate
   flask db upgrade
   ```

7. Run the application:

   ```bash
   flask run
   ```

   The application should now be running on `http://localhost:5000`.

## Usage

- Visit the website in your web browser by going to `http://localhost:5000`.
- Create a new account or log in with existing credentials.
- Start creating, editing, and deleting blog posts.
- Interact with other users by commenting on their posts.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Your contributions are highly appreciated.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

I'd like to thank the Flask community and the open-source contributors whose work has made this project possible. Additionally, I appreciate any guidance and support from mentors and fellow developers throughout this learning journey.

Happy coding! 🚀
