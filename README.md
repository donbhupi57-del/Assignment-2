# Assignment-2
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f4f7f6;
            color: #333333;
            line-height: 1.6;
        }

        #main-header {
            background-color: #1e3a8a;
            color: #ffffff;
            text-align: center;
            padding: 20px 0 0 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        #main-header h1 {
            margin-bottom: 15px;
            font-size: 2rem;
        }

        .navbar {
            background-color: #172554;
            padding: 10px 0;
        }

        .navbar ul {
            list-style: none;
        }

        .navbar ul li {
            display: inline-block;
            margin: 0 15px;
        }

        .navbar a {
            color: #ffffff;
            text-decoration: none;
            padding: 8px 16px;
            border-radius: 5px;
            font-weight: 500;
            transition: background-color 0.3s ease;
        }

        .navbar a:hover {
            background-color: #3b82f6;
        }

        main {
            max-width: 850px;
            margin: 30px auto;
            padding: 0 20px;
        }

        .card-section {
            background-color: #ffffff;
            padding: 30px;
            margin-bottom: 25px;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            text-align: center;
        }

        .card-section h2 {
            color: #1e3a8a;
            margin-bottom: 20px;
            font-size: 1.6rem;
        }

        .section-divider {
            border: 0;
            height: 2px;
            background: #cbd5e1;
            margin: 30px auto;
            width: 60%;
        }

        .profile-img {
            width: 140px;
            height: 140px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 15px;
            border: 3px solid #1e3a8a;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.15);
        }

        .skills-table {
            width: 70%;
            margin: 0 auto;
            border-collapse: collapse;
            text-align: left;
        }

        .skills-table th,
        .skills-table td {
            border: 1px solid #cbd5e1;
            padding: 12px 15px;
        }

        .skills-table th {
            background-color: #1e3a8a;
            color: #ffffff;
            font-weight: 600;
        }

        .skills-table tr:nth-child(even) {
            background-color: #f1f5f9;
        }

        .project-box {
            background-color: #f8fafc;
            border: 1px solid #e2e8f0;
            border-left: 4px solid #1e3a8a;
            padding: 15px 20px;
            margin: 15px auto;
            border-radius: 5px;
            text-align: left;
        }

        .project-box h3 {
            color: #1e3a8a;
            margin-bottom: 5px;
        }

        .contact-form {
            width: 80%;
            margin: 0 auto;
            text-align: left;
        }

        .form-group {
            margin-bottom: 15px;
        }

        .form-group label {
            display: block;
            font-weight: 600;
            margin-bottom: 5px;
            color: #333333;
        }

        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #cbd5e1;
            border-radius: 5px;
            font-family: 'Poppins', sans-serif;
        }

        .form-group input:focus,
        .form-group textarea:focus {
            outline: none;
            border-color: #1e3a8a;
        }

        .btn {
            background-color: #1e3a8a;
            color: #ffffff;
            padding: 10px 24px;
            border: none;
            border-radius: 5px;
            font-size: 1rem;
            font-family: 'Poppins', sans-serif;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #3b82f6;
        }

        .back-to-top {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #1e3a8a;
            color: #ffffff;
            padding: 10px 15px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 0.9rem;
            box-shadow: 0 3px 8px rgba(0, 0, 0, 0.2);
            transition: background-color 0.3s ease;
        }

        .back-to-top:hover {
            background-color: #3b82f6;
        }

        footer {
            background-color: #172554;
            color: #ffffff;
            text-align: center;
            padding: 15px 0;
            margin-top: 40px;
            font-size: 0.9rem;
        }
    </style>
</head>
<body id="top">

    <header id="main-header">
        <h1>My Portfolio</h1>
        <nav class="navbar">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about" class="card-section">
            <h2>About Me</h2>
            <div class="about-content">
                <img src="//profile.jpg.jpg" alt="" class="profile-img">
                <p>Hello! My name is John Doe. I am learning web development and this is my first portfolio website[cite: 3].</p>
            </div>
        </section>

        <hr class="section-divider">

        <section id="skills" class="card-section">
            <h2>My Skills</h2>
            <table class="skills-table">
                <thead>
                    <tr>
                        <th>Skill</th>
                        <th>Level</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>HTML</td>
                        <td>Beginner</td>
                    </tr>
                    <tr>
                        <td>CSS</td>
                        <td>Beginner</td>
                    </tr>
                    <tr>
                        <td>JavaScript</td>
                        <td>Learning</td>
                    </tr>
                </tbody>
            </table>
        </section>

        <hr class="section-divider">

        <section id="projects" class="card-section">
            <h2>My Projects</h2>
            <div class="project-box">
                <h3>Project 1</h3>
                <p>A simple HTML &amp; CSS webpage.</p>
            </div>
            <div class="project-box">
                <h3>Project 2</h3>
                <p>Another awesome mini project.</p>
            </div>
        </section>

        <hr class="section-divider">

        <section id="contact" class="card-section">
            <h2>Contact Me</h2>
            <form action="#" method="post" class="contact-form">
                <div class="form-group">
                    <label for="name">Name:</label>
                    <input type="text" id="name" name="name" placeholder="Enter your name" required>
                </div>

                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" id="email" name="email" placeholder="Enter your email" required>
                </div>

                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea id="message" name="message" rows="4" placeholder="Write your message" required></textarea>
                </div>

                <button type="submit" class="btn">Send Message</button>
            </form>
        </section>
    </main>


    <footer>
        <p>&copy; 2026 John Doe. All rights reserved.</p>
    </footer>

</body>
</html>
