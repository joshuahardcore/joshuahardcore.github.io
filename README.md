<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imię i Nazwisko | Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav class="container">
            <a href="index.html" class="logo">Twoje Imię.</a>
            <ul class="nav-links">
                <li><a href="#o-mnie">O mnie</a></li>
                <li><a href="#projekty">Projekty</a></li>
                <li><a href="#kontakt">Kontakt</a></li>
                <li><a href="sowka.html" class="sowka-link">🦉 Sówka</a></li>
            </ul>
        </nav>
    </header>

    <main class="container">
        <section id="o-mnie" class="hero">
            <h1>Cześć, tworzę kod i proste rozwiązania.</h1>
            <p class="subtitle">
                Jestem początkującym programistą / twórcą. Interesuję się technologią, 
                minimalistycznym designem i rozwiązywaniem problemów za pomocą kodu.
            </p>
        </section>

        <section id="projekty">
            <h2>Wybrane projekty</h2>
            <div class="projects-grid">
                <div class="card">
                    <h3>🦉 Program Sówka</h3>
                    <p>Mój autorski program przeniesiony bezpośrednio do przeglądarki internetowej.</p>
                    <a href="sowka.html" class="card-link">Uruchom program &rarr;</a>
                </div>
                <div class="card">
                    <h3>Projekt Drugi</h3>
                    <p>Krótki opis kolejnego projektu, wykorzystanych technologii oraz celu, jaki spełnia.</p>
                    <a href="https://github.com/" target="_blank" class="card-link">Zobacz na GitHub &rarr;</a>
                </div>
                <div class="card">
                    <h3>Projekt Trzeci</h3>
                    <p>Krótki opis trzeciego projektu. Możesz tu podlinkować repozytorium lub wersję live.</p>
                    <a href="https://github.com/" target="_blank" class="card-link">Zobacz na GitHub &rarr;</a>
                </div>
            </div>
        </section>

        <section id="kontakt">
            <h2>Kontakt</h2>
            <p>Chcesz porozmawiać lub nawiązać współpracę? Napisz do mnie:</p>
            <div class="contact-links">
                <a href="mailto:twoj@email.pl">twoj@email.pl</a>
                <a href="https://github.com/twoj-nick" target="_blank">GitHub</a>
                <a href="https://linkedin.com" target="_blank">LinkedIn</a>
            </div>
        </section>
    </main>

    <footer class="container">
        <p>&copy; 2026 Twoje Imię. Hosted on GitHub Pages.</p>
    </footer>

</body>
</html>
