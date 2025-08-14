<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cybersecurity Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #062b24;
            color: white;
        }

        /* Navbar */
        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: white;
            padding: 15px 40px;
            color: black;
        }
        nav .logo {
            font-weight: bold;
            font-size: 1.2em;
        }
        nav ul {
            display: flex;
            list-style: none;
            margin: 0;
            padding: 0;
        }
        nav ul li {
            margin-left: 20px;
        }
        nav ul li a {
            text-decoration: none;
            color: black;
            font-weight: bold;
        }

        /* Profile Section */
        .profile-section {
            display: flex;
            flex-wrap: wrap;
            padding: 50px;
            align-items: center;
            background-color: #064d3b;
        }
        .profile-left {
            flex: 1;
            text-align: center;
        }
        .profile-left img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 3px solid white;
        }
        .profile-left h2 {
            margin-top: 15px;
        }
        .social-icons {
            margin-top: 15px;
        }
        .social-icons a {
            color: white;
            margin: 0 10px;
            font-size: 1.4em;
            text-decoration: none;
        }

        /* About Section */
        .profile-right {
            flex: 2;
            padding: 20px;
        }
        .about-me {
            margin-bottom: 20px;
        }
        .download-btn {
            background-color: #222;
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }
        .columns {
            display: flex;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .column {
            flex: 1;
            min-width: 200px;
            padding: 10px;
        }
        .column h3 {
            margin-bottom: 10px;
        }
        ul {
            padding-left: 20px;
        }
    </style>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

    <!-- Navbar -->
    <nav>
        <div class="logo">Your Name</div>
        <ul>
            <li><a href="#">Bio</a></li>
            <li><a href="#">Papers</a></li>
            <li><a href="#">Talks</a></li>
            <li><a href="#">News</a></li>
            <li><a href="#">Experience</a></li>
            <li><a href="#">Projects</a></li>
            <li><a href="#">Teaching</a></li>
        </ul>
    </nav>

    <!-- Profile Section -->
    <div class="profile-section">
        <div class="profile-left">
            <img src="https://i.ibb.co/mzjJ7JY/ethical-hacker.jpg" alt="Profile Image">
            <h2>Shashwat Singh</h2>
            <p>Cybersecurity Student | Penetration Tester</p>
            <div class="social-icons">
                <a href="#"><i class="fab fa-x-twitter"></i></a>
                <a href="#"><i class="fab fa-instagram"></i></a>
                <a href="#"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
            </div>
        </div>

        <div class="profile-right">
            <div class="about-me">
                <h2>About Me</h2>
                <p>
                    I am a passionate cybersecurity student and penetration tester with strong skills 
                    in ethical hacking, vulnerability analysis, and security research. 
                    My focus is on securing systems, finding vulnerabilities, and building tools for 
                    the infosec community.
                </p>
                <a class="download-btn" href="SHASHWAT_SINGH_CV (1).pdf">📄 Download CV</a>
            </div>

            <div class="columns">
                <div class="column">
                    <h3>Interests</h3>
                    <ul>
                        <li>Penetration Testing</li>
                        <li>Vulnerability Research</li>
                        <li>Cybersecurity Tools Development</li>
                    </ul>
                </div>
                <div class="column">
                    <h3>Education</h3>
                    <ul>
                        <li>BSc in Cybersecurity - Example University</li>
                        <li>Cert. in Ethical Hacking - Example Institute</li>
                        <li>OSCP Certified</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
