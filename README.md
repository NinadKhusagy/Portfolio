# Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adnan Khusagy's Resume</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
            animation: fadeIn 2s;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #50b3a2;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #e8491d 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        #showcase {
            min-height: 400px;
            background: #35424a url('https://via.placeholder.com/800x400') no-repeat center center/cover;
            color: #fff;
            text-align: center;
            padding-top: 100px;
            animation: slideIn 2s;
        }
        @keyframes slideIn {
            from { margin-top: -50px; opacity: 0; }
            to { margin-top: 0; opacity: 1; }
        }
        #showcase h1 {
            font-size: 55px;
            margin-top: 0;
        }
        .main {
            padding: 20px;
            background: #fff;
            margin-bottom: 20px;
        }
        .section-title {
            margin: 0;
            padding-bottom: 10px;
            border-bottom: 2px solid #e8491d;
        }
        footer {
            padding: 20px;
            margin-top: 20px;
            color: #fff;
            background-color: #e8491d;
            text-align: center;
        }
        .profile-photo {
            display: block;
            margin: 0 auto 20px;
            border-radius: 50%;
            width: 150px;
            height: 150px;
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Adnan Khusagy</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#about">About</a></li>
                    <li><a href="#education">Education</a></li>
                    <li><a href="#skills">Skills</a></li>
                    <li><a href="#achievements">Achievements</a></li>
                    <li><a href="#activities">Activities</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="showcase">
        <div class="container">
            <h1>Welcome to My Personal Page</h1>
            <p>A brief overview of my academic and professional background.</p>
        </div>
    </section>

    <div class="container main">
        <section id="about">
            <h2 class="section-title">About Me</h2>
            <img src="https://via.placeholder.com/150" alt="Profile Photo" class="profile-photo">
            <p>Hello, I’m Adnan Khusagy. I am a student from the CSE department, aiming to utilize my interpersonal skills to achieve the goals of a company that focuses on my future career. Additionally, I strive to become self-independent.</p>
        </section>

        <section id="education">
            <h2 class="section-title">Education</h2>
            <ul>
                <li><strong>Undergraduate (7th Semester)</strong>, North South University - CSE</li>
                <li><strong>HSC</strong>, Bhola Govt. College - Science (2016-2018)</li>
                <li><strong>SSC</strong>, Lalmohan Ha-mim Res. School and College - Science (2016)</li>
            </ul>
        </section>

        <section id="skills">
            <h2 class="section-title">Skills</h2>
            <ul>
                <li>Expert in MS Word, Google Docs, MS PowerPoint, MS Excel, Google Spreadsheet</li>
                <li>Time management</li>
                <li>Experienced in translating</li>
            </ul>
        </section>

        <section id="achievements">
            <h2 class="section-title">Academic Achievements</h2>
            <ul>
                <li>Achieved an award for managing a student program</li>
                <li>Received a certificate for 100% attendance and punctuality in HSC</li>
            </ul>
        </section>

        <section id="activities">
            <h2 class="section-title">Extra Curricular Activities</h2>
            <ul>
                <li>Certificate in Grammar, Writing, Speaking, and Phonetics</li>
                <li>Member of North South University Earth Club</li>
                <li>Volunteer at UNICEF</li>
                <li>Volunteer at National Cyber Nuts competition</li>
            </ul>
        </section>

        <section id="contact">
            <h2 class="section-title">Contact Information</h2>
            <p>House Number: 151 Road 5 Block C Bashundhara R/A</p>
            <p>Phone Number: 01830347454</p>
            <p>Email: <a href="mailto:adnankhusagy1@gmail.com">adnankhusagy1@gmail.com</a></p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Adnan Khusagy. All rights reserved.</p>
    </footer>
</body>
</html>
