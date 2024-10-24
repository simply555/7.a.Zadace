<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Školske Zadace</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to CSS if you have one -->
</head>
<body>
    <header>
        <h1>Dobrodošli u Školu</h1>
        <nav>
            <ul>
                <li><a href="#homework">Zadace</a></li>
                <li><a href="#announcements">Najave</a></li>
                <li><a href="#contact">Kontakt</a></li>
                <li><a href="#resources">Resursi</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="homework">
            <h2>Zadace za danas</h2>
            <ul>
                <li>1. Čitanje stranica 10-15 iz udžbenika.</li>
                <li>2. Rješavanje zadatka 5 iz matematike.</li>
                <li>3. Pisanje sastava na temu "Moja omiljena knjiga".</li>
                <li>4. Vježbe iz engleskog jezika (str. 20-25).</li>
                <li>5. Rješavanje zadatka 12 iz prirode.</li>
            </ul>
        </section>
        <section id="announcements">
            <h2>Najave</h2>
            <p>Nema važnih najava danas.</p>
            <ul>
                <li>Rok za predaju projekata je 15. novembar.</li>
                <li>Izlet u zoološki vrt planiran je za 30. novembar.</li>
            </ul>
        </section>
        <section id="resources">
            <h2>Resursi</h2>
            <p>Pogledajte sledeće resurse za dodatnu pomoć:</p>
            <ul>
                <li><a href="https://www.khanacademy.org">Khan Academy</a></li>
                <li><a href="https://www.edx.org">edX</a></li>
                <li><a href="https://www.coursera.org">Coursera</a></li>
            </ul>
        </section>
        <section id="contact">
            <h2>Kontakt</h2>
            <p>Možete me kontaktirati putem e-maila: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
            <form action="#" method="post">
                <label for="name">Ime:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">E-mail:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Poruka:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Pošalji</button>
            </form>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Školska stranica</p>
        <img src="school_image.jpg" alt="Slika škole" style="max-width: 100%; height: auto;">
    </footer>
</body>
</html>

