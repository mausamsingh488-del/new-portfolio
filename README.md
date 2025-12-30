 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Mausam | B.Tech CSE Student</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Google Font -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: #0f2027;
            background: linear-gradient(to right, #2c5364, #203a43, #0f2027);
            color: #fff;
        }

        header {
            padding: 40px 10%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 28px;
            color: #00ffd5;
        }

        nav a {
            margin-left: 20px;
            text-decoration: none;
            color: #fff;
            font-weight: 500;
            transition: 0.3s;
        }

        nav a:hover {
            color: #00ffd5;
        }

        .hero {
            padding: 80px 10%;
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
        }

        .hero-text {
            max-width: 600px;
        }

        .hero-text h2 {
            font-size: 42px;
            margin-bottom: 15px;
        }

        .hero-text span {
            color: #00ffd5;
        }

        .hero-text p {
            font-size: 16px;
            line-height: 1.7;
            margin-bottom: 25px;
        }

        .btn {
            padding: 12px 28px;
            background: #00ffd5;
            color: #000;
            text-decoration: none;
            font-weight: 600;
            border-radius: 30px;
            transition: 0.3s;
        }

        .btn:hover {
            background: #00c9aa;
        }

        section {
            padding: 70px 10%;
        }

        .section-title {
            text-align: center;
            font-size: 32px;
            margin-bottom: 50px;
            color: #00ffd5;
        }

        .skills, .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .card {
            background: rgba(255, 255, 255, 0.08);
            padding: 25px;
            border-radius: 15px;
            transition: 0.3s;
        }

        .card:hover {
            transform: translateY(-8px);
            background: rgba(0, 255, 213, 0.15);
        }

        .card h3 {
            margin-bottom: 10px;
            color: #00ffd5;
        }

        .card p {
            font-size: 14px;
            line-height: 1.6;
        }

        .contact {
            text-align: center;
        }

        .contact p {
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0, 0, 0, 0.3);
            font-size: 14px;
        }

        @media(max-width: 768px) {
            .hero-text h2 {
                font-size: 32px;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Mausam</h1>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <div class="hero-text">
        <h2>Hi, I'm <span>Mausam</span></h2>
        <p>
            I am a 5th Semester B.Tech Computer Science student passionate about
            Web Development and React Native. I am actively looking for an
            internship where I can learn, grow, and contribute to real-world projects.
        </p>
        <a href="#contact" class="btn">Hire Me for Internship</a>
    </div>
</section>

<section id="about">
    <h2 class="section-title">About Me</h2>
    <p style="text-align:center; max-width:800px; margin:auto; line-height:1.8;">
        I am a motivated Computer Science student with hands-on experience in
        HTML, CSS, JavaScript, React Native, and basic backend concepts.
        I love building user-friendly applications and continuously improving my skills.
    </p>
</section>

<section id="skills">
    <h2 class="section-title">My Skills</h2>
    <div class="skills">
        <div class="card">
            <h3>Frontend</h3>
            <p>HTML, CSS, JavaScript, Responsive Design</p>
        </div>
        <div class="card">
            <h3>React Native</h3>
            <p>Mobile App UI, Components, Navigation</p>
        </div>
        <div class="card">
            <h3>Tools</h3>
            <p>VS Code, GitHub, Live Server</p>
        </div>
        <div class="card">
            <h3>Other</h3>
            <p>Basic Power BI, MS Office, Problem Solving</p>
        </div>
    </div>
</section>

<section id="projects">
    <h2 class="section-title">Projects</h2>
    <div class="projects">
        <div class="card">
            <h3>Event Aggregator App</h3>
            <p>
                A platform for students and teachers to view and manage college events.
                Designed with a clean UI and easy navigation.
            </p>
        </div>
        <div class="card">
            <h3>Mental Health Journey App</h3>
            <p>
                A wellness-focused app to track mood and mental health progress
                using simple and user-friendly design.
            </p>
        </div>
        <div class="card">
            <h3>Carbon Footprint Tracker</h3>
            <p>
                Helps users calculate and reduce their carbon footprint
                through daily activity tracking.
            </p>
        </div>
    </div>
</section>

<section id="contact" class="contact">
    <h2 class="section-title">Contact Me</h2>
    <p>Email: mausamsingh488@gmail.com</p>
    <p>Phone: 7079860581</p>
    <p>LinkedIn & GitHub available on request</p>
</section>

<footer>
    © 2025 Mausam | B.Tech CSE Student | Internship Portfolio
</footer>

<script>
    // Simple animation on load
    document.body.style.opacity = "0";
    window.onload = () => {
        document.body.style.transition = "1s";
        document.body.style.opacity = "1";
    };
</script>

</body>
</html>