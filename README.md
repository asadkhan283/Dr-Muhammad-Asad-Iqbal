<!DOCTYPE html>
<html>
<head>
    <title>Dr. Muhammad Asad Iqbal</title>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, sans-serif;
            background: #f5f7fa;
            color: #222;
        }

        /* Navigation */

        .navbar {
            background: #ffffff;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #ddd;
        }

        .logo {
            font-size: 22px;
            font-weight: bold;
            color: #123b70;
        }

        .menu a {
            margin-left: 25px;
            text-decoration: none;
            color: #333;
            font-size: 15px;
        }

        .menu a:hover {
            color: #1769aa;
        }


        /* Hero */

        .hero {
            background: linear-gradient(120deg, #123b70, #2879a9);
            color: white;
            padding: 90px 8%;
        }

        .hero-container {
            max-width: 1100px;
            margin: auto;
            display: flex;
            align-items: center;
            gap: 60px;
        }

        .photo {
            width: 220px;
            height: 220px;
            background: white;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #123b70;
            font-size: 55px;
            font-weight: bold;
            flex-shrink: 0;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }

        .hero h2 {
            font-size: 23px;
            font-weight: normal;
            color: #dcecff;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 17px;
            line-height: 1.8;
            max-width: 750px;
        }


        /* Buttons */

        .button {
            display: inline-block;
            margin-top: 25px;
            padding: 12px 25px;
            background: white;
            color: #123b70;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
        }


        /* Sections */

        .section {
            padding: 70px 8%;
        }

        .section-container {
            max-width: 1100px;
            margin: auto;
        }

        .title {
            text-align: center;
            font-size: 32px;
            color: #123b70;
            margin-bottom: 15px;
        }

        .subtitle {
            text-align: center;
            color: #777;
            margin-bottom: 40px;
        }


        /* About */

        .about {
            background: white;
        }

        .about-text {
            max-width: 900px;
            margin: auto;
            text-align: center;
        }

        .about-text p {
            font-size: 17px;
            line-height: 1.9;
            color: #555;
            margin-bottom: 18px;
        }


        /* Research */

        .research {
            background: #f5f7fa;
        }

        .cards {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            border: 1px solid #e0e5eb;
        }

        .card h3 {
            color: #123b70;
            margin-bottom: 12px;
        }

        .card p {
            color: #666;
            line-height: 1.6;
        }


        /* Expertise */

        .expertise {
            background: white;
        }

        .skills {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 12px;
        }

        .skill {
            padding: 12px 20px;
            background: #edf4fa;
            color: #123b70;
            border-radius: 25px;
            font-weight: bold;
        }


        /* Contact */

        .contact {
            background: #123b70;
            color: white;
            text-align: center;
        }

        .contact .title {
            color: white;
        }

        .contact p {
            margin: 8px;
        }


        /* Footer */

        footer {
            background: #0b2746;
            color: white;
            text-align: center;
            padding: 20px;
        }


        /* Mobile */

        @media(max-width: 800px) {

            .navbar {
                display: block;
                text-align: center;
            }

            .menu {
                margin-top: 15px;
            }

            .menu a {
                margin: 8px;
                display: inline-block;
            }

            .hero-container {
                display: block;
                text-align: center;
            }

            .photo {
                margin: auto;
                margin-bottom: 30px;
            }

            .hero h1 {
                font-size: 36px;
            }

            .cards {
                grid-template-columns: 1fr;
            }

        }

    </style>
</head>


<body>


<!-- NAVIGATION -->

<div class="navbar">

    <div class="logo">
        Dr. Asad Iqbal
    </div>

    <div class="menu">

        <a href="#home">Home</a>

        <a href="#about">About</a>

        <a href="#research">Research</a>

        <a href="#expertise">Expertise</a>

        <a href="#contact">Contact</a>

    </div>

</div>


<!-- HERO -->

<div class="hero" id="home">

    <div class="hero-container">

        <div class="photo">
            AI
        </div>

        <div>

            <h1>
                Dr. Muhammad Asad Iqbal
            </h1>

            <h2>
                Assistant Professor of Mathematics
            </h2>

            <p>
                Riphah International University, Sahiwal Campus
            </p>

            <p style="margin-top:15px;">

                Mathematician, researcher and educator with interests
                in Algebra, Topological Groups, Selection Principles,
                Game Theory, Algebraic Geometry, Vector Spaces,
                Linear Algebra, Calculus, Data Science and
                Artificial Intelligence.

            </p>

            <a href="#about" class="button">
                View Profile
            </a>

        </div>

    </div>

</div>


<!-- ABOUT -->

<div class="section about" id="about">

    <div class="section-container">

        <h2 class="title">
            About Me
        </h2>

        <p class="subtitle">
            Academic Profile
        </p>

        <div class="about-text">

            <p>

                I am <strong>Dr. Muhammad Asad Iqbal</strong>,
                currently working as an <strong>Assistant Professor
                of Mathematics at Riphah International University,
                Sahiwal Campus</strong>.

            </p>

            <p>

                My research interests are primarily focused on
                pure mathematics, particularly Algebra, Topological
                Groups, Vector Spaces, Selection Principles,
                Game Theory, and Algebraic Geometry.

            </p>

            <p>

                I also have academic interests in Linear Algebra,
                Calculus, Data Science, and Artificial Intelligence,
                with an emphasis on connecting mathematical concepts
                with modern computational applications.

            </p>

        </div>

    </div>

</div>


<!-- RESEARCH -->

<div class="section research" id="research">

    <div class="section-container">

        <h2 class="title">
            Research Interests
        </h2>

        <p class="subtitle">
            Areas of research and academic interest
        </p>


        <div class="cards">

            <div class="card">

                <h3>
                    Algebra
                </h3>

                <p>
                    Research in algebraic structures and
                    related mathematical theories.
                </p>

            </div>


            <div class="card">

                <h3>
                    Topological Groups
                </h3>

                <p>
                    Study of topological groups, topological
                    algebra and related structures.
                </p>

            </div>


            <div class="card">

                <h3>
                    Selection Principles
                </h3>

                <p>
                    Selection principles and covering properties
                    in topology.
                </p>

            </div>


            <div class="card">

                <h3>
                    Game Theory
                </h3>

                <p>
                    Mathematical and topological games and
                    their applications.
                </p>

            </div>


            <div class="card">

                <h3>
                    Algebraic Geometry
                </h3>

                <p>
                    Algebraic structures and geometric methods
                    in mathematics.
                </p>

            </div>


            <div class="card">

                <h3>
                    Data Science & AI
                </h3>

                <p>
                    Mathematical foundations of data science,
                    machine learning and artificial intelligence.
                </p>

            </div>

        </div>

    </div>

</div>


<!-- EXPERTISE -->

<div class="section expertise" id="expertise">

    <div class="section-container">

        <h2 class="title">
            Areas of Expertise
        </h2>

        <p class="subtitle">
            Academic and professional expertise
        </p>

        <div class="skills">

            <div class="skill">Algebra</div>

            <div class="skill">Topological Groups</div>

            <div class="skill">Vector Spaces</div>

            <div class="skill">Selection Principles</div>

            <div class="skill">Game Theory</div>

            <div class="skill">Algebraic Geometry</div>

            <div class="skill">Linear Algebra</div>

            <div class="skill">Calculus</div>

            <div class="skill">Data Science</div>

            <div class="skill">Artificial Intelligence</div>

        </div>

    </div>

</div>


<!-- CONTACT -->

<div class="section contact" id="contact">

    <div class="section-container">

        <h2 class="title">
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

    </div>

</div>


<!-- FOOTER -->

<footer>

    © 2026 Dr. Muhammad Asad Iqbal

</footer>


</body>
</html>
