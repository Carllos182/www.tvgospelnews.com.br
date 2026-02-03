# www.tvgospelnews.com.br
Tv Gospel News
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rádio Studio FM 99.1 - A Minha Rádio Gospel</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary-color: #004aad;
            --secondary-color: #ffcc00;
            --dark-bg: rgba(0, 0, 0, 0.85);
            --text-light: #ffffff;
            --card-bg: rgba(255, 255, 255, 0.1);
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }

        body {
            /* Imagem de estúdio de fundo */
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), 
                        url('https://images.unsplash.com/photo-1590602847861-f357a9332bbc?ixlib=rb-1.2.1&auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
            color: var(--text-light);
            line-height: 1.6;
        }

        /* Player Estilizado no Topo */
        .player-top {
            width: 100%;
            background: #000;
            padding: 10px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 15px rgba(0,0,0,0.5);
            text-align: center;
        }

        .player-container {
            max-width: 1200px;
            margin: 0 auto;
        }

        header {
            padding: 20px 0;
            text-align: center;
        }

        /* Menu de Navegação */
        nav {
            background: var(--primary-color);
            padding: 10px 0;
            position: sticky;
            top: 80px; /* Logo abaixo do player */
            z-index: 999;
        }

        nav ul {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            list-style: none;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            font-weight: 500;
            transition: 0.3s;
            font-size: 0.9rem;
        }

        nav ul li a:hover {
            color: var(--secondary-color);
        }

        /* Layout Principal */
        .container {
            max-width: 1200px;
            margin: 20px auto;
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 30px;
            padding: 0 20px;
        }

        main section {
            background: var(--dark-bg);
            padding: 25px;
            border-radius: 10px;
            margin-bottom: 25px;
            border-left: 5px solid var(--primary-color);
            backdrop-filter: blur(5px);
        }

        h2 {
            margin-bottom: 20px;
            color: var(--secondary-color);
            text-transform: uppercase;
            border-bottom: 1px solid #333;
            padding-bottom: 10px;
        }

        .destaque {
            color: var(--secondary-color);
            font-weight: bold;
            text-transform: uppercase;
        }

        /* Notícias e Itens */
        .noticia-item, .agenda-item, .testemunho-item {
            background: var(--card-bg);
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 15px;
        }

        /* Formulários */
        form {
            display: flex;
            flex-direction: column;
        }

        label { margin: 10px 0 5px; }

        input, textarea, select {
            padding: 10px;
            border-radius: 5px;
            border: none;
            background: #eee;
            margin-bottom: 10px;
        }

        button {
            padding: 12px;
            background: var(--secondary-color);
            border: none;
            border-radius: 5px;
            font-weight: bold;
            cursor: pointer;
            transition: 0.3s;
        }

        button:hover {
            background: #e6b800;
        }

        /* Sidebar */
        aside {
            background: var(--dark-bg);
            padding: 20px;
            border-radius: 10px;
            height: fit-content;
        }

        aside h3 {
            color: var(--secondary-color);
            margin: 20px 0 10px;
        }

        #hora-atual {
            font-size: 2rem;
            font-weight: bold;
            color: var(--secondary-color);
        }

        /* Footer */
        footer {
            background: #000;
            text-align: center;
            padding: 40px 20px;
            margin-top: 50px;
        }

        /* Responsividade */
        @media (max-width: 768px) {
            .container {
                grid-template-columns: 1fr;
            }
            nav ul li {
                width: 50%;
                text-align: center;
            }
        }
    </style>
</head>
<body>

<!-- Player Fixo no Topo -->
<div class="player-top">
    <div class="player-container">
        <iframe src="https://player.stmsrv.com/player-simples/8314/1" width="100%" height="60" frameborder="0" scrolling="no"></iframe>
    </div>
</div>

<header>
    <h1>RÁDIO STUDIO FM 99.1</h1>
    <p>A Minha Rádio Gospel</p>
</header>

