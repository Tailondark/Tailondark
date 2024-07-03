!DOCTYPE html><html lang="en"><head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MENOR 7 MINES 💎</title>
    <link rel="stylesheet" href="css/main.css">
    <link rel="shortcut icon" href="images/fav-icon.png" type="image/x-icon">
    <link href="css/boxicons.min.css" rel="stylesheet">

    <style>
        #avisodep {
            width: 300px;
            display: block;
            margin-right: auto;
            margin-left: auto;
        }
        
        .headline {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px;
            background-color: #000000;
            color: #ffffff;
            position: relative;
            z-index: 2;
            /* Garante que a headline esteja na frente */
        }
        
        .headline h1 {
            margin: 0;
            font-size: 24px;
            /* Tamanho da fonte ajustado */
        }
        
        .menu-icon {
            color: #007bff;
            /* Cor azul */
            font-size: 35px;
            margin-right: 10px;
        }
        
        .menu {
            position: fixed;
            top: 60px;
            /* Posição abaixo da headline */
            left: -250px;
            /* Esconder o menu à esquerda */
            width: 250px;
            height: 100%;
            background-color: #000000;
            transition: left 0.3s ease;
            z-index: 1;
            /* Garante que o menu esteja atrás de todo o conteúdo */
        }
        
        .menu ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        
        .menu ul li {
            padding: 10px;
            border-bottom: 1px solid #444;
        }
        
        .menu ul li a {
            color: #fff;
            text-decoration: none;
            display: flex;
            align-items: center;
        }
        
        .menu ul li a img {
            margin-right: 10px;
            width: 25px;
            /* Definindo a largura das logos */
            height: auto;
            /* Mantendo a proporção */
        }
        
        .menu ul li:last-child {
            border-bottom: none;
            /* Remover borda inferior da última entrada */
        }
        
        .menu ul li:last-child a {
            margin-top: auto;
            /* Alinhar a última entrada ao final */
        }
        
        .menu ul li:last-child a img {
            margin-right: 10px;
            width: 20px;
            /* Reduzir o tamanho do ícone */
            height: auto;
        }
        /* Remover fundo branco do botão do menu */
        
        #menu-toggle {
            background-color: transparent;
            border: none;
            cursor: pointer;
        }
        /* Estilo para a seção de perfil do usuário */
        
        .profile-section {
            background: linear-gradient(to bottom, #004d99, #007bff);
            /* Degradê de azul escuro para azul claro */
            padding: 20px;
            border-bottom: 1px solid #444;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        
        .profile-section img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        
        .profile-section .user-id {
            color: #fff;
            font-size: 18px;
        }
    </style>
</head>

<body>
    <!-- Headline with Menu Button -->
    <div class="headline">
        <h1>MENOR 7 MINES 💎</h1>
        <button id="menu-toggle" onclick="toggleMenu()">
            <i class="bx bx-menu menu-icon"></i> <!-- Ícone do Boxicons -->
        </button>
    </div>

    <!-- Hidden Menu -->
    <div class="menu" id="menu">
        <ul>
            <!-- Seção de perfil do usuário -->
            <li class="profile-section">
                <img src="images/HACKERPROFILE.JPG" alt="Profile Picture">
                <span class="user-id">ID: 777</span>
            </li>
            <li>
                <a href="https://www.instagram.com/021tailon/">
                    <img src="images/instagram_logo.png" alt="Instagram"> INSTAGRAM
                </a>
            </li>
            <li>
                
                
            </li>
            <li>
               
                
            </li>
        </ul>
    </div>

    <!-- Play Movie Container starts -->
    <div class="play-container container">
        <img src="" style="display: block; margin-left: auto; margin-right: auto; width: 1px;">
        <h3 id="mines" style="text-align: center;">💣 Minas: 3 </h3>
        <h3 style="text-align: center;">💥 Tentativas: 1</h3>
        <h3 style="text-align: center;">🎯 Porcentagem de ganho: 100%</h3>

        <br>
        <img id="avisodep" src="">
        <div id="quadrados">
            <div id="fileira-1"></div>
            <div id="fileira-2"></div>
            <div id="fileira-3"></div>
            <div id="fileira-4"></div>
            <div id="fileira-5"></div>
        </div><br>
        <div class="container">
            <button id="botao-sinal" onclick="gerarSinal()">HACKEAR MINES</button>

            <br>
        </div>

        <div class="container">
            <button id="botao-iframe" onclick="toggleIframe()">Fechar casa de aposta</button>
            <br><br>
        </div>

        <script src="js/app.js"></script>
        <iframe id="meu-iframe" src="https://ganho.win/yur9yi9rf" height="1900px" width="1000px"></iframe>

        <br><br>

        <div class="container">

        </div>
    </div>
    <!-- Play Movie Container ends -->

    <!-- Copyright starts -->
    <div class="copyright">
        <p>© Todos os Direitos Reservados!</p>
    </div>
    <!-- Copyright ends -->

    <script>
        function toggleMenu() {
            var menu = document.getElementById("menu");
            if (menu.style.left === "0px") {
                menu.style.left = "-250px";
            } else {
                menu.style.left = "0px";
            }
        }
    </script>

    <script src="js/swiper-bundle.min.js"></script>
    <script src="js/main.js"></script>


</body></html>
