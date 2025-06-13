<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anand Kumar Shukla - GitHub Profile</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117; /* GitHub dark background */
            color: #c9d1d9; /* GitHub text color */
            display: flex;
            justify-content: center;
            align-items: flex-start;
            min-height: 100vh;
            padding: 2rem 1rem; /* Add padding for mobile view */
        }
        .container {
            max-width: 900px;
            width: 100%;
            background-color: #161b22; /* GitHub card background */
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
            padding: 2.5rem;
            box-sizing: border-box; /* Include padding in element's total width and height */
        }
        h1, h3 {
            color: #58a6ff; /* A vibrant blue for headings */
            margin-bottom: 1rem;
        }
        h1 {
            font-size: 2.5rem; /* Larger for main heading */
            text-align: center;
            margin-bottom: 1.5rem;
        }
        h3 {
            font-size: 1.75rem;
            text-align: left;
            border-bottom: 2px solid #30363d; /* Subtle separator */
            padding-bottom: 0.5rem;
            margin-top: 2rem;
        }
        p {
            margin-bottom: 1rem;
            line-height: 1.6;
        }
        img {
            border-radius: 5px; /* Slightly rounded corners for images */
        }
        a {
            color: #58a6ff;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .icon-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 1.5rem; /* Spacing between icons */
            margin-bottom: 1.5rem;
        }
        .icon-grid img {
            width: 40px;
            height: 40px;
            transition: transform 0.2s; /* Smooth hover effect */
        }
        .icon-grid img:hover {
            transform: translateY(-5px);
        }
        .section-content ul {
            list-style: none; /* Remove default list bullets */
            padding-left: 0;
        }
        .section-content ul li {
            background-color: #0d1117; /* Darker background for list items */
            padding: 1rem 1.5rem;
            margin-bottom: 0.75rem;
            border-radius: 8px;
            border-left: 4px solid #58a6ff; /* Accent border */
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
            transition: background-color 0.2s;
        }
        .section-content ul li:hover {
            background-color: #12161c; /* Slightly lighter on hover */
        }
        .section-content ul li strong {
            color: #c9d1d9;
            font-size: 1.1rem;
        }
        .section-content ul li em {
            color: #8b949e;
            font-size: 0.9rem;
        }
        .section-content ul li p {
            margin-top: 0.5rem;
            margin-bottom: 0;
        }
        .section-content ul li ul { /* Nested lists for bullet points in projects/experience */
            margin-top: 0.5rem;
            padding-left: 1.5rem;
            list-style: disc; /* Use discs for nested lists */
        }
        .section-content ul li ul li {
            background-color: transparent; /* No separate background for nested list items */
            border-left: none; /* No border for nested list items */
            padding: 0;
            margin-bottom: 0.25rem;
        }
        .github-stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); /* Responsive grid for stats */
            gap: 1rem;
            justify-items: center;
            margin-top: 2rem;
            margin-bottom: 2rem;
        }
        .github-stats-grid img {
            max-width: 100%; /* Ensure images don't overflow */
            height: auto;
        }

        /* Responsive adjustments */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            h3 {
                font-size: 1.5rem;
            }
            .container {
                padding: 1.5rem;
            }
            .icon-grid {
                gap: 1rem;
                justify-content: center;
            }
            .github-stats-grid {
                grid-template-columns: 1fr; /* Stack stats on small screens */
            }
        }
    </style>
