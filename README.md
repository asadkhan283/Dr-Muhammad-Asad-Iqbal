<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Dr. Muhammad Asad Iqbal | Mathematics</title>

<style>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #f4f7fb;
    color: #222;
}

/* NAVIGATION */

nav {
    width: 100%;
    background: #ffffff;
    padding: 18px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 2px 15px rgba(0,0,0,0.08);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.logo {
    font-size: 22px;
    font-weight: bold;
    color: #173f8a;
}

nav ul {
    display: flex;
    list-style: none;
    gap: 30px;
}

nav ul li a {
    text-decoration: none;
    color: #333;
    font-weight: 500;
}

nav ul li a:hover {
    color: #173f8a;
}

/* HERO SECTION */

.hero {
    min-height: 600px;
    background: linear-gradient(135deg, #173f8a, #2563b8);
    color: white;
    display: flex;
    align-items: center;
    padding: 80px 10%;
}

.hero-content {
    max-width: 850px;
}

.hero h1 {
    font-size: 58px;
    margin-bottom: 15px;
}

.hero h2 {
    font-size: 26px;
    font-weight: normal;
    margin-bottom: 25px;
    color: #dbeafe;
}

.hero p {
    font-size: 19px;
    line-height: 1.8;
    max-width: 750px;
    color: #f1f5f9;
}

.button {
    display: inline-block;
    margin-top: 30px;
    padding: 14px 28px;
    background: white;
    color: #173f8a;
    text-decoration: none;
    border-radius: 30px;
    font-weight: bold;
}

.button:hover {
    background: #e5e7eb;
}

/* GENERAL */

section {
    padding: 80px 10%;
}

.section-title {
    text-align: center;
    font-size: 35px;
    color: #173f8a;
    margin-bottom: 15px;
}

.section-subtitle {
    text-align: center;
    color: #666;
    margin-bottom: 50px;
    font-size: 17px;
}

/* ABOUT */

.about {
    background: white;
}

.about-text {
    max-width: 900px;
    margin: auto;
    text-align: center;
}

.about-text p {
    font-size: 18px;
    line-height: 1.9;
    color: #555;
}

/* EXPERTISE */

.expertise {
    background: #f4f7fb;
}

.cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.card {
    background: white;
    padding: 30px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 5px 20px rgba(0,0,0,0.07);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-8px);
}

.card-icon {
    font-size: 40px;
    margin-bottom: 15px;
}

.card h3 {
    color: #173f8a;
    margin-bottom: 12px;
}

.card p {
    color: #666;
    line-height: 1.6;
}

/* RESEARCH */

.research {
    background: white;
}

.research-list {
    max-width: 900px;
    margin: auto;
}

.research-item {
    padding: 22px;
    margin-bottom: 15px;
    background: #f4f7fb;
    border-left: 5px solid #173f8a;
    border-radius: 8px;
}

.research-item h3 {
    color: #173f8a;
    margin-bottom: 7px;
}

/* CONTACT */

.contact {
    background: #173f8a;
    color: white;
    text-align: center;
}

.contact .section-title {
    color: white;
}

.contact p {
    font-size: 18px;
    margin: 10px;
}

/* FOOTER */

footer {
    background: #102d63;
    color: white;
    text-align: center;
    padding: 25px;
    font-size: 14px;
}

/* MOBILE */

@media(max-width: 800px) {

    nav {
        padding: 15px 5%;
    }

    nav ul {
        display: none;
    }

    .hero {
        padding: 70px 7%;
    }

    .hero h1 {
        font-size: 40px;
    }

    .hero h2 {
        font-size: 21px;
    }

    .hero p {
        font-size: 17px;
    }

    section {
        padding: 60px 7%;
    }

    .cards {
        grid-template-columns: 1fr;
    }

}

</style>
</head>

<body>


<!-- NAVIGATION -->

<nav>

    <div class="logo">
        Dr. Asad Iqbal
    </div>

    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#expertise">Expertise</a></li>
        <li><a href="#research">Research</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>

</nav>


<!-- HERO / PROFILE -->

<section class="hero" id="home">

    <div class="hero-content">

        <h1>
            Dr. Muhammad Asad Iqbal
        </h1>

        <h2>
            Assistant Professor of Mathematics
        </h2>

        <p>
            Riphah International University, Sahiwal Campus
        </p>

        <p style="margin-top:20px;">

            Mathematician and educator with research interests in
            Algebra, Topological Groups, Selection Principles,
            Game Theory, Algebraic Geometry, and Vector Spaces,
            with additional expertise in Linear Algebra, Calculus,
            Data Science, and Artificial Intelligence.

        </p>

        <a href="#about" class="button">
            Explore My Profile
        </a>

    </div>

</section>


<!-- ABOUT -->

<section class="about" id="about">

    <h2 class="section-title">
        About Me
    </h2>

    <p class="section-subtitle">
        Mathematics • Research • Teaching • Data & AI
    </p>

    <div class="about-text">

        <p>

            I am <strong>Dr. Muhammad Asad Iqbal</strong>, currently serving
            as an <strong>Assistant Professor of Mathematics at Riphah
            International University, Sahiwal Campus</strong>.

            My academic interests cover both pure and applied mathematics.
            My research focuses particularly on Algebra, Topological Groups,
            Vector Spaces, Selection Principles, Game Theory, and Algebraic
            Geometry.

        </p>

        <br>

        <p>

            Alongside my research in mathematics, I am interested in
            Linear Algebra, Calculus, Data Science, and Artificial
            Intelligence, especially in exploring how mathematical
            concepts can contribute to modern computational and
            data-driven applications.

        </p>

    </div>

</section>


<!-- EXPERTISE -->

<section class="expertise" id="expertise">

    <h2 class="section-title">
        Areas of Expertise
    </h2>

    <p class="section-subtitle">
        Research and academic interests
    </p>


    <div class="cards">


        <div class="card">

            <div class="card-icon">∑</div>

            <h3>Algebra</h3>

            <p>
                Algebraic structures, algebraic methods,
                and their applications in mathematical research.
            </p>

        </div>


        <div class="card">

            <div class="card-icon">∞</div>

            <h3>Topological Groups</h3>

            <p>
                Topological groups, topological algebra,
                and related structural properties.
            </p>

        </div>


        <div class="card">

            <div class="card-icon">◇</div>

            <h3>Selection Principles</h3>

            <p>
                Selection principles, covering properties,
                and related problems in topology.
            </p>

        </div>


        <div class="card">

            <div class="card-icon">♟</div>

            <h3>Game Theory</h3>

            <p>
                Mathematical games, topological games,
                and strategic approaches to mathematical problems.
            </p>

        </div>


        <div class="card">

            <div class="card-icon">V</div>

            <h3>Vector Spaces</h3>

            <p>
                Vector spaces, linear transformations,
                and structural aspects of linear algebra.
            </p>

        </div>


        <div class="card">

            <div class="card-icon">AI</div>

            <h3>Data Science & AI</h3>

            <p>
                Mathematical foundations of data science,
                machine learning, and artificial intelligence.
            </p>

        </div>


    </div>

</section>


<!-- RESEARCH -->

<section class="research" id="research">

    <h2 class="section-title">
        Research Interests
    </h2>

    <p class="section-subtitle">
        Current academic interests
    </p>


    <div class="research-list">

        <div class="research-item">

            <h3>Topological Groups</h3>

            <p>
                Research in topological groups, topological algebra,
                and related structural properties.
            </p>

        </div>


        <div class="research-item">

            <h3>Selection Principles</h3>

            <p>
                Study of Menger-type properties, selection principles,
                and their generalizations in topology.
            </p>

        </div>


        <div class="research-item">

            <h3>Topological Games</h3>

            <p>
                Investigation of game-theoretic methods and
                topological games associated with covering properties.
            </p>

        </div>


        <div class="research-item">

            <h3>Mathematics, Data Science & AI</h3>

            <p>
                Exploring connections between mathematical theory,
                data analysis, machine learning, and artificial intelligence.
            </p>

        </div>

    </div>

</section>


<!-- CONTACT -->

<section class="contact" id="contact">

    <h2 class="section-title">
        Contact
    </h2>

    <p>
        Dr. Muhammad Asad Iqbal
    </p>

    <p>
        Assistant Professor of Mathematics
    </p>

    <p>
        Riphah International University, Sahiwal Campus
    </p>

</section>


<!-- FOOTER -->

<footer>

    © 2026 Dr. Muhammad Asad Iqbal | Academic Profile

</footer>


</body>
</html>
