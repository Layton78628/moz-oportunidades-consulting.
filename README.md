# moz-oportunidades-consulting.
moz-oportunidades-consulting.
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moçambique Oportunidades Consulting</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Moçambique Oportunidades Consulting</h1>
        <p>Consultoria para o Desenvolvimento Sustentável</p>
    </header>

    <nav>
        <ul>
            <li><a href="#sobre">Sobre</a></li>
            <li><a href="#sustentabilidade">Sustentabilidade</a></li>
            <li><a href="#servicos">Serviços</a></li>
            <li><a href="#contato">Contato</a></li>
        </ul>
    </nav>

    <section id="sobre">
        <h2>Sobre Nós</h2>
        <p>Somos uma consultoria focada no desenvolvimento sustentável em Moçambique, oferecendo suporte estratégico para educação, economia e meio ambiente.</p>
    </section>

    <section id="sustentabilidade">
        <h2>Compromisso com a Sustentabilidade</h2>
        <p>Promovemos soluções inovadoras para impulsionar o crescimento sustentável, fortalecendo comunidades e oportunidades de desenvolvimento.</p>
    </section>

    <section id="servicos">
        <h2>Nossos Serviços</h2>
        <div class="galeria">
            <img src="img/servico1.jpg" alt="Serviço 1">
            <img src="img/servico2.jpg" alt="Serviço 2">
            <img src="img/servico3.jpg" alt="Serviço 3">
        </div>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p><strong>Endereço:</strong> Avenida do Trabalho, Nampula</p>
        <p><strong>Telefone:</strong> 870755479</p>
        <p><strong>Email:</strong> jaimecassimo99@gmail.com</p>
    </section>

    <footer>
        <p>&copy; 2025 Moçambique Oportunidades Consulting - Criado por Layton</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
}

header {
    background: #007BFF;
    color: white;
    padding: 20px;
}

nav ul {
    list-style: none;
    padding: 0;
    background: #0056b3;
}

nav ul li {
    display: inline;
    margin: 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

section {
    padding: 20px;
}

.galeria {
    display: flex;
    justify-content: center;
    gap: 10px;
}

.galeria img {
    width: 200px;
    height: 150px;
    border-radius: 10px;
}

footer {
    background: #333;
    color: white;
    padding: 10px;
}document.addEventListener("DOMContentLoaded", function() {
    alert("Bem-vindo à Moçambique Oportunidades Consulting! Trabalhamos pelo desenvolvimento sustentável em Moçambique.");
});