</head>
<body class="selection:bg-blue-600 selection:text-white">
    <div class="container">
        <!-- Profile Header -->
        <h1 class="font-bold">Hi there 👋, I'm Anand Kumar Shukla</h1>
        <h3 class="font-medium text-center">A passionate Frontend Developer from India</h3>

        <p class="text-left mb-4">
            <img src="https://komarev.com/ghpvc/?username=thecoatcard&label=Profile%20views&color=0e75b6&style=flat" alt="thecoatcard" class="inline-block align-middle rounded-md">
        </p>

        <p class="text-left mb-8">
            <a href="https://github.com/ryo-ma/github-profile-trophy" target="_blank" rel="noreferrer">
                <img src="https://github-profile-trophy.vercel.app/?username=thecoatcard" alt="thecoatcard" class="inline-block align-middle rounded-md">
            </a>
        </p>

        <hr class="border-t border-gray-700 my-8">

        <!-- About Me Section -->
        <h3>About Me</h3>
        <p class="text-gray-300">
            A dedicated and versatile developer with a strong foundation in both frontend and backend technologies, currently pursuing a Bachelor of Technology in Computer Science and Engineering. I thrive on building impactful applications and optimizing data processes. My experience spans full-stack development, data analysis, and creating user-friendly interfaces. I am always eager to learn new technologies and contribute to innovative projects.
        </p>

        <hr class="border-t border-gray-700 my-8">

        <!-- Skills Section -->
        <h3>Skills</h3>
        <h3 class="text-left text-base font-semibold text-gray-400 !mt-4 !mb-4 !border-none">Languages and Tools:</h3>
        <div class="icon-grid">
            <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" title="C"/> </a>
            <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" title="C++"/> </a>
            <a href="https://www.java.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="java" title="Java"/> </a>
            <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" title="Python"/> </a>
            <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" title="JavaScript"/> </a>
            <a href="https://www.r-project.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/r-project/r-project-icon.svg" alt="r" title="R"/> </a>
        </div>
        <div class="icon-grid">
            <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" title="ReactJS"/> </a>
            <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" title="ExpressJS"/> </a>
            <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" title="NodeJS"/> </a>
            <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="tailwind" title="Tailwind CSS"/> </a>
        </div>
        <div class="icon-grid">
            <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" title="MySQL"/> </a>
            <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" title="MongoDB"/> </a>
            <!-- Derby icon not commonly available in devicons, can use a generic database icon or skip if not crucial for visual consistency -->
        </div>
        <div class="icon-grid">
            <a href="https://hadoop.apache.org/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/apache_hadoop/apache_hadoop-icon.svg" alt="hadoop" title="Hadoop"/> </a>
            <a href="https://www.microsoft.com/en-us/microsoft-365/excel" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/3/34/Microsoft_Office_Excel_%282019%E2%80%93present%29.svg" alt="excel" title="Excel"/> </a>
            <a href="https://www.tableau.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tableau/tableau-icon.svg" alt="tableau" title="Tableau"/> </a>
            <a href="https://powerbi.microsoft.com/en-us/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/microsoft_powerbi/microsoft_powerbi-icon.svg" alt="powerbi" title="PowerBI"/> </a>
            <!-- Hive icon not commonly available -->
            <a href="https://code.visualstudio.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" alt="vscode" title="VS Code"/> </a>
            <a href="https://www.jetbrains.com/idea/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/intellij/intellij-original.svg" alt="intellij" title="IntelliJ IDEA"/> </a>
        </div>
        <div class="icon-grid">
            <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" title="Linux"/> </a>
            <a href="https://www.microsoft.com/en-us/windows/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/windows8/windows8-original.svg" alt="windows" title="Windows"/> </a>
            <a href="https://www.apple.com/macos/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apple/apple-original.svg" alt="mac" title="macOS"/> </a>
        </div>

        <hr class="border-t border-gray-700 my-8">

        <!-- Experience Section -->
        <h3 class="section-title">Experience</h3>
        <div class="section-content">
            <ul>
                <li>
                    <strong>Data Science Intern</strong> | BioLogic Products Pvt Ltd | Remote
                    <em>May 2024 - July 2024</em>
                    <ul>
                        <li>Spearheaded analysis of 10+ brand product lines to uncover shared ingredient patterns, driving strategic product alignment and data-backed decisions.</li>
                        <li>Developed backend feature enhancements by applying regression techniques, contributing to a 15% increase in analytical accuracy.</li>
                        <li>Led team collaboration through effective communication, ensuring 100% on-time delivery of project milestones over a 3-month internship period.</li>
                    </ul>
                </li>
            </ul>
        </div>

        <hr class="border-t border-gray-700 my-8">

        <!-- Projects Section -->
        <h3 class="section-title">Projects</h3>
        <div class="section-content">
            <ul>
                <li>
                    <strong>TO-DO APPLICATION</strong>
                    <em>Tech: ReactJS, NodeJS, ExpressJS, MongoDB, JWT, Nodemailer</em>
                    <ul>
                        <li>Built a full-stack To-Do Application with secure JWT-based user authentication and password encryption.</li>
                        <li>Integrated email functionality using Nodemailer to enable password reset via a secure link.</li>
                        <li>Enabled authenticated users to perform complete CRUD operations on tasks, enhancing personal productivity.</li>
                        <li>Planned and designed a leaderboard feature for future implementation to encourage timely task completion through gamification.</li>
                    </ul>
                </li>
                <li>
                    <strong>DEVELOPER PORTFOLIO WEBSITE</strong>
                    <em>Tech: ReactJS, HTML, Tailwind CSS, Js</em>
                    <ul>
                        <li>Designed and developed a fully responsive and visually appealing personal portfolio website using ReactJS.</li>
                        <li>Built a modern UI with smooth animations, interactive components, and elegant section transitions using Tailwind CSS.</li>
                        <li>Showcased projects, skills, and contact information in a clean, user-friendly layout optimized for all devices.</li>
                    </ul>
                </li>
                <li>
                    <strong>DATA MANIPULATION HELPER</strong>
                    <em>Tech: Java, DSA, Java Swing</em>
                    <ul>
                        <li>Engineered a desktop-based data handler with 10+ CRUD operations using Java Swing and OOP principles.</li>
                        <li>Optimized sorting algorithms using Merge Sort ($O(n~log~n))$ for 25% faster data processing.</li>
                        <li>Facilitated seamless UI interaction to enhance data management efficiency by 10%.</li>
                    </ul>
                </li>
            </ul>
        </div>

        <hr class="border-t border-gray-700 my-8">

        <!-- Education Section -->
        <h3 class="section-title">Education</h3>
        <div class="section-content">
            <ul>
                <li>
                    <strong>Bachelor of Technology - Computer Science and Engineering</strong> | Lovely Professional University, Punjab, India
                    <em>Since Sep 2022</em>
                    <ul>
                        <li>CGPA: 7.44</li>
                    </ul>
                </li>
                <li>
                    <strong>Intermediate</strong> | Sanskar Global School, Pratapgarh, Uttar Pradesh
                    <em>July 2019 - July 2021</em>
                    <ul>
                        <li>Percentage: 86.6%</li>
                    </ul>
                </li>
                <li>
                    <strong>Matriculation</strong> | Sanskar Global School, Pratapgarh, Uttar Pradesh
                    <em>June 2017 - July 2019</em>
                    <ul>
                        <li>Percentage: 75%</li>
                    </ul>
                </li>
            </ul>
        </div>

        <hr class="border-t border-gray-700 my-8">

        <!-- Certifications Section -->
        <h3 class="section-title">Certifications</h3>
        <div class="section-content">
            <ul>
                <li><strong>Data Analysis with Tableau</strong> (Coursera: Tableau Learning Partner) - Oct 2024 - Nov 2024</li>
                <li><strong>Excel Fundamentals for Data Analysis</strong> (Coursera: Macquarie University) - Jan 2024 - Apr 2024</li>
                <li><strong>SQL Essential Training</strong> (LinkedIn) - Jan 2023 - Feb 2023</li>
            </ul>
        </div>

        <hr class="border-t border-gray-700 my-8">

        <!-- Connect with me Section -->
        <h3>Connect with me:</h3>
        <div class="icon-grid">
            <a href="https://www.linkedin.com/in/anand-kumar-shukla/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linkedin/linkedin-original.svg" alt="linkedin" title="LinkedIn"/> </a>
            <a href="https://github.com/thecoatcard" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" alt="github" title="GitHub"/> </a>
            <a href="mailto:kumaranand43856@gmail.com" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/gmail/gmail-icon.svg" alt="email" title="Email"/> </a>
        </div>

        <hr class="border-t border-gray-700 my-8">

        <!-- GitHub Stats Section -->
        <h3>GitHub Stats</h3>
        <div class="github-stats-grid">
            <img src="https://github-readme-stats.vercel.app/api/top-langs?username=thecoatcard&show_icons=true&locale=en&layout=compact&theme=dark" alt="thecoatcard Top Languages" class="rounded-md">
            <img src="https://github-readme-stats.vercel.app/api?username=thecoatcard&show_icons=true&locale=en&theme=dark" alt="thecoatcard GitHub Stats" class="rounded-md">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=thecoatcard&theme=dark" alt="thecoatcard GitHub Streak" class="rounded-md">
        </div>
    </div>
</body>
</html>
