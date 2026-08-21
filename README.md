<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Dr. Muhammad Asad Iqbal | Academic Profile</title>

<style>

/* =========================
   GLOBAL STYLES
========================= */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: "Segoe UI", Arial, sans-serif;
    background: #f7f9fc;
    color: #1e293b;
    line-height: 1.7;
}

a {
    text-decoration: none;
    color: inherit;
}

.container {
    width: 90%;
    max-width: 1200px;
    margin: auto;
}


/* =========================
   NAVIGATION
========================= */

header {
    background: #ffffff;
    border-bottom: 1px solid #e5e7eb;
    position: sticky;
    top: 0;
    z-index: 1000;
}

.navbar {
    height: 75px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 22px;
    font-weight: 700;
    color: #123b70;
}

.logo span {
    color: #2b7bbb;
}

.nav-links {
    display: flex;
    gap: 30px;
    list-style: none;
}

.nav-links a {
    color: #475569;
    font-size: 15px;
    font-weight: 500;
    transition: 0.3s;
}

.nav-links a:hover {
    color: #1769aa;
}


/* =========================
   HERO SECTION
========================= */

.hero {
    background:
        linear-gradient(
            120deg,
            #0f3158 0%,
            #174f80 55%,
            #2879a9 100%
        );

    color: white;
    padding: 90px 0;
}

.hero-content {
    display: grid;
    grid-template-columns: 260px 1fr;
    gap: 60px;
    align-items: center;
}


/* PROFILE PHOTO */

.profile-photo {
    width: 240px;
    height: 240px;
    border-radius: 50%;
    background: #ffffff;
    border: 7px solid rgba(255,255,255,0.25);

    display: flex;
    justify-content: center;
    align-items: center;

    color: #174f80;
    font-size: 70px;
    font-weight: 700;

    box-shadow: 0 15px 40px rgba(0,0,0,0.2);
}


/* HERO TEXT */

.hero h1 {
    font-size: 48px;
    line-height: 1.2;
    margin-bottom: 12px;
}

.hero h2 {
    font-size: 22px;
    font-weight: 400;
    color: #dbeafe;
    margin-bottom: 20px;
}

.hero-location {
    font-size: 16px;
    color: #d7e8f7;
    margin-bottom: 25px;
}

.hero-description {
    max-width: 800px;
    font-size: 17px;
    color: #edf6ff;
}


/* BUTTON */

.btn {
    display: inline-block;
    margin-top: 30px;
    padding: 12px 25px;
    background: white;
    color: #174f80;
    border-radius: 6px;
    font-weight: 600;
    transition: 0.3s;
}

.btn:hover {
    background: #e7f2fa;
}


/* =========================
   STATS
========================= */

.stats {
    background: white;
    box-shadow: 0 5px 25px rgba(0,0,0,0.06);
}

.stats-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
}

.stat {
    text-align: center;
    padding: 28px;
    border-right: 1px solid #e5e7eb;
}

.stat:last-child {
    border-right: none;
}

.stat h3 {
    color: #174f80;
    font-size: 28px;
}

.stat p {
    color: #64748b;
    font-size: 14px;
}


/* =========================
   SECTIONS
========================= */

section {
    padding: 85px 0;
}

.section-heading {
    text-align: center;
    margin-bottom: 55px;
}

.section-heading h2 {
    font-size: 34px;
    color: #123b70;
    margin-bottom: 10px;
}

.section-heading p {
    color: #64748b;
}


/* =========================
   ABOUT
========================= */

.about-content {
    max-width: 950px;
    margin: auto;
    text-align: center;
}

.about-content p {
    font-size: 17px;
    color: #475569;
    margin-bottom: 20px;
}


/* =========================
   RESEARCH AREAS
========================= */

.research {
    background: #eef4f9;
}

.research-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.research-card {
    background: white;
    padding: 30px;
    border-radius: 10px;
    border: 1px solid #e1e8ef;
    transition: 0.3s;
}

.research-card:hover {
    transform: translateY(-6px);
    box-shadow: 0 12px 30px rgba(0,0,0,0.08);
}

.research-icon {
    width: 50px;
    height: 50px;
    border-radius: 8px;
    background: #e7f2fa;
    color: #1769aa;

    display: flex;
    align-items: center;
    justify-content: center;

    font-size: 23px;
    margin-bottom: 20px;
}

.research-card h3 {
    color: #123b70;
    margin-bottom: 10px;
}

.research-card p {
    color: #64748b;
    font-size: 15px;
}


/* =========================
   EXPERTISE
========================= */

.expertise-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 12px;
    max-width: 900px;
    margin: auto;
}

.expertise-item {
    background: white;
    border: 1px solid #dbe3ec;
    padding: 12px 22px;
    border-radius: 30px;
    color: #174f80;
    font-size: 15px;
    font-weight: 500;
}


/* =========================
   ACADEMIC PROFILE
========================= */

