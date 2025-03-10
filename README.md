# Sebi-Logistik-AG
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Sebi Logistik AG - Transporturi eficiente, sigure și rapide, cu flota de camioane Scania noi. Asistență rutieră 24/7.">
    <title>Sebi Logistik AG</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- HEADER -->
    <header>
        <div class="logo">
            <h1>Sebi Logistik AG</h1>
            <p>Transporturi rapide și sigure</p>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Acasă</a></li>
                <li><a href="#about">Despre Noi</a></li>
                <li><a href="#services">Servicii</a></li>
                <li><a href="#careers">Carieră</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- HOME -->
    <section id="home" class="home">
        <div class="home-content">
            <h2>Transporturi eficiente, sigure și rapide</h2>
            <p>Cu flota noastră de 9 camioane Scania noi, asigurăm transporturi de încredere pentru clienți din întreaga Europă.</p>
            <a href="#contact" class="cta">Contactează-ne</a>
        </div>
    </section>

    <!-- DESPRE NOI -->
    <section id="about" class="about">
        <h2>Despre Sebi Logistik AG</h2>
        <p>Sebi Logistik AG este o companie de transport cu o flota de 9 camioane Scania noi. Oferim cele mai bune salarii din domeniul transporturilor, asistență rutieră 24/7 și dispecerat continuu pentru siguranța clienților noștri.</p>
    </section>

    <!-- SERVICII -->
    <section id="services" class="services">
        <h2>Serviciile Noastre</h2>
        <div class="service">
            <h3>Transporturi naționale și internaționale</h3>
            <p>Oferim servicii de transport rapid și sigur pe teritoriul național și internațional.</p>
        </div>
        <div class="service">
            <h3>Asistență rutieră 24/7</h3>
            <p>Suntem disponibili 24/7 pentru asistență rutieră, indiferent de situația în care te afli.</p>
        </div>
        <div class="service">
            <h3>Dispecerat 24/7</h3>
            <p>Dispeceratul nostru este deschis non-stop pentru a răspunde la toate solicitările tale.</p>
        </div>
    </section>

    <!-- CARIERA -->
    <section id="careers" class="careers">
        <h2>Alătură-te Echipei Noastre</h2>
        <p>Oferim cele mai bune condiții de muncă și salarii competitive în domeniul transporturilor. Dacă ești interesat să lucrezi cu noi, trimite CV-ul tău la <a href="mailto:contact@sebilogistik.com">contact@sebilogistik.com</a>.</p>
    </section>

    <!-- CONTACT -->
    <section id="contact" class="contact">
        <h2>Contactează-ne</h2>
        <p>Pentru informații suplimentare, completează formularul de mai jos sau contactează-ne direct.</p>
        <form action="#">
            <input type="text" name="name" placeholder="Nume" required>
            <input type="email" name="email" placeholder="Email" required>
            <textarea name="message" placeholder="Mesajul tău..." required></textarea>
            <button type="submit">Trimite</button>
        </form>
        <p>Adresa: Strada Exemplu, Nr. 123, Oraș, Țară</p>
        <p>Telefon: +40 123 456 789</p>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>&copy; 2025 Sebi Logistik AG | Toate drepturile rezervate.</p>
    </footer>
</body>
</html>
/* General */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

a {
    text-decoration: none;
    color: inherit;
}

/* Header */
header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 2rem;
}

header nav ul {
    list-style: none;
    display: flex;
}

header nav ul li {
    margin-left: 20px;
}

header nav ul li a {
    color: #fff;
    font-weight: bold;
}

/* Home Section */
.home {
    background: url('https://via.placeholder.com/1920x600') center/cover no-repeat;
    color: white;
    padding: 4rem;
    text-align: center;
}

.home h2 {
    font-size: 3rem;
}

.cta {
    background-color: #333;
    color: #fff;
    padding: 1rem 2rem;
    margin-top: 2rem;
    border-radius: 5px;
}

/* About Section */
.about, .services, .careers, .contact {
    padding: 3rem 2rem;
    text-align: center;
}

.about h2, .services h2, .careers h2, .contact h2 {
    margin-bottom: 2rem;
}

/* Services Section */
.services .service {
    margin: 1.5rem 0;
}

.service h3 {
    font-size: 1.8rem;
}

/* Contact Form */
form input, form textarea {
    width: 100%;
    padding: 1rem;
    margin-bottom: 1rem;
    border: 1px solid #ccc;
}

form button {
    padding: 1rem 2rem;
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
}

form button:hover {
    background-color: #555;
}

/* Footer */
footer {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
    margin-top: 2rem;
}
