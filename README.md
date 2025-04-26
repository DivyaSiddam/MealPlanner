Project Name: 

Meal Planner

Description:

This Flask application is designed to help users efficiently manage their meal plans, recipes, and personal data. It utilizes Flask-SQLAlchemy to handle database management, storing essential information such as user profiles, recipes, and meal plans. The app integrates Flask-Login for secure user authentication, allowing users to register, log in, and manage their profiles. Passwords are hashed using Flask-Bcrypt for added security. Users can create, edit, and delete meal plans, add and modify recipes, and even rate and favorite recipes. The app also provides the ability to export shopping lists in CSV format based on meal plans, making it easy for users to prepare for grocery shopping. It includes a search function to find recipes, as well as a section for users to share cooking tips with one another. A weekly summary feature helps users review their meal plans, The app's dynamic forms, built with Flask-WTForms, ensure smooth user interaction by validating input for tasks like registration, login, and recipe management. Overall, the application serves as a comprehensive tool for users to plan meals, manage recipes.

purpose:

The purpose of this Flask application is to provide users with a comprehensive and user-friendly platform for managing meal planning, recipes, and related tasks. It allows users to efficiently create and organize meal plans, add and modify recipes, and track grocery shopping lists. The app helps users manage their personal preferences and dietary needs by offering features like rating and favoriting recipes, sharing cooking tips. 

Value:

The value of this Flask application lies in its ability to simplify and enhance the user experience when it comes to meal planning, recipe management, and grocery shopping. By offering a centralized platform for users to organize meal plans, store and search for recipes, and track ingredients and costs, it saves users time and effort in their daily routine. The app also provides personalized features such as the ability to rate and favorite recipes, helping users to easily find the meals they enjoy most.


Technologies Used: 

The technologies used in the provided Flask application code are:

Flask: A micro web framework for building web applications in Python. It is used to create the server-side application and handle HTTP requests and responses.

Flask-SQLAlchemy: A Flask extension that simplifies integration with databases. It provides an ORM (Object Relational Mapper) for managing database operations.

Flask-WTF: A Flask extension that helps with handling forms, making it easier to work with forms in Flask applications. It integrates with WTForms.

WTForms: A form-handling library for Python. It provides tools for creating and validating web forms with various field types like text fields, passwords, select fields, and more.

Flask-Bcrypt: A Flask extension for handling password hashing and security using bcrypt. It is used for safely storing and verifying user passwords.

Flask-Login: A Flask extension that manages user sessions. It helps with login management, protecting views that require login, and keeping track of users' login state.

Pandas: A data manipulation and analysis library for Python. It is used for working with CSVs and data manipulation, which can be useful for handling meal plans, recipes, or user data in your application.

CSV/IO: The Python standard library modules csv and io are used for reading and writing CSV files. These modules allow you to import/export data to/from your application in CSV format.

datetime and timedelta: The Python standard library for working with dates and times. datetime is used to handle date and time in the application, such as calculating meal plan dates or deadlines.

Flask Response: The Response class from Flask is used to return HTTP responses, which can include various types of data, such as files or raw data.

Flask's send_file: A utility function from Flask to send files from the server to the client. It can be used for downloading files like CSVs or meal plans.

HTML5: The application includes HTML forms and fields for user interaction, including form elements such as StringField, PasswordField, SelectField, etc.

CSS (for styling): Although not explicitly shown in the code, CSS would typically be used for styling the HTML components (forms, buttons, etc.) of the application.

Setup Instructions: 

Making sure that Python is installed on your system. If not you can download it from the official site: 

https://www.python.org/downloads/.

To check if Python is installed, run:

python --version

Cloning the Project from the GitHub:

Open your Command Prompt and run the following command to clone the repository:

git clone https://github.com/DivyaSiddam/MealPlanner

Then navigate to the project directory:

cd MealPlanner

Then navigate to src

cd MealPlanner/src

Now install all Required Packages:

pip install -r requirements.txt.txt

Running the Application:

python app.py

This will launch the application at:http://127.0.0.1:5000

Now open your browser and go to http://127.0.0.1:5000 to start using the Home-Workout-Tracker, Now you u can use all these features like User Authentication and Management,Meal Plan Management,Recipe Management,Meal Tips,Search Functionality,Weekly Summary,Surprise Me! Feature,User Interface,Data Export etc and  more... 

YouTube Video Link:








