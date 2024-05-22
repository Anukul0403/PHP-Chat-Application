<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ChatApp - A PHP-Based Chat Application</title>
</head>
<body>
    <h1>ChatApp - A PHP-Based Chat Application</h1>

    <h2>Table of Contents</h2>
    <ul>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#configuration">Configuration</a></li>
        <li><a href="#usage">Usage</a></li>
        <li><a href="#technologies-used">Technologies Used</a></li>
        <li><a href="#contributing">Contributing</a></li>
        <li><a href="#license">License</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>

    <h2 id="introduction">Introduction</h2>
    <p><strong>ChatApp</strong> is a real-time chat application built using PHP. It allows users to create accounts, log in, and participate in chat rooms. The application supports one-on-one messaging and group chats, providing an interactive and engaging communication platform.</p>

    <h2 id="features">Features</h2>
    <ul>
        <li><strong>User Authentication:</strong> Secure user registration and login system.</li>
        <li><strong>Real-Time Messaging:</strong> Instant messaging with live updates.</li>
        <li><strong>Chat Rooms:</strong> Create and join multiple chat rooms.</li>
        <li><strong>Private Messaging:</strong> Send direct messages to other users.</li>
        <li><strong>User Profiles:</strong> View and update user profiles.</li>
        <li><strong>Notifications:</strong> Get notified of new messages.</li>
        <li><strong>Responsive Design:</strong> Fully responsive design for seamless use on mobile and desktop devices.</li>
    </ul>

    <h2 id="installation">Installation</h2>
    <p>To get started with ChatApp, follow these steps:</p>
    <ol>
        <li><strong>Clone the Repository:</strong>
            <pre><code>git clone https://github.com/yourusername/ChatApp.git
cd ChatApp</code></pre>
        </li>
        <li><strong>Install Dependencies:</strong>
            <p>Make sure you have Composer installed. Run the following command to install PHP dependencies:</p>
            <pre><code>composer install</code></pre>
        </li>
        <li><strong>Set Up the Database:</strong>
            <ul>
                <li>Create a new MySQL database.</li>
                <li>Import the database schema from <code>database/schema.sql</code>.</li>
            </ul>
        </li>
        <li><strong>Configure Environment Variables:</strong>
            <ul>
                <li>Rename <code>.env.example</code> to <code>.env</code>.</li>
                <li>Update the <code>.env</code> file with your database credentials and other necessary configuration settings.</li>
            </ul>
        </li>
        <li><strong>Start the Application:</strong>
            <pre><code>php -S localhost:8000</code></pre>
            <p>Open your browser and navigate to <a href="http://localhost:8000">http://localhost:8000</a> to see the application in action.</p>
        </li>
    </ol>

    <h2 id="configuration">Configuration</h2>
    <p>Before running the application, ensure you configure the following settings in the <code>.env</code> file:</p>
    <pre><code>DB_HOST=your_database_host
DB_NAME=your_database_name
DB_USER=your_database_user
DB_PASS=your_database_password

APP_URL=http://localhost:8000</code></pre>

    <h2 id="usage">Usage</h2>
    <p>Once the application is up and running, you can perform the following actions:</p>
    <ul>
        <li><strong>Register:</strong> Create a new account.</li>
        <li><strong>Log In:</strong> Log in with your credentials.</li>
        <li><strong>Join/Create Chat Rooms:</strong> Join existing chat rooms or create new ones.</li>
        <li><strong>Send Messages:</strong> Participate in chat rooms and send private messages.</li>
        <li><strong>Edit Profile:</strong> Update your profile information.</li>
    </ul>

    <h2 id="technologies-used">Technologies Used</h2>
    <ul>
        <li><strong>PHP:</strong> Backend logic and server-side scripting.</li>
        <li><strong>MySQL:</strong> Database management.</li>
        <li><strong>JavaScript (AJAX):</strong> Asynchronous requests and real-time updates.</li>
        <li><strong>HTML/CSS:</strong> Frontend structure and design.</li>
        <li><strong>Composer:</strong> Dependency management.</li>
    </ul>

    <h2 id="contributing">Contributing</h2>
    <p>We welcome contributions to enhance ChatApp. To contribute:</p>
    <ol>
        <li>Fork the repository.</li>
        <li>Create a new branch.</li>
        <li>Make your changes.</li>
        <li>Submit a pull request.</li>
    </ol>
    <p>Please ensure your code adheres to the project's coding standards and include appropriate tests.</p>

    <h2 id="license">License</h2>
    <p>This project is licensed under the MIT License. See the <a href="LICENSE">LICENSE</a> file for details.</p>

    <h2 id="contact">Contact</h2>
    <p>For any questions, suggestions, or feedback, please contact us at <a href="mailto:anukulgupta17@gmail.com">anukulgupta17@gmail.com</a>.</p>

    
</body>
</html>
