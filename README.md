<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Jainam Shah's Portfolio - Data Analytics, Power BI, Cloud Architecture, Big Data, AWS, Adobe Analytics, Google Analytics, Marketing Strategy Implementation">
    <meta name="keywords" content="Data Analytics, Power BI, Cloud Architecture, Big Data, AWS, Adobe Analytics, Google Analytics">
    <meta name="author" content="Jainam Shah">
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="images/favicon.ico" type="image/x-icon">
    <!-- Google tag (gtag.js) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-2DJ0XY2Q5L"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());

        gtag('config', 'G-2DJ0XY2Q5L');
    </script>
    
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
        <div class="outer-perimeter"></div>
        <div class="profile-icon">
            <img src="images/pic.jpg" class="profile-pic" alt="Profile picture of Jainam Shah">
        </div>
        <div class="hero-content">
            <div class="hero-text">
                <h1>Jainam Shah</h1>
                <p>Web Analytics & Data Visualization Specialist</p>
                <p>Proficient in Marketing Strategy Implementation & Big Data Tools</p>
            </div>
        </div>
    </section>


    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <div class="card-container">
            <div class="card" onclick="toggleCard(this)">
                <div class="front">
                    <h3>Professional Background <span class="hint">(Click to see more)</span></h3>
                    <p>Data Analyst with expertise in web analytics and data visualization.</p>
                </div>
                <div class="back">
                    <p>With a strong foundation in web analytics, data visualization, and cloud architecture, I am a certified Data Analyst dedicated to transforming raw data into meaningful insights. Over the past two years, I have honed my skills in tools like Google Analytics, Adobe Analytics, and Adobe Target to enhance user experiences and drive informed decision-making.</p>
                </div>
            </div>
            <div class="card" onclick="toggleCard(this)">
                <div class="front">
                    <h3>Educational Background <span class="hint">(Click to see more)</span></h3>
                    <p>Postgraduate courses in Big Data Analytics and Cloud Architecture.</p>
                </div>
                <div class="back">
                    <p>I pursued professional growth by completing postgraduate courses in Big Data Analytics and Cloud Architecture and Administration. This journey equipped me with expertise in tools such as Hadoop, Spark, Terraform, and Ansible, along with knowledge of AWS and Microsoft Azure.</p>
                </div>
            </div>
            <div class="card" onclick="toggleCard(this)">
                <div class="front">
                    <h3>Skills & Expertise <span class="hint">(Click to see more)</span></h3>
                    <p>Combining data, technology, and strategy to deliver results.</p>
                </div>
                <div class="back">
                    <p>I thrive at the intersection of data, technology, and strategy, combining analytical expertise with a problem-solving mindset to deliver impactful results. Whether through data-driven marketing campaigns or deploying robust cloud architectures, my focus is on excellence and innovation.</p>
                </div>
            </div>
        </div>
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
                        <div class="iframe-container">
                            <iframe src="images/ISO.pdf#toolbar=0"></iframe>
                        </div>
                    </div>
                </li>
                <li class="project-item" onclick="toggleDetails(this)">
                    <h3>Data Analysis - Adidas Dataset</h3>
                    <p>Performed detailed data analysis on the Adidas dataset to derive actionable insights.</p>
                    <span class="toggle-icon">+</span>
                    <div class="project-details">
                        <div class="iframe-container">
                            <iframe src="images/dataAnalysis1.pdf#toolbar=0"></iframe>
                        </div>
                    </div>
                </li>
                <li class="project-item" onclick="toggleDetails(this)">
                    <h3>Data Analysis - Auto Insurance Dataset</h3>
                    <p>Comprehensive data analysis of the Auto Insurance dataset using advanced techniques.</p>
                    <span class="toggle-icon">+</span>
                    <div class="project-details">
                        <div class="iframe-container">
                            <iframe src="images/dataAnalysis2.pdf#toolbar=0"></iframe>
                        </div>
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
                        <div class="iframe-container">
                            <iframe src="images/Dataset Exploration.pdf#toolbar=0"></iframe>
                        </div>
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

        <!-- LinkedIn Link -->
        <a href="https://www.linkedin.com/in/jainam2411/" class="linkedin-link" target="_blank">Connect on LinkedIn</a>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2025 Jainam Shah. All rights reserved.</p>
    </footer>

    <script>
        function toggleCard(card) {
            card.classList.toggle('flipped');
        }
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
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>

</body>
</html>
