<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Portfólio</title>
    <link rel="stylesheet" href="style.css">
    <script defer src="https://cdn.emailjs.com/dist/email.min.js"></script>
    <script defer src="script.js"></script>
</head>
<body>
    <header>
        <h1 id="titulo">Meu Portfólio</h1>
        <nav>
            <a href="#portfolio">Portfólio</a>
            <a href="#contact">Contato</a>
            <a href="https://www.linkedin.com/in/marcelo-augusto-neto-a341a8218/" target="_blank">LinkedIn</a>
        </nav>
    </header>
    <div class="content">
        <section class="portfolio-section">
            <h2>Portfólio</h2>
            <div class="portfolio-item">
                <img src="images/captura.png" alt="Projeto 1">
                <p>Durante meu estágio na Fábrica de Tecnologias Turing da UniEvangelica, desenvolvi um projeto para a empresa CXM Corps como Product Owner. 
                   O desafio era criar um site de white label, uma solução flexível que permite à empresa personalizar e rebrandar a plataforma conforme necessário, sem necessidade de desenvolver uma nova estrutura do zero.
                   Como Product Owner, fui responsável por definir a visão do produto, priorizar o backlog e garantir que todas as funcionalidades atendessem aos requisitos do cliente. Trabalhei em estreita colaboração com a equipe de desenvolvimento, desde a concepção até a implementação, focando na criação de um design intuitivo e responsivo. Utilizamos tecnologias como Angular, Nodejs e frameworks modernos para garantir desempenho e escalabilidade.</p>
            </div>
            <div class="portfolio-item">
                <img src="images/captura.png" alt="Projeto 2">
                <p>Descrição do Projeto 2</p>
            </div>
        </section>
        <div class="content">
            <section id="contact" class="contact">
                <h2>Contato</h2>
                <form id="contactForm">
                    <input type="text" name="name" placeholder="Seu Nome" required>
                    <input type="email" name="email" placeholder="Seu Email" required>
                    <textarea name="message" placeholder="Sua Mensagem" rows="5" required></textarea>
                    <button type="submit">Enviar</button>
                </form>
            </section>   
        </div>
    </div>
    <footer>
        <p>&copy; 2024 Marcelo Augusto Neto. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