<nav>
    <ul>
        <li><a href="#inicial">Inicial</a></li>
        <li><a href="#quem-somos">Quem Somos</a></li>
        <li><a href="#pedido-oracao">Pedido de Oração</a></li>
        <li><a href="#agenda">Agenda</a></li>
        <li><a href="#testemunhos">Testemunhos</a></li>
        <li><a href="#fotos">Fotos</a></li>
        <li><a href="#locutores">Locutores</a></li>
        <li><a href="#noticias">Notícias</a></li>
        <li><a href="#programacao">Programação</a></li>
        <li><a href="#videos">Vídeos</a></li>
    </ul>
</nav>

<div class="container">
    <main>
        <section id="inicial">
            <h2>Destaques</h2>
            <div class="noticia-item">
                <p class="destaque">PREGUE A PALAVRA</p>
                <p><strong>Brasil</strong> - Cantores Gospel atingem 100 milhões de visualizações no YouTube</p>
            </div>
            <div class="noticia-item">
                <p><strong>Brasil</strong> - Carllos Passim lança nova música "O Cenário Entrar"</p>
            </div>
            <div class="noticia-item">
                <p><strong>Brasil</strong> - Carllos Passim lança single "Meus Sonhos"</p>
            </div>
        </section>

        <section id="quem-somos">
            <h2>Quem Somos</h2>
            <p>A Rádio Studio FM 99.1 - A Minha Rádio Gospel é uma emissora do Grupo Gospel News, é dedicada a levar a Palavra de Deus e música gospel de qualidade para nossos ouvintes. Nosso objetivo é evangelizar, inspirar e fortalecer a fé de todos que nos ouvem. Baseado no livro de Marcos 16:15 que nos ordena fazer o IDE do Senhor Jesus.</p>
        </section>

        <section id="pedido-oracao">
            <h2>Pedido de Oração</h2>
            <p>Envie seu pedido de oração que nossa equipe e comunidade irá interceder por você!</p>
            <form action="#">
                <input type="text" id="nome-oracao" placeholder="Seu nome" required>
                <input type="text" id="cidade-oracao" placeholder="Sua cidade">
                <textarea id="mensagem-oracao" rows="4" placeholder="Descreva seu pedido de oração" required></textarea>
                <button type="submit">Enviar Pedido</button>
            </form>
        </section>

        <section id="agenda">
            <h2>Agenda de Eventos</h2>
            <div class="agenda-item">
                <p class="destaque">2026</p>
                <p><strong>Cultos:</strong> Terças, Quartas e Quintas</p>
                <p>Com Pr. Carllos, Miss May Carvalho, Miss Maria Zilda e Pr. Romildo</p>
            </div>
            <div class="agenda-item">
                <p class="destaque">2026</p>
                <p><strong>Sábados:</strong> Louvor e Adoração</p>
                <p>Com Pr. Carllos Passim e Equipe</p>
            </div>
            <div class="agenda-item">
                <p class="destaque">2026</p>
                <p><strong>Domingos (18:30h):</strong> Palavras de Vida</p>
                <p>Pr. Carllos Passim / Ministério de Louvor</p>
            </div>
        </section>

        <section id="testemunhos">
            <h2>Testemunhos</h2>
            <div class="testemunho-item">
                <p class="destaque">Paula Soares</p>
                <p>"Meu casamento estava destruído. Depois da novena, Deus restaurou tudo entre eu e meu marido. Obrigada!"</p>
            </div>
            <div class="testemunho-item">
                <p class="destaque">Cleusa Damasceno</p>
                <p>"Meu filho estava envolvido com coisas ruins. Depois da oração, ele se converteu. Deus é fiel!"</p>
            </div>
            <p><strong>Envie seu testemunho:</strong></p>
            <form action="#">
                <input type="text" placeholder="Seu nome">
                <textarea rows="3" placeholder="Conte sua história"></textarea>
                <button type="submit">Enviar Testemunho</button>
            </form>
        </section>

        <section id="fotos">
            <h2>Fotos</h2>
            <!-- Imagem de exemplo do seu código -->
            <img src="https://images.unsplash.com/photo-1516280440614-37939bbacd81?auto=format&fit=crop&w=800&q=80" alt="Estúdio" style="width:100%; border-radius:5px; margin-bottom: 20px;">
            <p>Confira algumas fotos dos nossos eventos e da equipe da rádio.</p>
        </section>

        <section id="locutores">
            <h2>Locutores</h2>
            <div class="noticia-item">
                <ul>
                    <li>May Carvalho</li>
                    <li>Mayos</li>
                    <li>Carllos Passim - "Programação Demonstrativa"</li>
                </ul>
            </div>
        </section>

        <section id="noticias">
            <h2>Notícias</h2>
            <div class="noticia-item">
                <p><strong>IA e o Relógio do Juízo Final:</strong> Analistas discutem impactos nas previsões bíblicas.</p>
            </div>
            <div class="noticia-item">
                <p><strong>Família:</strong> Psicóloga orienta como fortalecer laços à luz da Bíblia.</p>
            </div>
        </section>

        <section id="programacao">
            <h2>Programação</h2>
            <p class="destaque">Grade Horária</p>
            <ul style="list-style: none; margin-bottom: 20px;">
                <li>00:00h - Auto DJ</li>
                <li>07:00h - Desperta Brasil</li>
                <li>09:00h - Manhã Feliz</li>
                <li>12:00h - Jornal Gospel News</li>
                <li>21:00h - Good Night</li>
            </ul>
            
            <p class="destaque">Top Músicas</p>
            <ol style="margin-left: 20px;">
                <li>Carllos Passim - O Cenário</li>
                <li>Jairo Bonfim - Deus Proverá</li>
                <li>Eyshila - Me Leva</li>
            </ol>
        </section>

        <section id="videos">
            <h2>Vídeos</h2>
            <div class="noticia-item">
                <p><a href="#" style="color: white;">Aline Barros - Ressuscita-me</a></p>
                <p><a href="#" style="color: white;">Davi Sacer - Deus de Promessas</a></p>
            </div>
        </section>
    </main>

    <aside>
        <h3>Informações</h3>
        <p class="destaque">Hora Atual</p>
        <p id="hora-atual">00:00:00</p>
        <p>03/02/2026</p>

        <h3>Contato</h3>
        <p>📱 WhatsApp: (11) 95963-3512</p>
        <p>📧 tvgospelnews99.1@gmail.com</p>

        <h3>Enquete</h3>
        <p>Qual rede social você acessa mais?</p>
        <form>
            <label><input type="radio" name="social"> Facebook</label>
            <label><input type="radio" name="social"> Instagram</label>
            <label><input type="radio" name="social"> YouTube</label>
            <button type="submit">Votar</button>
        </form>

        <h3>Ouvinte do Mês</h3>
        <p class="destaque">Adria - Curitiba</p>
    </aside>
</div>

<footer>
    <p><strong>Rádio Studio FM 99.1</strong> - A Minha Rádio Gospel</p>
    <p>Todos os direitos reservados © 2026</p>
</footer>

<script>
    // Atualiza a hora em tempo real
    function atualizarHora() {
        const data = new Date();
        const horas = String(data.getHours()).padStart(2, '0');
        const minutos = String(data.getMinutes()).padStart(2, '0');
        const segundos = String(data.getSeconds()).padStart(2, '0');
        document.getElementById('hora-atual').textContent = `${horas}:${minutos}:${segundos}`;
    }
    setInterval(atualizarHora, 1000);
    atualizarHora();

    // Scroll Suave
    document.querySelectorAll('nav a').forEach(anchor => {
        anchor.addEventListener('click', function(e) {
            e.preventDefault();
            const section = document.querySelector(this.getAttribute('href'));
            window.scrollTo({
                top: section.offsetTop - 150,
                behavior: 'smooth'
            });
        });
    });
</script>

</body>
</html>
