<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ruchira Lakshitha Bandaranayake - Portfolio</title>
    <style>
        /* Header animation */
        @keyframes typing {
            0% { width: 0; }
            100% { width: 100%; }
        }

        .typing-effect {
            display: inline-block;
            overflow: hidden;
            white-space: nowrap;
            border-right: 2px solid;
            animation: typing 3s steps(30) 1s forwards;
        }

        /* Animating moving images */
        @keyframes moveImage {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }

        .moving-image {
            animation: moveImage 10s infinite linear;
        }

        /* Styling for the header */
        header {
            text-align: center;
            padding: 50px;
            background: #f0f0f0;
        }

        h1 {
            font-size: 2.5em;
            color: #333;
        }

        .tech-image {
            width: 100px;
            height: auto;
            margin: 20px;
        }

        .project-link {
            color: #007bff;
            text-decoration: none;
        }

        .project-link:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <header>
        <h1 class="typing-effect">HI I'M Ruchira Lakshitha Bandaranayake</h1>
        <p>Forward-Thinking IT Student at SLIIT | Team Leader Equipped for Tomorrow’s Tech Challenges</p>

        <div class="moving-image">
            <img src="https://source.unsplash.com/1600x500/?technology,programming" alt="Tech Image" class="tech-image">
        </div>
    </header>

    <section id="about-me">
        <h2>🚀 About Me</h2>
        <p>🎓 **Undergraduate** | *Following a degree in Information Technology at SLIIT*  
        💡 **Passionate** about technology, software development, and innovation!  
        📌 I love building full-stack applications, mobile apps, and exploring new technologies.</p>
    </section>

    <section id="tech-stack">
        <h2>🛠️ Tech Stack</h2>
        <h3>💻 Programming Languages</h3>
        <div>
            <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C">
            <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++">
            <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="Java">
            <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
            <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML">
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS">
        </div>
        
        <h3>🗄️ Databases</h3>
        <div>
            <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="MongoDB">
            <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
        </div>
    </section>

    <section id="projects">
        <h2>📌 Projects</h2>

        <h3>🏋️ Android Workout App with To-Do List</h3>
        <p>📱 **App Features:**  
            - Diet plans & muscle workout plans  
            - Login system  
            - To-do list with notifications & vibrations  
            - Shared preferences for secure user data storage
        </p>
        <a href="https://github.com/ruchira403/Android-Application-workout-app-with-the-Todo-list-" class="project-link">GitHub Repo</a>

        <h3>🌍 Java Online Tour Guide System</h3>
        <p>🖥️ **Tech Stack:** HTML (Frontend) | Java (Backend) | MySQL (Database)  
            📌 **Key Features:**  
            - Dynamic website with seamless UX  
            - Integrated MySQL database for feedback & package management
        </p>
        <a href="https://github.com/ruchira403/Java-project-online-tour-guide-system-" class="project-link">GitHub Repo</a>

        <h3>📦 MERN Packaging System</h3>
        <p>🌍 **Skilled MERN stack developer** for full-stack solutions!  
            🚀 **Features:**  
            - Client tracking & automated email workflows  
            - Delivery tracking, inventory alerts, & machine maintenance modules  
            - Scalable, optimized package management system
        </p>
        <a href="https://github.com/ruchira403/Mern-Project-Packaging-System-" class="project-link">GitHub Repo</a>
    </section>

    <section id="contact">
        <h2>📞 Contact Me</h2>
        <p>📧 **Email:** Lruchira58@gmail.com  
        📱 **Phone:** 0762633451  
        🌐 **GitHub:** <a href="https://github.com/ruchira403">ruchira403</a></p>
    </section>

    <section id="fun-fact">
        <h2>🎭 Fun Fact</h2>
        <p>💡 *Code is like humor. When you have to explain it, it’s bad.* 😆</p>
    </section>

</body>
</html>
