<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Caio - Designer & Desenvolvedor</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #1a2a6c, #b21f1f, #fdbb2d);
            color: #333;
            padding: 20px;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .container {
            max-width: 1000px;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            overflow: hidden;
        }
        
        .profile-card {
            display: flex;
            padding: 30px;
        }
        
        .profile-image {
            flex: 1;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .profile-image img {
            width: 100%;
            max-width: 300px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        
        .profile-image img:hover {
            transform: scale(1.03);
        }
        
        .profile-info {
            flex: 2;
            padding: 20px;
        }
        
        h1 {
            color: #2c3e50;
            margin-bottom: 10px;
            font-size: 2.2rem;
        }
        
        h3 {
            color: #e74c3c;
            margin: 20px 0 10px;
            font-size: 1.4rem;
            border-bottom: 2px solid #f0f0f0;
            padding-bottom: 5px;
        }
        
        p {
            line-height: 1.6;
            margin-bottom: 15px;
        }
        
        ul {
            list-style-type: none;
            margin: 15px 0;
        }
        
        li {
            margin-bottom: 8px;
            padding-left: 20px;
            position: relative;
        }
        
        li:before {
            content: "•";
            color: #e74c3c;
            font-weight: bold;
            position: absolute;
            left: 0;
        }
        
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 20px 0;
        }
        
        .badge {
            display: inline-block;
            padding: 8px 15px;
            border-radius: 5px;
            font-weight: bold;
            color: white;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.2);
        }
        
        .badge-design {
            background: #9b59b6;
        }
        
        .badge-dev {
            background: #3498db;
        }
        
        .badge-art {
            background: #e74c3c;
        }
        
        .contact-links {
            display: flex;
            flex-direction: column;
            gap: 10px;
            margin-top: 25px;
        }
        
        .contact-link {
            display: flex;
            align-items: center;
            padding: 12px 15px;
            background: #f8f9fa;
            border-radius: 8px;
            text-decoration: none;
            color: #333;
            transition: all 0.3s ease;
            border: 1px solid #e0e0e0;
        }
        
        .contact-link:hover {
            background: #2c3e50;
            color: white;
            transform: translateY(-2px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .contact-link img {
            width: 24px;
            height: 24px;
            margin-right: 10px;
        }
        
        @media (max-width: 768px) {
            .profile-card {
                flex-direction: column;
            }
            
            .profile-image, .profile-info {
                width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-card">
            <div class="profile-image">
                <img src="https://media.tenor.com/Z8WqNvjVbOYAAAAM/guilty-gear-strive-slayer.gif" alt="Caio - Designer e Desenvolvedor">
            </div>
            <div class="profile-info">
                <h1>👋 Olá, sou o Caio</h1>
                
                <div class="badges">
                    <span class="badge badge-design">🎨 Designer</span>
                    <span class="badge badge-art">🧠 Ilustrador</span>
                    <span class="badge badge-dev">💻 Desenvolvedor</span>
                </div>
                
                <p>Sou um criador que combina lógica e criatividade para transformar ideias em experiências visuais e interativas. Tenho experiência com C e Python, sempre buscando criar código limpo e escalável. No design, trabalho com identidades visuais, interfaces, arte conceitual e personagens, usando ferramentas como Photoshop, Illustrator e Procreate.</p>
                
                <h3>🌟 Minhas preferências</h3>
                <ul>
                    <li>Projetos que unem arte e tecnologia</li>
                    <li>Trabalhar com equipes criativas</li>
                    <li>Café ☕, bons livros 📚 e músicas empolgantes 🎧</li>
                </ul>
                
                <p>Sempre em busca de aprender e compartilhar conhecimento.</p>
                
                <h3>📫 Contato</h3>
                <div class="contact-links">
                    <a href="https://www.linkedin.com/in/caio-siqueira-amaral-78538b364/" class="contact-link">
                        <img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" alt="LinkedIn">
                        LinkedIn
                    </a>
                    <a href="https://github.com/HcL-Caio" class="contact-link">
                        <img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" alt="GitHub">
                        GitHub
                    </a>
                    <a href="mailto:caiosiqueiraamaral@gmail.com" class="contact-link">
                        <img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Email">
                        caiosiqueiraamaral@gmail.com
                    </a>
                    <a href="mailto:caiopcmx@gmail.com" class="contact-link">
                        <img src="https://cdn-icons-png.flaticon.com/512/281/281769.png" alt="Email">
                        caiopcmx@gmail.com
                    </a>
                    <a href="https://wa.me/5561983594678" class="contact-link">
                        <img src="https://cdn-icons-png.flaticon.com/512/124/124034.png" alt="WhatsApp">
                        WhatsApp: (61) 98359-4678
                    </a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
