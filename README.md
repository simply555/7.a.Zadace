<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Školske Zadace</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to CSS -->
</head>
<body>
    <header>
        <h1>Dobrodošli u Školu</h1>
        <nav>
            <ul>
                <li><a href="#homework">Zadace</a></li>
                <li><a href="#announcements">Najave</a></li>
                <li><a href="#contact">Kontakt</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="homework">
            <h2>Zadace za danas</h2>
            <div>
                <input type="date" id="dateInput">
                <input type="text" id="taskInput" placeholder="Unesite zadaću">
                <button onclick="addTask()">Dodaj zadaću</button>
            </div>
            <ul id="homework-list">
                <!-- Zadaće će se dodavati ovdje -->
            </ul>
        </section>
        <section id="announcements">
            <h2>Najave</h2>
            <p>Nema važnih najava danas.</p>
        </section>
        <section id="contact">
            <h2>Kontakt</h2>
            <p>Možete me kontaktirati putem e-maila: <a href="mailto:youremail@example.com">youremail@example.com</a></p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Školska stranica</p>
    </footer>

    <script src="script.js"></script> <!-- Link to JavaScript -->
</body>
</html>

