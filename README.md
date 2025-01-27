<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Jainam Shah's Portfolio - Data Analytics, Power BI, Cloud Architecture">
    <meta name="keywords" content="Data Analytics, Power BI, Cloud Architecture, Big Data, AWS, Adobe Analytics, Google Analytics">
    <meta name="author" content="Jainam Shah">
    <link rel="stylesheet" href="style.css">
    <title>Jainam Shah's Portfolio</title>
</head>
<body>

    <!-- Animated Background for Analytics Visualization -->
    <div class="analytics-background"></div>

    <!-- Navigation Links -->
    <nav>
        <div class="logo">Jainam Shah</div>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#connect">Let's Connect</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-content">
            <h1>Jainam Shah</h1>
            <p>Web Analytics & Data Visualization Specialist</p>
            <p>Proficient in Marketing Strategy Implementation & Big Data Tools</p>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm a passionate data analyst and cloud enthusiast with experience in technologies like Power BI, Tableau, Python, SQL, and cloud infrastructure. I focus on delivering actionable insights and driving business decisions. I believe in the power of data to transform businesses and am always eager to explore new ways of leveraging it.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>

        <!-- Data Visualization -->
        <div class="project-category" id="data-visualization">
            <h3>Data Visualization</h3>
            <ul class="project-list">
                <li class="project-item" onclick="toggleDetails(this)">
                    <h3>Social Media KPI Dashboard</h3>
                    <p>Designed a KPI-focused dashboard using Power BI and DAX to analyze social media performance.</p>
                    <span class="toggle-icon">+</span>
                    <div class="project-details">
                        <iframe src="images/ISO.pdf#toolbar=0"></iframe>
                    </div>
                </li>
                <li class="project-item" onclick="toggleDetails(this)">
                    <h3>Data Analysis - Adidas Dataset</h3>
                    <p>Performed detailed data analysis on the Adidas dataset to derive actionable insights.</p>
                    <span class="toggle-icon">+</span>
                    <div class="project-details">
                        <iframe src="images/dataAnalysis1.pdf#toolbar=0"></iframe>
                    </div>
                </li>
                <li class="project-item" onclick="toggleDetails(this)">
                    <h3>Data Analysis - Auto Insurance Dataset</h3>
                    <p>Comprehensive data analysis of the Auto Insurance dataset using advanced techniques.</p>
                    <span class="toggle-icon">+</span>
                    <div class="project-details">
                        <iframe src="images/dataAnalysis2.pdf#toolbar=0"></iframe>
                    </div>
                </li>
            </ul>
        </div>

        <!-- Data Analysis -->
        <div class="project-category" id="data-analysis">
            <h3>Data Analysis</h3>
            <ul class="project-list">
                <li class="project-item" onclick="toggleDetails(this)">
                    <h3>Excel Statistical Analysis</h3>
                    <p>Statistical Analysis performed on a dataset to understand patterns and gather insights using MS Excel.</p>
                    <span class="toggle-icon">+</span>
                    <div class="project-details">
                        <iframe src="images/Dataset Exploration.pdf"></iframe>
                    </div>
                </li>
            </ul>
        </div>

        <!-- Cloud Technology -->
        <div class="project-category" id="cloud-technology">
            <h3>Cloud Technology</h3>
            <ul class="project-list">
                <li class="project-item" onclick="toggleDetails(this)">
                    <h3>ETL using Microservice</h3>
                    <p>Developed an ETL process using a microservice architecture. View the project on GitHub.</p>
                    <a href="https://github.com/jainamShah1998/nodejsProjectCLO835" target="_blank">ETL using Microservice - github</a>
                </li>
            </ul>
        </div>

    </section>

    <!-- Let's Connect Section -->
    <section id="connect">
        <h2>Let's Connect</h2>
        <p>Feel free to connect with me through LinkedIn or view my profile below.</p>

        <!-- Profile Icon -->
        <div class="profile-icon">
            <img src="images/pic.jpg" class="profile-pic" alt="Jainam Shah">
        </div>

        <!-- LinkedIn Link -->
        <a href="https://www.linkedin.com/in/jainam2411/" class="linkedin-link" target="_blank">Connect on LinkedIn</a>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Jainam Shah. All rights reserved.</p>
    </footer>

    <script>
        function toggleDetails(item) {
            const details = item.querySelector('.project-details');
            const icon = item.querySelector('.toggle-icon');
            if (details.style.display === 'block') {
                details.style.display = 'none';
                icon.textContent = '+';
            } else {
                details.style.display = 'block';
                icon.textContent = '-';
            }
        }
    </script>

</body>
</html>
