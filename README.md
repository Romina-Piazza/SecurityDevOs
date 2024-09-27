<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Servizi di Cybersecurity e Analisi dei Rischi">
    <title>Sicurezza Informatica - Romina Piazza</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Romina Piazza Cybersecurity</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#about">Chi Siamo</a></li>
                <li><a href="#services">Servizi</a></li>
                <li><a href="#projects">Progetti</a></li>
                <li><a href="#contact">Contatti</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h2>Proteggiamo la tua attività dai rischi informatici</h2>
        <p>Servizi di Cybersecurity, analisi dei rischi e protezione dei dati per aziende e privati.</p>
        <a href="#services" class="button">Scopri i nostri servizi</a>
    </section>

    <section id="about">
        <h2>Chi Siamo</h2>
        <p>Siamo esperti nel campo della sicurezza informatica con anni di esperienza in analisi dei rischi, difesa da attacchi cyber e protezione dei dati sensibili. Collaboriamo con aziende globali come Google per garantire la massima sicurezza.</p>
    </section>

    <section id="services">
        <h2>Servizi</h2>
        <ul>
            <li>Analisi dei rischi informatici</li>
            <li>Protezione contro attacchi DDoS</li>
            <li>Auditing di sicurezza e compliance</li>
            <li>Formazione del personale in cybersecurity</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Progetti Recenti</h2>
        <ul>
            <li>Collaborazione con Google su progetti di Cyber Risk</li>
            <li>Implementazione di strategie di sicurezza per piccole e medie imprese</li>
            <li>Protezione dei dati sensibili per enti pubblici e privati</li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contattaci</h2>
        <p>Per maggiori informazioni sui nostri servizi o per una consulenza, contattaci:</p>
        <form action="submit_form.php" method="POST">
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Messaggio:</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Invia</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Romina Piazza - Cybersecurity Services. Tutti i diritti riservati.</p>
    </footer>
</body>
</html>
