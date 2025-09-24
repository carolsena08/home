<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seteeduca - Dashboard</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Estilos Gerais */
        :root {
            --orange: #F88C12;
            --blue: #00A6FF;
            --green: #59C631;
            --background: #FCFAFF; 
            --text-primary: #333;
            --text-secondary: #6c757d;
            --sidebar-bg: #FFF4DF;
            --sidebar-width: 280px; 
        }

        /* SEU CÓDIGO CSS DA SIDEBAR (INTEGRADO E AJUSTADO PARA O LAYOUT GLOBAL) */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: var(--background); 
            min-height: 100vh;
            display: flex; 
        }

        .sidebar {
            width: var(--sidebar-width); 
            background: linear-gradient(180deg, #FFF4DF 0%, #f8f0e3 100%);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            box-shadow: 2px 0 15px rgba(0, 0, 0, 0.1);
            min-height: 100vh;
            flex-shrink: 0; 
            position: fixed; 
            left: 0;
            top: 0;
            z-index: 1000;
        }

        .logo {
            padding: 0px 40px;
            text-align: center;
            margin-bottom: 25px;
            margin-top: 30px;
        }
        .logo img {
            max-width: 150px; 
        }

        .menu {
            flex: 1; 
            padding: 20px 18px;
            overflow-y: auto; 
        }

        .menu-item {
            padding: 30px 20px;
            margin-bottom: 6px;
            border-radius: 6px;
            cursor: pointer;
            transition: all 0.3s ease;
            position: relative;
            display: flex;
            align-items: center;
            font-weight: 500;
            overflow: visible;
            color: black;
            text-decoration: none; 
        }

        .menu-item i {
            margin-right: 15px;
            font-size: 18px;
            width: 24px;
            text-align: center;
            z-index: 2;
        }

        .menu-item span {
            z-index: 2;
            font-size: 15px;
        }

        .menu-item:hover {
            background-color: #6c757d21;
        }

        .menu-item::after {
            padding: 0 10px;
            content: '';
            position: absolute;
            bottom: -3px;
            left: 20px;
            height: 2px;
            width: 0px;
            transition: width 0.3s ease;
            border-radius: 1px;
        }

        .menu-item:hover::after,
        .menu-item.active::after {
            width: calc(100% - 40px);
        }

        /* Cores das barrinhas inferiores dos itens do menu */
        .menu-item:nth-child(1)::after { background-color: #F4BF27; } 
        .menu-item:nth-child(2)::after { background-color: #00A6FF; } 
        .menu-item:nth-child(3)::after { background-color: #9747FF; } 
        .menu-item:nth-child(4)::after { background-color: #F88C12; } 
        .menu-item:nth-child(5)::after { background-color: #D22A2A; } 
        .menu-item:nth-child(6)::after { background-color: #59C631; } 

        .menu-item.active {
            background-color: rgba(128, 128, 128, 0.356);
            color: #333;
            font-weight: 600;
        }

        .menu-item.active::before {
            content: '';
            position: absolute;
            right: 15px;
            top: 50%;
            transform: translateY(-50%);
            width: 8px;
            height: 8px;
            border-radius: 50%;
            background-color: currentColor; 
            z-index: 2;
        }

        .sidebar-footer {
            padding: 20px 18px;
            border-top: 1px solid rgba(0, 0, 0, 0.1);
        }
        
        .logout-button {
            padding: 16px 20px;
            border-radius: 8px;
            cursor: pointer;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            font-weight: 500;
            color: #333;
            width: 100%;
            text-decoration: none;
        }

        .logout-button i {
            margin-right: 15px;
            font-size: 18px;
            width: 24px;
            text-align: center;
        }

        .logout-button:hover {
            background-color: rgba(210, 42, 42, 0.1); 
            color: #D22A2A; 
            font-weight: 600;
        }

        /* CONTEÚDO PRINCIPAL */
        .main-content {
            margin-left: var(--sidebar-width); 
            padding: 30px 25px; 
            width: calc(100% - var(--sidebar-width));
            flex-grow: 1; 
        }

        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 40px;
        }

        .header-title h1 {
            color: var(--text-primary);
            font-size: 28px;
            font-weight: 600;
        }

        .header-title p {
            color: var(--text-secondary);
            font-size: 16px;
        }
        
        /* Perfil do Usuário e Dropdown */
        .profile {
            position: relative;
            cursor: pointer;
            z-index: 10; 
        }
        
        .profile-header {
            display: flex;
            align-items: center;
            padding: 5px;
            border-radius: 50px;
            transition: background-color 0.2s ease;
        }
        
        .profile-header:hover {
            background-color: #f0f0f0;
        }
        
        .profile-icon {
            font-size: 38px;
            color: #333;
        }
        
        .profile-arrow {
            font-size: 14px;
            margin-left: 8px;
            color: #555;
            transition: transform 0.3s ease;
        }

        .profile-dropdown {
            display: none;
            position: absolute;
            top: 110%; 
            right: 0;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
            width: 200px;
            z-index: 1001;
            overflow: hidden;
            padding: 8px 0;
            border: 1px solid #eee;
        }

        .profile-dropdown.show {
            display: block;
        }

        .profile-dropdown a {
            display: flex;
            align-items: center;
            padding: 12px 18px;
            text-decoration: none;
            color: #444;
            font-size: 15px;
            transition: background-color 0.2s ease;
        }

        .profile-dropdown a:hover {
            background-color: #f5f5f5;
        }

        .profile-dropdown a i {
            width: 20px;
            margin-right: 15px;
            color: #666;
            text-align: center;
        }
        
        .dropdown-divider {
            height: 1px;
            background-color: #eee;
            margin: 8px 0;
        }

        /* Banner Principal */
        .welcome-banner {
            background-color: var(--sidebar-bg);
            border-radius: 20px;
            padding: 90px;
            position: relative; 
            overflow: hidden; 
            margin-bottom: 40px;
        }

        .banner-text {
            width: 65%;
            min-width: 350px;
            padding-right: 20px;
            position: relative; 
            z-index: 2; 
        }

        .banner-text h2 {
            font-size: 32px;
            font-weight: 600;
            color: var(--text-primary);
            margin-bottom: 15px;
            margin-top: -30px;

        }
        
        .banner-features {
            list-style: none;
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 10px 20px;
        }
        
        .banner-features li {
            display: flex;
            align-items: center;
            color: var(--text-secondary);
            font-size: 15px;
        }
        
        .banner-features li::before {
            content: '';
            display: inline-block;
            width: 10px;
            height: 10px;
            border-radius: 50%;
            margin-right: 10px;
        }
        
        .banner-features li:nth-child(1)::before { background-color: #4285F4; } 
        .banner-features li:nth-child(2)::before { background-color: #FBBC05; }  
        .banner-features li:nth-child(3)::before { background-color: #EA4335; } 
        .banner-features li:nth-child(4)::before { background-color: #34A853; } 
        
        .sete {
            position: absolute; 
            right: 40px; 
            top: 50%; 
            transform: translateY(-50%); 
            z-index: 1; 
        }

        .sete img {
            max-width: 300px;
            height: 300px;
            display: block;
            margin-top: -430px;
        }

        /* Cards de Informações Rápidas */
        .quick-info-title {
            font-size: 22px;
            font-weight: 600;
            color: var(--text-primary);
            margin-bottom: 20px;
            margin-top: 80px;
        }
        
        .info-cards-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }

        .info-card {
            background-color: #fff;
            padding: 20px;
            border-radius: 15px;
            border-bottom: 5px solid;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            height: 270px;
        }
        
        .info-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.08);
        }

        .card-header {
            display: flex;
            justify-content: space-between;
            align-items: flex-start;
            margin-bottom: 30px;
        }

        .card-header .icon {
            font-size: 24px;
            padding: 12px;
            border-radius: 10px;
        }
        
        .card-number {
            font-size: 42px;
            font-weight: 700;
        }

        .card-label {
            font-size: 16px;
            color: var(--text-secondary);
        }
        
        .card-professores { border-color: var(--orange); }
        .card-professores .icon { background-color: #fdecd9; color: var(--orange); }
        .card-professores .card-number { color: var(--orange); }
        
        .card-alunos { border-color: var(--blue); }
        .card-alunos .icon { background-color: #e0f3ff; color: var(--blue); }
        .card-alunos .card-number { color: var(--blue); }

        .card-turmas { border-color: var(--green); }
        .card-turmas .icon { background-color: #e6f6e1; color: var(--green); }
        .card-turmas .card-number { color: var(--green); }
        
        .page-footer {
            margin-top: 53px;
            padding-top: 25px;
            border-top: 1px solid #e0e0e0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 15px;
            color: var(--text-secondary);
            font-size: 14px;
        }

        .footer-links a {
            color: var(--text-secondary);
            text-decoration: none;
            margin-left: 20px;
            transition: color 0.2s ease;
        }

        .footer-links a:hover {
            color: var(--text-primary);
            text-decoration: underline;
        }

        /* --- NOVOS ESTILOS PARA O MODAL DE CONFIRMAÇÃO --- */
        .modal-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            display: none; /* Escondido por padrão */
            align-items: center;
            justify-content: center;
            z-index: 2000;
            opacity: 0;
            transition: opacity 0.3s ease, display 0.3s ease;
        }
        .modal-container.active {
            display: flex;
            opacity: 1;
        }
        .modal-content {
            background-color: var(--sidebar-bg);
            padding: 40px;
            border-radius: 16px;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.2);
            text-align: center;
            max-width: 400px;
            width: 90%;
            transform: scale(0.9);
            transition: transform 0.3s ease;
        }
        .modal-container.active .modal-content {
            transform: scale(1);
        }
        .modal-content p {
            font-size: 20px;
            font-weight: 600;
            margin-bottom: 30px;
            color: var(--text-primary);
        }
        .modal-buttons {
            display: flex;
            justify-content: center;
            gap: 20px;
        }
        .modal-buttons button {
            padding: 12px 30px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: bold;
            color: white;
            cursor: pointer;
            transition: transform 0.2s ease;
        }
        .modal-buttons button:hover {
            transform: scale(1.05);
        }
        .btn-cancel {
            background-color: #D22A2A; /* Vermelho */
        }
        .btn-confirm {
            background-color: var(--green); /* Verde */
        }
        /* --- FIM DOS ESTILOS DO MODAL --- */


        /* Media Queries para Responsividade */
        @media (max-width: 1024px) {
            .welcome-banner { padding-bottom: 120px; text-align: center; display: block; }
            .banner-text { width: 100%; margin-right: 0; padding-right: 0; margin-bottom: 20px; }
            .sete { position: absolute; bottom: 20px; right: 50%; transform: translateX(50%); top: auto; }
            .banner-features { grid-template-columns: 1fr; display: inline-block; text-align: left; }
        }
        
        @media (max-width: 768px) {
            :root { --sidebar-width: 70px; }
            .menu-item span, .logout-button span, .seteeduca { display: none; }
            .menu-item i, .logout-button i { margin-right: 0; }
            .sidebar .logo { padding: 0 10px; } 
            .sidebar .logo img { max-width: 50px; } 
            .sidebar-footer { padding: 10px 5px; } 
            .menu { padding: 10px 5px; } 
            .menu-item { padding: 15px 5px; justify-content: center; } 
            .menu-item::after { display: none; } 
            .menu-item.active::before { right: 5px; } 
            .main-content { margin-left: var(--sidebar-width); width: calc(100% - var(--sidebar-width)); }
            .header-title h1 { font-size: 22px; }
            .header-title p { font-size: 14px; }
            .welcome-banner { padding: 20px; padding-bottom: 100px; }
            .banner-text h2 { font-size: 24px; }
            .sete img { max-width: 120px; }
            .page-footer { flex-direction: column; justify-content: center; text-align: center; }
            .footer-links a { margin: 0 10px; }
        }
    </style>
</head>
<body>
    
    <div class="sidebar">
        <div>
            <div class="logo">
                <img src="imagem/logo.png.png" alt="logo">
            </div>
            <div class="menu">
                <a href="#" class="menu-item active" onclick="navegarPara('inicio')">
                    <i class="fas fa-home"></i>
                    <span>INÍCIO</span>
                </a>
                <a href="#" class="menu-item" onclick="navegarPara('cadastro')">
                    <i class="fas fa-address-card"></i>
                    <span>CADASTRO</span>
                </a>
                <a href="#" class="menu-item" onclick="navegarPara('matricula')">
                    <i class="fas fa-user-graduate"></i>
                    <span>MATRÍCULA</span>
                </a>
                <a href="#" class="menu-item" id="professor-link">
                    <i class="fas fa-chalkboard-teacher"></i>
                    <span>PROFESSOR</span>
                </a>
    
                <a href="#" class="menu-item" onclick="navegarPara('turmas')"> 
                    <i class="fas fa-users"></i>
                    <span>TURMA</span>
                </a>
                <a href="#" class="menu-item" onclick="navegarPara('financeiro')">
                    <i class="fas fa-dollar-sign"></i>
                    <span>FINANCEIRO</span>
                </a>
            </div>
        </div>
        <div>
            <div class="sidebar-footer">
                <a href="#" class="logout-button logout-trigger">
                    <i class="fa-solid fa-right-from-bracket"></i>
                    <span>Sair</span>
                </a>
            </div>
        </div>
    </div>  

    <main class="main-content">
        <header class="header">
            <div class="header-title">
                <h1>Olá, Usuário!</h1>
                <p>Como podemos te ajudar?</p>
            </div>
            <div class="profile" id="profile-toggle">
                <div class="profile-header">
                    <i class="fas fa-user-circle profile-icon"></i>
                    <i class="fas fa-chevron-down profile-arrow"></i>
                </div>
                <div class="profile-dropdown" id="profile-dropdown-menu">
                    <a href="#" onclick="navegarPara('meu-perfil')"><i class="fas fa-user"></i> Meu perfil</a>
                    <a href="#" onclick="navegarPara('mensalidade')"><i class="fas fa-file-invoice-dollar"></i> Mensalidade</a>
                    <a href="#" onclick="navegarPara('arquivados')"><i class="fas fa-archive"></i> Arquivados</a>
                    <div class="dropdown-divider"></div>
                    <a href="#" onclick="navegarPara('ajuda')"><i class="fas fa-question-circle"></i> Ajuda</a>
                    <a href="#" class="logout-trigger"><i class="fas fa-sign-out-alt"></i> Sair</a>
                </div>
            </div>
        </header>

        <div class="welcome-banner">
            <div class="banner-text">
                <h2>Gerencie sua creche!</h2> <br>
                <ul class="banner-features">
                    <li>Cadastro e matrícula de alunos</li>
                    <li>Gestão de professores</li>
                    <li>Gerenciamento de turmas</li>
                    <li>Administração financeira facilitada</li>
                </ul>
            </div>
        </div>

        <h3 class="quick-info-title">Informações rápidas</h3>
        <div class="info-cards-container">
            <div class="info-card card-professores">
                <div class="card-header"><div class="icon"><i class="fas fa-chalkboard-teacher"></i></div></div>
                <div class="card-number" id="prof-count">...</div>
                <div class="card-label">Professores cadastrados</div>
            </div>
            <div class="info-card card-alunos">
                <div class="card-header"><div class="icon"><i class="fas fa-user-graduate"></i></div></div>
                <div class="card-number" id="alunos-count">...</div>
                <div class="card-label">Alunos matriculados</div>
            </div>
            <div class="info-card card-turmas">
                <div class="card-header"><div class="icon"><i class="fas fa-users"></i></div></div>
                <div class="card-number" id="turmas-count">...</div>
                <div class="card-label">Turmas ativas</div>
            </div>
        </div>
        <div class="sete">
            <img src="imagem/sete.png.png" alt="Logo Seteeduca">
        </div>
        
        <footer class="page-footer">
            <p>&copy; 2025 Seteeduca. Todos os direitos reservados.</p>
            <div class="footer-links">
                <a href="#">Termos de Serviço</a>
                <a href="#">Política de Privacidade</a>
            </div>
        </footer>
    </main>

    <div id="logout-modal" class="modal-container">
        <div class="modal-content">
            <p>Tem certeza que deseja sair dessa conta?</p>
            <div class="modal-buttons">
                <button id="cancel-logout" class="btn-cancel">Cancelar</button>
                <button id="confirm-logout" class="btn-confirm">Confirmar</button>
            </div>
        </div>
    </div>


    <script>
        // Função dummy para simular navegação
        function navegarPara(pagina) {
            console.log("Navegando para: " + pagina);
            // Aqui você implementaria a lógica real de navegação (SPA, redirecionamento, etc.)
        }

        document.addEventListener('DOMContentLoaded', function() {
            // --- LÓGICA DO MENU DROPDOWN DO PERFIL ---
            const profileToggle = document.getElementById('profile-toggle');
            const dropdownMenu = document.getElementById('profile-dropdown-menu');
            const profileArrow = profileToggle.querySelector('.profile-arrow');

            profileToggle.addEventListener('click', function(event) {
                event.stopPropagation();
                dropdownMenu.classList.toggle('show');
                profileArrow.style.transform = dropdownMenu.classList.contains('show') ? 'rotate(180deg)' : 'rotate(0deg)';
            });

            window.addEventListener('click', function() {
                if (dropdownMenu.classList.contains('show')) {
                    dropdownMenu.classList.remove('show');
                    profileArrow.style.transform = 'rotate(0deg)';
                }
            });


            // --- NOVA LÓGICA PARA O MODAL DE LOGOUT ---
            const logoutModal = document.getElementById('logout-modal');
            const logoutTriggers = document.querySelectorAll('.logout-trigger');
            const cancelLogoutBtn = document.getElementById('cancel-logout');
            const confirmLogoutBtn = document.getElementById('confirm-logout');

            // Abrir o modal
            logoutTriggers.forEach(trigger => {
                trigger.addEventListener('click', function(event) {
                    event.preventDefault();
                    logoutModal.classList.add('active');
                });
            });

            // Fechar o modal com o botão "Cancelar"
            cancelLogoutBtn.addEventListener('click', function() {
                logoutModal.classList.remove('active');
            });

            // Fechar o modal clicando fora dele
            logoutModal.addEventListener('click', function(event) {
                if (event.target === this) {
                    logoutModal.classList.remove('active');
                }
            });

            // Ação de confirmar o logout
            confirmLogoutBtn.addEventListener('click', function() {
                console.log("Usuário deslogado! Redirecionando...");
                // Aqui você colocaria a lógica real de logout, por exemplo:
                // window.location.href = '/sua-pagina-de-logout';
                logoutModal.classList.remove('active'); // Fecha o modal após confirmar
            });


            // --- BUSCAR DADOS DO BACKEND ---
            // (código mantido, adicionado dados de exemplo em caso de falha)
            fetch('/api/dashboard-data')
                .then(response => response.json())
                .then(data => {
                    document.getElementById('prof-count').textContent = data.professores;
                    document.getElementById('alunos-count').textContent = data.alunos;
                    document.getElementById('turmas-count').textContent = data.turmas;
                })
                .catch(error => {
                    console.error('Erro ao buscar dados (usando dados de exemplo):', error);
                    document.getElementById('prof-count').textContent = 10;
                    document.getElementById('alunos-count').textContent = 10;
                    document.getElementById('turmas-count').textContent = 10;
                });
                });

                document.addEventListener('DOMContentLoaded', function() {
                // ... (outras lógicas do modal)

                const confirmLogoutBtn = document.getElementById('confirm-logout');

                // --- AÇÃO DE CONFIRMAR O LOGOUT (MODIFICADA) ---
                confirmLogoutBtn.addEventListener('click', function() {
                    console.log("Usuário deslogado! Redirecionando para a página de login...");
                    
                    // ESTA É A LINHA QUE FAZ TUDO ACONTECER:
                    window.location.href = 'login.html'; 
                });

                // ... (resto do código)
            });
    </script>
</body>
</html>
