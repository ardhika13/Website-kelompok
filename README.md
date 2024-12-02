<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kelompok 1 - Our Journey</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');
        
        :root {
            --primary-color: #3498db;
            --secondary-color: #2ecc71;
            --background-color: #f0f4f8;
            --text-color: #2c3e50;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Poppins', sans-serif;
            background-color: var(--background-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }

        .header {
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            text-align: center;
            padding: 2rem;
            clip-path: polygon(0 0, 100% 0, 100% 85%, 0 100%);
            margin-bottom: 30px;
        }

        .header h1 {
            font-size: 2.5rem;
            font-weight: 600;
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        .team-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 20px;
        }

        .member-card {
            background: white;
            border-radius: 10px;
            padding: 25px;
            text-align: center;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
            position: relative;
            overflow: hidden;
        }

        .member-card:hover {
            transform: translateY(-10px);
        }

        .member-card::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 5px;
            background: linear-gradient(to right, var(--primary-color), var(--secondary-color));
        }

        .member-icon {
            font-size: 3rem;
            color: var(--primary-color);
            margin-bottom: 15px;
        }

        .member-name {
            font-size: 1.3rem;
            font-weight: 600;
            margin-bottom: 10px;
        }

        .member-nim {
            color: var(--primary-color);
            font-weight: 300;
            margin-bottom: 15px;
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 15px;
        }

        .social-links a {
            color: var(--text-color);
            font-size: 1.5rem;
            transition: color 0.3s ease;
        }

        .social-links a:hover {
            color: var(--primary-color);
        }

        @media (max-width: 768px) {
            .team-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>Kelompok 1 - Inovasi Bersama</h1>
        </div>

        <div class="team-grid">
            <div class="member-card">
                <div class="member-icon">
                    <i class="fas fa-graduation-cap"></i>
                </div>
                <div class="member-name">Ardhika Galuh Jati Kusuma</div>
                <div class="member-nim">NIM: 23550044</div>
                <div class="social-links">
                    <a href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
                    <a href="#" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                    <a href="#" title="GitHub"><i class="fab fa-github"></i></a>
                </div>
            </div>

            <div class="member-card">
                <div class="member-icon">
                    <i class="fas fa-code"></i>
                </div>
                <div class="member-name">Taufiq Saiful Andi</div>
                <div class="member-nim">NIM: 23550002</div>
                <div class="social-links">
                    <a href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
                    <a href="#" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                    <a href="#" title="GitHub"><i class="fab fa-github"></i></a>
                </div>
            </div>

            <div class="member-card">
                <div class="member-icon">
                    <i class="fas fa-laptop-code"></i>
                </div>
                <div class="member-name">Rizky Hidayat</div>
                <div class="member-nim">NIM: 23550007</div>
                <div class="social-links">
                    <a href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
                    <a href="#" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                    <a href="#" title="GitHub"><i class="fab fa-github"></i></a>
                </div>
            </div>

            <div class="member-card">
                <div class="member-icon">
                    <i class="fas fa-brain"></i>
                </div>
                <div class="member-name">Hilmi Indra Permana</div>
                <div class="member-nim">NIM: 23550018</div>
                <div class="social-links">
                    <a href="#" title="Instagram"><i class="fab fa-instagram"></i></a>
                    <a href="#" title="LinkedIn"><i class="fab fa-linkedin"></i></a>
                    <a href="#" title="GitHub"><i class="fab fa-github"></i></a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
