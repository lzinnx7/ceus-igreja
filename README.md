<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comunidade Evangélica União dos Santos - CEUS</title>
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@400;500&family=Sacramento&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Cabeçalho -->
    <header>
        <div class="logo">
            <img src="logo.png" alt="Logo CEUS"> <!-- Substitua logo.png pelo caminho do seu logo -->
        </div>
        <nav>
            <ul>
                <li><a href="#home">Início</a></li>
                <li><a href="#about">Sobre</a></li>
                <li><a href="#events">Eventos</a></li>
                <li><a href="#ministries">Ministérios</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <!-- Página Inicial -->
    <section id="home">
        <h1>Bem-vindo à Comunidade Evangélica União dos Santos - CEUS</h1>
        <p>Uma igreja acolhedora, onde a palavra de Deus transforma vidas e nos guia para a união em Cristo.</p>
        <p><em>"Onde dois ou três estiverem reunidos em meu nome, ali estou no meio deles." - Mateus 18:20</em></p>
        <a href="#events" class="cta-btn">Confira nossos próximos eventos</a>
    </section>

    <!-- Seção Sobre -->
    <section id="about">
        <h2>Sobre a CEUS</h2>
        <p>A **CEUS** é uma igreja evangélica comprometida em viver o evangelho com fervor e acolhimento. Com a presença de Deus entre nós, temos a missão de levar a palavra ao próximo, acolher a todos com amor e criar uma comunidade unida na fé.</p>
        <p>Seja parte dessa jornada de transformação!</p>
    </section>

    <!-- Seção de Eventos -->
    <section id="events">
        <h2>Próximos Eventos</h2>
        <ul>
            <li><strong>Culto de Adoração</strong> - Todos os domingos, 10h</li>
            <li><strong>Estudo Bíblico</strong> - Terças-feiras, 19h</li>
            <li><strong>Evangelismo na Comunidade</strong> - Sábados, 9h</li>
        </ul>
    </section>

    <!-- Seção de Ministérios -->
    <section id="ministries">
        <h2>Ministérios da CEUS</h2>
        <p>Na CEUS, acreditamos na importância de servir à comunidade e ao Reino de Deus. Confira os nossos ministérios:</p>
        <ul>
            <li><strong>Ministério de Mídia</strong> - Responsável por criar conteúdo e transmitir as mensagens da igreja.</li>
            <li><strong>Ministério de Louvor</strong> - Nossa equipe de louvor conduz os cultos com música e adoração.</li>
            <li><strong>Ministério de Recepção</strong> - Recebe com carinho todos os visitantes e membros da igreja.</li>
            <li><strong>Ministério Infantil</strong> - Ensina as crianças sobre o amor de Deus de forma divertida e segura.</li>
        </ul>
    </section>

    <!-- Seção de Contato -->
    <section id="contact">
        <h2>Contato</h2>
        <form action="#">
            <label for="name">Nome:</label>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">E-mail:</label>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Mensagem:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br><br>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Comunidade Evangélica União dos Santos - CEUS. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
/* Resetando alguns estilos padrões */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Quicksand', sans-serif;
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.6;
}

header {
    background-color: #900; /* Vermelho para fogo e fervor espiritual */
    color: white;
    padding: 20px 0;
    text-align: center;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2);
}

header .logo img {
    max-width: 100px;
    margin-bottom: 10px;
}

header nav ul {
    list-style: none;
    padding-top: 10px;
}

header nav ul li {
    display: inline;
    margin: 0 20px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
    font-family: 'Sacramento', cursive;
}

section {
    padding: 50px 20px;
    text-align: center;
    background: linear-gradient(135deg, #f3f3f3 50%, #fce1c8);
}

section h2 {
    color: #900;
    font-family: 'Sacramento', cursive;
    font-size: 2em;
}

.cta-btn {
    background-color: #ff6a13;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    display: inline-block;
    margin-top: 20px;
    font-weight: bold;
}

ul {
    list-style: none;
    text-align: left;
    margin-top: 20px;
}

ul li {
    font-size: 1.2em;
    margin-bottom: 10px;
}

footer {
    background-color: #900;
    color: white;
    padding: 10px 0;
    text-align: center;
}

form {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
    margin: 0 auto;
    width: 80%;
    max-width: 600px;
}

form input, form textarea, form button {
    margin-bottom: 15px;
    padding: 10px;
    width: 100%;
    border: 1px solid #ccc;
    border-radius: 5px;
}

form button {
    background-color: #900;
    color: white;
    font-weight: bold;
    cursor: pointer;
}

form button:hover {
    background-color: #bb0000;
}

footer p {
    font-size: 0.8em;
}