.profile-section {
    background: #ffffff;
}

.profile-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
}

.profile-box {
    padding: 30px;
    background: #f7f9fc;
    border-left: 4px solid #2879a9;
}

.profile-box h3 {
    color: #123b70;
    margin-bottom: 12px;
}

.profile-box p {
    color: #64748b;
}


/* =========================
   CONTACT
========================= */

.contact {
    background: #123b70;
    color: white;
}

.contact .section-heading h2 {
    color: white;
}

.contact .section-heading p {
    color: #cbdbea;
}

.contact-box {
    max-width: 750px;
    margin: auto;
    text-align: center;
}

.contact-box p {
    margin: 10px 0;
    color: #e2edf7;
}


/* =========================
   FOOTER
========================= */

footer {
    background: #0b2746;
    color: #b9cad9;
    text-align: center;
    padding: 25px;
    font-size: 14px;
}


/* =========================
   MOBILE RESPONSIVE
========================= */

@media (max-width: 900px) {

    .hero-content {
        grid-template-columns: 1fr;
        text-align: center;
    }

    .profile-photo {
        margin: auto;
    }

    .hero-description {
        margin: auto;
    }

    .stats-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .research-grid {
        grid-template-columns: 1fr 1fr;
    }

    .profile-grid {
        grid-template-columns: 1fr;
    }
}


@media (max-width: 600px) {

    .navbar {
        height: auto;
        padding: 18px 0;
    }

    .nav-links {
        display: none;
    }

    .hero {
        padding: 60px 0;
    }

    .hero h1 {
        font-size: 35px;
    }

    .hero h2 {
        font-size: 19px;
    }

    .profile-photo {
        width: 190px;
        height: 190px;
        font-size: 55px;
    }

    .stats-grid {
        grid-template-columns: 1fr 1fr;
    }

    .stat {
        padding: 20px 10px;
    }

    .research-grid {
        grid-template-columns: 1fr;
    }

    section {
        padding: 60px 0;
    }

    .section-heading h2 {
        font-size: 28px;
    }
}

</style>
</head>


<body>


<!-- =========================
     NAVIGATION
========================= -->

<header>

    <div class="container navbar">

        <div class="logo">
            Dr. <span>Asad Iqbal</span>
        </div>

        <ul class="nav-links">

            <li>
                <a href="#home">Home</a>
            </li>

            <li>
                <a href="#about">About</a>
            </li>

            <li>
                <a href="#research">Research</a>
            </li>

            <li>
                <a href="#expertise">Expertise</a>
            </li>

            <li>
                <a href="#contact">Contact</a>
            </li>

        </ul>

    </div>

</header>



<!-- =========================
     HERO
========================= -->

<section class="hero" id="home">

    <div class="container hero-content">


        <!-- PROFILE PHOTO -->

        <div class="profile-photo">

            AI

        </div>


        <!-- PROFILE INFORMATION -->

        <div>

            <h1>
                Dr. Muhammad Asad Iqbal
            </h1>

            <h2>
                Assistant Professor of Mathematics
            </h2>

            <div class="hero-location">

                Riphah International University,
                Sahiwal Campus

            </div>

            <p class="hero-description">

                Mathematician, researcher, and educator with
                research interests in Algebra, Topological Groups,
                Selection Principles, Game Theory, Algebraic Geometry,
                and Vector Spaces, with a strong interest in Linear
                Algebra, Calculus, Data Science, and Artificial
                Intelligence.

            </p>

            <a href="#about" class="btn">
                View Academic Profile
            </a>

        </div>

    </div>

</section>



<!-- =========================
     ACADEMIC STATS
========================= -->

<div class="stats">

    <div class="container stats-grid">

        <div class="stat">

            <h3>Mathematics</h3>

            <p>
                Academic Discipline
            </p>

        </div>


        <div class="stat">

            <h3>Research</h3>

            <p>
                Pure & Applied Mathematics
            </p>

        </div>


        <div class="stat">

            <h3>Teaching</h3>

            <p>
                Mathematics & Data Science
            </p>

        </div>


        <div class="stat">

            <h3>AI</h3>

            <p>
                Computational Applications
            </p>

        </div>

    </div>

</div>



<!-- =========================
     ABOUT
========================= -->

<section id="about">

    <div class="container">

        <div class="section-heading">

            <h2>About Me</h2>

            <p>
                Academic Profile & Professional Introduction
            </p>

        </div>


        <div class="about-content">

            <p>

                I am <strong>Dr. Muhammad Asad Iqbal</strong>,
                currently serving as an <strong>Assistant Professor
                of Mathematics at Riphah International University,
                Sahiwal Campus</strong>.

            </p>

            <p>

                My academic and research interests primarily focus
                on pure mathematics, particularly Algebra,
                Topological Groups, Vector Spaces, Selection
                Principles, Game Theory, and Algebraic Geometry.

            </p>

            <p>

                I am also interested in Linear Algebra, Calculus,
                Data Science, and Artificial Intelligence, with an
                emphasis on connecting mathematical foundations
                with modern computational and data-driven
                applications.

            </p>

        </div>

    </div>

