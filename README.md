<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Skill-Sharing & Learning Platform - README</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Skill-Sharing & Learning Platform</h1>
        <p>This platform enables users to share and learn various skills like coding, cooking, photography, and DIY crafts.</p>
    </header>

    <section>
        <h2>Key Features</h2>
        <ul>
            <li>Skill Posts: Users can share their skills through photos or videos.</li>
            <li>Learning Progress Updates: Users can track and share their learning journey.</li>
            <li>Learning Plans: Users can create and share personalized learning plans.</li>
            <li>Interactivity: Users can like and comment on others' posts.</li>
            <li>User Profiles: Each user has a profile to showcase their skills and progress.</li>
        </ul>
    </section>

    <section>
        <h2>Tech Stack</h2>
        <ul>
            <li><strong>Backend:</strong> Spring Boot, Java, MySQL</li>
            <li><strong>Frontend:</strong> React, JavaScript, HTML, CSS</li>
            <li><strong>Version Control:</strong> Git, GitHub</li>
            <li><strong>IDE:</strong> VS Code, IntelliJ IDEA</li>
        </ul>
    </section>

    <section>
        <h2>Project Structure</h2>
        <pre>
📁 Skill-Sharing-Platform/
├── 📁 backend/             # Spring Boot Backend
│   ├── 📁 src/
│   └── 📄 pom.xml          # Maven Dependencies
├── 📁 frontend/            # React Frontend
│   ├── 📁 public/
│   ├── 📁 src/
│   └── 📄 package.json     # Frontend Dependencies
└── 📄 README.md            # Project Documentation
        </pre>
    </section>

    <section>
        <h2>Setup Instructions</h2>
        <h3>Prerequisites</h3>
        <ul>
            <li>Java 17+</li>
            <li>Node.js 18+</li>
            <li>MySQL Database</li>
            <li>Git Bash (or any terminal of your choice)</li>
        </ul>

        <h3>Backend Setup (Spring Boot)</h3>
        <ol>
            <li>Clone the repository:</li>
            <pre><code>git clone &lt;repository_url&gt;<br>cd backend</code></pre>
            <li>Configure the database connection in <code>application.properties</code>.</li>
            <li>Build and run the application:</li>
            <pre><code>mvn spring-boot:run</code></pre>
        </ol>

        <h3>Frontend Setup (React)</h3>
        <ol>
            <li>Navigate to the frontend directory:</li>
            <pre><code>cd ../frontend</code></pre>
            <li>Install dependencies:</li>
            <pre><code>npm install</code></pre>
            <li>Start the React application:</li>
            <pre><code>npm start</code></pre>
        </ol>
    </section>

    <section>
        <h2>Usage</h2>
        <ul>
            <li>Post a Skill: Share your skills through text, images, or videos.</li>
            <li>Update Learning Progress: Track and share your learning journey.</li>
            <li>Plan Your Learning: Create and share personalized learning plans.</li>
            <li>Engage with Others: Like and comment on posts.</li>
        </ul>
    </section>

    <section>
        <h2>Future Enhancements</h2>
        <ul>
            <li>Notifications for new comments or likes.</li>
            <li>Personalized skill recommendations.</li>
            <li>Progress analytics and insights.</li>
        </ul>
    </section>

    <section>
        <h2>Contributing</h2>
        <p>Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.</p>
    </section>

    <section>
        <h2>License</h2>
        <p>This project is licensed under the MIT License.</p>
    </section>

    <footer>
        <p>Happy Learning! 🚀</p>
    </footer>
</body>
</html>
