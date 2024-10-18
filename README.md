<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV - Mustafa</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-image: url('https://c4.wallpaperflare.com/wallpaper/522/548/990/rick-and-morty-rick-sanchez-tv-adult-swim-wallpaper-preview.jpg'); /* وضع صورة الخلفية هنا */
            background-size: cover;
            background-position: center;
            height: 100vh; /* ارتفاع كامل الشاشة */
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0;
            padding: 0;
        }

        .container {
            width: 90%;
            max-width: 1000px;
            margin: 30px auto;
            display: flex;
            background-color: white;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }

        .container:hover {
            transform: scale(1.01);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
        }

        /* Left section (Profile picture and Contact info) */
        .left-section {
            width: 35%;
            background-color: #2b2b2b;
            color: white;
            padding: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding-top: 30px; /* Add padding at the top */
            position: relative;
        }

        .profile-pic {
            margin-bottom: 30px;
            position: absolute;
            top: 20px; /* Move the image to the top */
            left: 50%;
            transform: translateX(-50%);
        }

        .profile-pic img {
            width: 180px;
            height: 180px;
            object-fit: cover;
            border: 5px solid #fff;
            border-radius: 20px;
            transition: all 0.3s ease;
        }

        .profile-pic img:hover {
            transform: rotate(5deg);
        }

        .contact-info {
            margin-top: 220px; /* Adjust margin to move content below image */
            text-align: center;
        }

        .contact-info h3 {
            color: #007BFF;
            margin-bottom: 15px;
            text-transform: uppercase;
            letter-spacing: 1.5px;
        }

        .contact-info p {
            margin: 10px 0;
        }

        /* Right section (Personal info and Skills) */
        .right-section {
            width: 65%;
            padding: 30px;
            background-color: #fff;
            transition: all 0.3s ease;
        }

        h1 {
            margin-top: 0;
            font-size: 36px;
            color: #2b2b2b;
        }

        h2 {
            color: #007BFF;
            margin-bottom: 10px;
            font-weight: 600;
        }

        .section {
            margin-bottom: 30px;
        }

        .skills ul, .languages ul {
            list-style: none;
            padding: 0;
            display: flex;
            flex-wrap: wrap;
        }

        .skills ul li, .languages ul li {
            width: 48%;
            margin: 5px 0;
            background-color: #f0f0f0;
            padding: 10px;
            border-radius: 10px;
            text-align: center;
            transition: all 0.3s ease;
        }

        .skills ul li:hover, .languages ul li:hover {
            background-color: #007BFF;
            color: white;
            transform: translateY(-5px);
        }

        .section p {
            line-height: 1.6;
        }

        /* Mobile responsiveness */
        @media (max-width: 768px) {
            .container {
                flex-direction: column;
            }

            .left-section, .right-section {
                width: 100%;
            }

            .profile-pic img {
                width: 150px;
                height: 150px;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Left section -->
        <div class="left-section">
            <div class="profile-pic">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/bc/Brahim_Elmazned_in_2016.jpg/220px-Brahim_Elmazned_in_2016.jpg" alt="Photo de profil de Mustafa">
            </div>
            <div class="contact-info">
                <h3>Contact</h3>
                <p><strong>Téléphone:</strong> 123-456-789</p>
                <p><strong>Email:</strong> mustafa@example.com</p>
                <p><strong>Adresse:</strong> Rue Taboula, Tétouan</p>
                <p><strong>Nationalité:</strong> Marocaine</p>
            </div>
        </div>

        <!-- Right section -->
        <div class="right-section">
            <h1>Mustafa</h1>
            <p>Professionnel en conception de sites web avec une expertise dans la création de sites innovants et bien structurés. Passionné par l'intégration d'éléments visuels et fonctionnels de haute qualité pour améliorer l'expérience utilisateur.</p>

            <!-- Experiences -->
            <div class="section">
                <h2>Expériences Professionnelles</h2>
                <p><strong>Web Designer</strong> – XYZ Company | 2022 - Présent</p>
                <p>Conception et développement de sites web en utilisant HTML, CSS, JavaScript, avec une bonne coordination des couleurs et des éléments visuels.</p>
            </div>

            <!-- Education -->
            <div class="section">
                <h2>Éducation</h2>
                <p><strong>Licence en Informatique</strong> – Université de Tétouan | 2020</p>
            </div>

            <!-- Skills -->
            <div class="section">
                <h2>Compétences</h2>
                <div class="skills">
                    <ul>
                        <li>HTML & CSS</li>
                        <li>JavaScript</li>
                        <li>Conception d'interfaces utilisateur</li>
                        <li>Gestion de projets</li>
                        <li>Git & GitHub</li>
                        <li>Responsive Design</li>
                    </ul>
                </div>
            </div>

            <!-- Languages -->
            <div class="section">
                <h2>Langues</h2>
                <div class="languages">
                    <ul>
                        <li>Arabe – Excellent</li>
                        <li>Anglais – Bon</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>

</body>
</html>
