<!DOCTYPE html>
<html>
<head>
</head>
<body>
    <h1>CRM App</h1>
    <p>A CRM (Customer Relationship Management) application that allows user registration, login, and CRUD (Create, Read, Update, Delete) operations. The application is built with Python, Django, Flask and uses MySQL as the database.</p>
     

  <h2>Features</h2>
    <ul>
        <li>User Registration</li>
        <li>User Login</li>
        <li>Create, Read, Update, Delete (CRUD) operations for customer records</li>
        <li>MySQL database integration</li>
    </ul>

  <h2>Installation</h2>
    <ol>
        <li><b>Clone the repository:</b>
            <pre><code>git clone https://github.com/yourusername/crm-app.git
cd crm-app
            </code></pre>
        </li>
        <li><b>Create and activate a virtual environment (optional but recommended):</b>
            <pre><code>python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
            </code></pre>
        </li>
        <li><b>Install the dependencies:</b>
            <pre><code>pip install -r requirements.txt
            </code></pre>
        </li>
        <li><b>Configure the database:</b>
            <p>Create a MySQL database and update the database configuration in your project settings (e.g., <code>config.py</code>, <code>settings.py</code>).</p>
            <pre><code>DATABASE = {
    
dataBase = mysql.connector.connect(
	host = 'localhost',
	user = 'root',
	passwd = 'password123'
)}
            </code></pre>
        </li>
        <li><b>Run database migrations:</b>
            <pre><code># Example for Flask-Migrate or Django
flask db upgrade  # For Flask
python manage.py migrate  # For Django
            </code></pre>
        </li>
        <li><b>Run the application:</b>
            <pre><code>flask run  # For Flask
python manage.py runserver  # For Django
            </code></pre>
        </li>
    </ol>

  <h2>Usage</h2>
    <ol>
        <li><b>Register a new user:</b>
            <p>Navigate to the registration page and fill out the form to create a new account.</p>
        </li>
        <li><b>Login:</b>
            <p>After registering, log in with your new credentials.</p>
        </li>
        <li><b>Manage Customers:</b>
            <p>Once logged in, you can create, view, update, and delete customer records.</p>
        </li>
    </ol>
