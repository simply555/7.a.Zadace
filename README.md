<!DOCTYPE html>
<html lang="hr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Školske Zadace</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to CSS if you have one -->
    <script>
        // Funkcija za dodavanje zadatka
        function addHomework() {
            const dateInput = document.getElementById('dateInput').value;
            const homeworkInput = document.getElementById('homeworkInput').value;
            const homeworkList = document.getElementById('homeworkList');

            // Provjera je li datum i zadatak unesen
            if (dateInput && homeworkInput) {
                const listItem = document.createElement('li');
                listItem.textContent = `${dateInput}: ${homeworkInput}`;
                homeworkList.appendChild(listItem);
                document.getElementById('homeworkInput').value = ''; // Očisti unos
            } else {
                alert('Molimo unesite datum i domaću zadaću!');
            }
        }
    </script>
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
                <input type="date" id="dateInput" placeholder="Datum" />
                <input type="text" id="homeworkInput" placeholder="Domaća zadaća" />
                <button onclick="addHomework()">Dodaj zadatak</button>
            </div>
            <ul id="homeworkList">
                <!-- Ovdje će se dodavati domaće zadaće -->
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
</body>
</html>
