<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile - Oyembo</title>
    <style>
        /* Basic Styling */
        body { font-family: sans-serif; margin: 20px; color: #333; }
        p { line-height: 1.6; }
        h1, h2, h3 { color: #0077B5; }
        ul { list-style-type: disc; margin-left: 20px; }
        li { margin-bottom: 8px; }
        a { color: #0077B5; text-decoration: none; }
        a:hover { text-decoration: underline; }
        .badge-link { margin-right: 5px; }

        /* Profile Picture Animation */
        p align="center" img {
            transition: transform 0.3s ease-in-out;
        }
        p align="center" img:hover {
            transform: scale(1.05);
        }

        /* Section Title Animation */
        h2 {
            position: relative;
            padding-bottom: 5px;
        }
        h2::before {
            content: '';
            position: absolute;
            bottom: 0;
            left: 0;
            width: 40px;
            height: 2px;
            background-color: #0077B5;
            transition: width 0.3s ease-in-out;
        }
        h2:hover::before {
            width: 100%;
        }

        /* Project List Animation */
        .projects-list li {
            opacity: 0;
            transform: translateY(10px);
            animation: fadeInUp 0.5s ease-out forwards;
            margin-bottom: 15px;
        }
        .projects-list li:nth-child(2) { animation-delay: 0.2s; }
        .projects-list li:nth-child(3) { animation-delay: 0.4s; }

        @keyframes fadeInUp {
            to { opacity: 1; transform: translateY(0); }
        }
    </style>
</head>
<body>

    <p align="center">
        <img src="YOUR_PROFILE_PICTURE_URL" alt="Your Profile Picture" width="150" height="150" style="border-radius: 50%;">
    </p>

    <h1 align="center">Oyembo</h1>
    <h3 align="center">Aspiring Back End Developer | Passionate about Earth Observation & Conservation</h3>

    <p align="center">
        <a href="YOUR_LINKEDIN_PROFILE_URL" target="_blank" class="badge-link"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
        <a href="YOUR_TWITTER_PROFILE_URL" target="_blank" class="badge-link"><img src="https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"></a>
    </p>

    <h2>About Me 🌱</h2>
    <p>
        Driven by a deep passion for <b>Earth observation</b>, <b>environmental conservation</b>, <b>natural resource management</b>, and <b>wildlife conservation</b>, and with a background in <strong>Geographic Information Systems (GIS)</strong>, <strong>Environmental Impact Assessment</strong>, <strong>urban and rural land management</strong>, and <strong>Research</strong>, my journey into technology began with the <strong>ALX Professional Foundations</strong> program, where I cultivated essential tech professional skills, including <strong>effective communication</strong>, <strong>collaborative teamwork</strong>, and <strong>structured problem-solving</strong>. Building upon this robust groundwork, I am now an enthusiastic learner in the <strong>ALX Back End Web Development</strong> program.
    </p>
    <p>
        This intensive training is equipping me with the fundamental skills in [mention a few key back-end technologies] necessary to build impactful solutions for our planet. I am particularly interested in leveraging my interdisciplinary skills to create powerful tools for <b>spatial analysis</b> and understanding complex patterns in <b>wildlife movement</b>. The potential of technology to contribute to a healthier and more sustainable world is what truly inspires me.
    </p>

    <h2>Skills 💻</h2>
    <p>
        <strong>Tech Professional Skills:</strong> Effective Communication, Collaborative Teamwork, Structured Problem-Solving, [add other relevant skills from the Foundations program]
    </p>
    <p>
        <strong>Back End Development:</strong> HTML, CSS, JavaScript, Python, [mention other relevant back-end technologies you're learning]
    </p>
    <p>
        <strong>Technical Skills:</strong> Geographic Information Systems (GIS), Environmental Impact Assessment, Urban and Rural Land Management, Research, AutoCAD
    </p>
    <p>
        <strong>Tools & Technologies:</strong> Git, GitHub, [mention other tools like specific databases, frameworks, etc.]
    </p>
    <p>
        <strong>Other Interests:</strong> Earth Observation, Remote Sensing, GIS, Environmental Data Analysis
    </p>

    <h2>Projects 🛠️</h2>
    <ul class="projects-list">
        <li>
            <strong>[Project Title 1]:</strong> [**The Why:** Briefly state the motivation/problem.] [**The What:** Describe the functionality and what it does.]
            <ul>
                <li>Tech Stack: [List the technologies used]</li>
                <li>[Link to the repository if available]</li>
                <li>[**The So What:** Mention the potential impact or what you learned.]</li>
            </ul>
        </li>
        <li>
            <strong>[Project Title 2 (Geocoding Focused)]:** [**The Why:** Explain why you're focusing on geocoding in this project - e.g., To accurately map wildlife sightings for conservation efforts.] [**The What:** Describe how the project utilizes geocoding - e.g., It takes raw location data and converts it into usable geographic coordinates for analysis.]
            <ul>
                <li>Tech Stack: [List the technologies used, explicitly mentioning any geocoding libraries or APIs you're using or plan to use]</li>
                <li>[Link to the repository if available]</li>
                <li>[**The So What:** Highlight the significance of the geocoding aspect for your broader goals - e.g., This project is a foundational step towards my goal of developing tools for wildlife movement analysis.]</li>
            </ul>
        </li>
        <li>
            <strong>[Future Project Idea: Earth Observation Tool]:</strong> A future project focused on developing an earth observation tool for [mention specific spatial analysis or wildlife movement aspect - e.g., real-time tracking of endangered species using satellite data and geofencing]. [**The Why:** Briefly state the potential impact of this tool.] [**Potential Tech Stack:** List potential technologies you might explore.]
        </li>
    </ul>

    <h2>ALX Learning Journey 🚀</h2>
    <p>
        My journey into the world of technology commenced with the <strong>ALX Professional Foundations</strong> program, where I cultivated essential tech professional skills, including <strong>effective communication</strong>, <strong>collaborative teamwork</strong>, and <strong>structured problem-solving</strong>. Building upon this robust groundwork, I am now deeply engaged in the <strong>ALX Back End Web Development</strong> program. This intensive training is providing me with a strong and practical understanding of:
    </p>
    <ul>
        <li><strong>Core Programming:</strong> Python, JavaScript</li>
        <li><strong>Web Development Fundamentals:</strong> HTML, CSS</li>
        <li><strong>[Mention other relevant modules or skills you're learning - e.g., Databases (e.g., SQL), Frameworks (e.g., Flask, Django), Version Control (Git)]</strong></li>
    </ul>
    <p>
        The comprehensive skills acquired through both the Professional Foundations and the Back End Development programs, combined with my expertise in Geographic Information Systems, Environmental Impact Assessment, urban and rural land management, Research, and AutoCAD, are instrumental in my pursuit of developing innovative tools for Earth observation, spatial analysis, and wildlife movement. I am eager to leverage this integrated learning to contribute meaningful and impactful solutions to the fields I am passionate about.
    </p>

    <h2>Connect with Me 🤝</h2>
    <p>
        I'm always open to connecting with fellow developers, conservationists, and anyone passionate about leveraging technology for a better future. Feel free to reach out!
    </p>
    <p align="center">
        <a href="YOUR_GITHUB_PROFILE_URL" target="_blank" class="badge-link"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
        <a href="YOUR_EMAIL_ADDRESS" target="_blank" class="badge-link"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
    </p>

</body>
</html>