</section>



<!-- =========================
     RESEARCH
========================= -->

<section class="research" id="research">

    <div class="container">

        <div class="section-heading">

            <h2>Research Interests</h2>

            <p>
                Areas of mathematical research
            </p>

        </div>


        <div class="research-grid">


            <div class="research-card">

                <div class="research-icon">
                    ∑
                </div>

                <h3>
                    Algebra
                </h3>

                <p>

                    Study of algebraic structures, properties,
                    and mathematical relationships.

                </p>

            </div>


            <div class="research-card">

                <div class="research-icon">
                    ∞
                </div>

                <h3>
                    Topological Groups
                </h3>

                <p>

                    Research in topological groups,
                    topological algebra, and related
                    structural properties.

                </p>

            </div>


            <div class="research-card">

                <div class="research-icon">
                    ◇
                </div>

                <h3>
                    Selection Principles
                </h3>

                <p>

                    Covering properties, selection principles,
                    and their applications in topology.

                </p>

            </div>


            <div class="research-card">

                <div class="research-icon">
                    ♟
                </div>

                <h3>
                    Game Theory
                </h3>

                <p>

                    Mathematical games and game-theoretic
                    approaches to problems in topology.

                </p>

            </div>


            <div class="research-card">

                <div class="research-icon">
                    V
                </div>

                <h3>
                    Vector Spaces
                </h3>

                <p>

                    Vector spaces, linear transformations,
                    and related concepts in linear algebra.

                </p>

            </div>


            <div class="research-card">

                <div class="research-icon">
                    AI
                </div>

                <h3>
                    Data Science & AI
                </h3>

                <p>

                    Mathematical foundations and applications
                    of data science and artificial intelligence.

                </p>

            </div>


        </div>

    </div>

</section>



<!-- =========================
     EXPERTISE
========================= -->

<section id="expertise">

    <div class="container">

        <div class="section-heading">

            <h2>
                Areas of Expertise
            </h2>

            <p>
                Academic and professional expertise
            </p>

        </div>


        <div class="expertise-list">

            <div class="expertise-item">
                Algebra
            </div>

            <div class="expertise-item">
                Topological Groups
            </div>

            <div class="expertise-item">
                Vector Spaces
            </div>

            <div class="expertise-item">
                Selection Principles
            </div>

            <div class="expertise-item">
                Game Theory
            </div>

            <div class="expertise-item">
                Algebraic Geometry
            </div>

            <div class="expertise-item">
                Linear Algebra
            </div>

            <div class="expertise-item">
                Calculus
            </div>

            <div class="expertise-item">
                Data Science
            </div>

            <div class="expertise-item">
                Artificial Intelligence
            </div>

        </div>

    </div>

</section>



<!-- =========================
     ACADEMIC PROFILE
========================= -->

<section class="profile-section">

    <div class="container">

        <div class="section-heading">

            <h2>
                Academic Profile
            </h2>

            <p>
                Teaching, research and professional interests
            </p>

        </div>


        <div class="profile-grid">


            <div class="profile-box">

                <h3>
                    Teaching
                </h3>

                <p>

                    Mathematics education with interests in
                    Linear Algebra, Calculus, mathematical
                    foundations of Data Science, and
                    Artificial Intelligence.

                </p>

            </div>


            <div class="profile-box">

                <h3>
                    Research
                </h3>

                <p>

                    Research interests include Topological Groups,
                    Selection Principles, Topological Games,
                    Algebra, Vector Spaces, and Algebraic Geometry.

                </p>

            </div>


            <div class="profile-box">

                <h3>
                    Applied Mathematics
                </h3>

                <p>

                    Exploring mathematical concepts and methods
                    for modern computational, analytical,
                    and data-driven applications.

                </p>

            </div>


            <div class="profile-box">

                <h3>
                    Artificial Intelligence
                </h3>

                <p>

                    Interest in the mathematical foundations of
                    machine learning, neural networks, data
                    analysis, and artificial intelligence.

                </p>

            </div>


        </div>

    </div>

</section>



<!-- =========================
     CONTACT
========================= -->

<section class="contact" id="contact">

    <div class="container">

        <div class="section-heading">

            <h2>
                Contact
            </h2>

            <p>
                Academic correspondence
            </p>

        </div>


        <div class="contact-box">

            <p>
                <strong>
                    Dr. Muhammad Asad Iqbal
                </strong>
            </p>

            <p>
                Assistant Professor of Mathematics
            </p>

            <p>
                Riphah International University,
                Sahiwal Campus
            </p>

        </div>

    </div>

</section>



<!-- =========================
     FOOTER
========================= -->

<footer>

    © 2026 Dr. Muhammad Asad Iqbal.
    All Rights Reserved.

</footer>


</body>
</html>
