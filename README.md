<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            font-family: 'Times New Roman', serif;
            background-color: #f5f0e6; /* Parchemin */
            color: #333;
            max-width: 210mm; /* A4 */
            margin: 0 auto;
            padding: 15px;
            border: 8px double #8B4513; /* Bordure vieux papier */
        }
        .header {
            text-align: center;
            background: linear-gradient(to right, #8B0000, #8B4513);
            color: #FFD700; /* Or */
            padding: 15px;
            margin-bottom: 20px;
            border: 3px groove #FFD700;
            font-variant: small-caps;
        }
        h1 {
            font-size: 32px;
            letter-spacing: 2px;
            text-shadow: 2px 2px 4px #000;
            margin: 0;
        }
        h2 {
            background-color: #8B0000;
            color: #FFD700;
            padding: 8px;
            border-left: 15px solid #8B4513;
            margin-top: 25px;
            font-variant: small-caps;
        }
        .timeline {
            display: flex;
            justify-content: space-between;
            margin: 30px 0;
            position: relative;
            padding: 0 50px;
        }
        .timeline::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 0;
            right: 0;
            height: 2px;
            background: linear-gradient(to right, transparent, #8B4513, transparent);
            z-index: 1;
        }
        .timeline-item {
            text-align: center;
            z-index: 2;
            background: url('https://i.imgur.com/JQkYQ6T.png'); /* Texture vieux papier */
            padding: 10px;
            border: 1px solid #8B4513;
            width: 18%;
            box-shadow: 3px 3px 5px rgba(0,0,0,0.3);
        }
        .timeline-year {
            font-weight: bold;
            color: #8B0000;
            font-size: 20px;
            border-bottom: 1px solid #8B4513;
            margin-bottom: 5px;
        }
        .press-section {
            display: flex;
            gap: 15px;
            margin: 20px 0;
        }
        .press-column {
            flex: 1;
            background: url('https://i.imgur.com/JQkYQ6T.png');
            padding: 15px;
            border: 1px solid #8B4513;
            box-shadow: inset 0 0 10px rgba(0,0,0,0.2);
        }
        .quote {
            font-style: italic;
            background: rgba(139, 69, 19, 0.1);
            padding: 15px;
            border-left: 5px solid #8B0000;
            margin: 20px 0;
            font-family: 'Palatino Linotype', serif;
        }
        .newspaper-img {
            float: right;
            width: 150px;
            border: 3px ridge #8B4513;
            margin: 0 0 15px 15px;
            shape-outside: margin-box;
        }
        .footer {
            text-align: center;
            margin-top: 30px;
            font-size: 11px;
            color: #8B4513;
            border-top: 1px dashed #8B4513;
            padding-top: 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>AFFAIRE DREYFUS</h1>
        <p style="color: white; text-shadow: none;">LE RÔLE DE LA PRESSE DANS L'AFFAIRE DU SIÈCLE</p>
    </div>

    <!-- Image de journal vintage (à remplacer par votre image) -->
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/49/J_accuse.jpg/800px-J_accuse.jpg" 
         class="newspaper-img" 
         alt="Une du J'accuse">

    <h2>LA PRESSE DIVISÉE</h2>
    <div class="press-section">
        <div class="press-column">
            <h3 style="color: #8B0000;">◼ DREYFUSARDS</h3>
            <ul style="list-style-type: '✒ ';">
                <li><strong>L'Aurore</strong> (publication de "J'accuse")</li>
                <li><strong>Le Figaro</strong></li>
                <li>Défense des droits de l'homme</li>
                <li>Soutien des intellectuels</li>
            </ul>
        </div>
        <div class="press-column">
            <h3 style="color: #8B0000;">◼ ANTIDREYFUSARDS</h3>
            <ul style="list-style-type: '⚔ ';">
                <li><strong>La Libre Parole</strong> (antisémite)</li>
                <li><strong>Le Petit Journal</strong></li>
                <li>Raison d'État</li>
                <li>Soutien à l'armée</li>
            </ul>
        </div>
    </div>

    <div class="quote">
        "La vérité est en marche et rien ne l'arrêtera" — Émile Zola, L'Aurore (1897)
    </div>

    <h2>CHRONOLOGIE</h2>
    <div class="timeline">
        <div class="timeline-item">
            <div class="timeline-year">1894</div>
            <p>Arrestation<br>de Dreyfus</p>
        </div>
        <div class="timeline-item">
            <div class="timeline-year">1898</div>
            <p>"J'accuse"<br>de Zola</p>
        </div>
        <div class="timeline-item">
            <div class="timeline-year">1899</div>
            <p>Révision<br>du procès</p>
        </div>
        <div class="timeline-item">
            <div class="timeline-year">1906</div>
            <p>Réhabilitation<br>officielle</p>
        </div>
    </div>

    <h2>IMPACT MÉDIATIQUE</h2>
    <div class="press-section">
        <div class="press-column">
            <p><strong>L'Aurore</strong> passe de 30 000 à 300 000 exemplaires en un jour après "J'accuse".</p>
        </div>
        <div class="press-column">
            <p>Apparition des <strong>premiers reportages d'investigation</strong> (Joseph Reinach).</p>
        </div>
    </div>

    <!-- Espace pour images -->
    <div style="text-align: center; margin: 20px 0; border: 2px dashed #8B4513; padding: 15px;">
        <p style="font-style: italic; color: #8B4513;">[Insérer ici : Portraits de Dreyfus/Zola • Caricatures d'époque • Unes de journaux]</p>
    </div>

    <div class="footer">
        Infographie historique • Lycée • 2023 • Sources : BNF Gallica, Musée Dreyfus
    </div>
</body>
</html>
