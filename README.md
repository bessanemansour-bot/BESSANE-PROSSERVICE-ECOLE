# BESSANE-PROSSERVICE-ECOLE<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>École Élémentaire MBAR2 - Excellence & Numérique</title>
    <link rel="stylesheet" href="assets/css/style.css">
</head>
<body>
    <header>
        <h1>MBAR2 - Espace Numérique</h1>
        <nav>
            <ul>
                <li><a href="index.html">Accueil</a></li>
                <li><a href="pages/pedagogie.html">Pédagogie</a></li>
                <li><a href="pages/actualites.html">Actualités</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <h2>Bienvenue à l'École MBAR2</h2>
            <p>Portail officiel géré par le Référent Numérique.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 - Bessane Pro Service - Tous droits réservés</p>
    </footer>
</body>
</html>
/* Configuration de base */
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
}

/* En-tête raffiné */
header {
    background: #ffffff;
    padding: 2rem 5%;
    border-bottom: 1px solid #eee;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-weight: 300;
    letter-spacing: 1px;
    margin: 0;
    color: #2c3e50;
}

/* Navigation épurée */
nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    margin: 0;
}

nav a {
    text-decoration: none;
    color: #555;
    font-weight: 500;
    transition: color 0.3s;
}

nav a:hover {
    color: #007bff; /* Un bleu professionnel pour le rappel numérique */
}

/* Section Principale (Hero) */
.hero {
    text-align: center;
    padding: 100px 20px;
    background: #fff;
}

.hero h2 {
    font-size: 2.5rem;
    margin-bottom: 10px;
}

/* Pied de page discret */
footer {
    text-align: center;
    padding: 40px;
    font-size: 0.9rem;
    color: #888;
    background: #f4f4f4;
}    
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ressources Pédagogiques - MBAR2</title>
    <link rel="stylesheet" href="../assets/css/style.css">
</head>
<body>
    <header>
        <h1>MBAR2 - Pédagogie</h1>
        <nav>
            <ul>
                <li><a href="../index.html">Accueil</a></li>
                <li><a href="pedagogie.html">Ressources</a></li>
            </ul>
        </nav>
    </header>

    <main class="container">
        <h2>Supports Pédagogiques du Sénégal</h2>
        <p>Retrouvez ici les fiches de préparation et évaluations pour chaque niveau.</p>

        <div class="grid-niveaux">
            <article class="card">
                <h3>Étape 1 : CI - CP</h3>
                <p>Fiches d'activités et initiation à la lecture.</p>
                <a href="#" class="btn">Accéder</a>
            </article>

            <article class="card">
                <h3>Étape 2 : CE1 - CE2</h3>
                <p>Supports de français et mathématiques.</p>
                <a href="#" class="btn">Accéder</a>
            </article>

            <article class="card">
                <h3>Étape 3 : CM1 - CM2</h3>
                <p>Préparation au CFEE et ressources avancées.</p>
                <a href="#" class="btn">Accéder</a>
            </article>
        </div>
    </main>
</body>
</html>.container {
    max-width: 1000px;
    margin: 40px auto;
    padding: 0 20px;
}

.grid-niveaux {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin-top: 30px;
}

.card {
    background: #ffffff;
    padding: 25px;
    border: 1px solid #eee;
    border-radius: 8px;
    transition: transform 0.2s, box-shadow 0.2s;
}

.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.05);
}

.btn {
    display: inline-block;
    margin-top: 15px;
    padding: 10px 20px;
    background-color: #007bff;
    color: #fff;
    text-decoration: none;
    border-radius: 4px;
    font-size: 0.9rem;
}
<section class="referent-numerique">
    <hr>
    <h2>Espace Référent Numérique</h2>
    <div class="banner-ai">
        <h3>Innovation & IA avec Bessane Pro Service</h3>
        <p>Découvrez comment l'intelligence artificielle transforme nos pratiques enseignantes à MBAR2.</p>
        
        <ul class="tuto-list">
            <li><strong>Tutoriel 1 :</strong> Créer des visuels pédagogiques avec l'IA.</li>
            <li><strong>Tutoriel 2 :</strong> Sécuriser les comptes Windows de l'école.</li>
            <li><strong>Tutoriel 3 :</strong> Guide de dépannage matériel (maintenance PC).</li>
        </ul>
        <a href="#" class="btn-dark">Consulter les ressources numériques</a>
    </div>
</section>
.referent-numerique {
    margin-top: 60px;
}

hr {
    border: 0;
    border-top: 1px dashed #ccc;
    margin-bottom: 40px;
}

.banner-ai {
    background: #2c3e50;
    color: #ffffff;
    padding: 40px;
    border-radius: 12px;
    text-align: left;
}

.banner-ai h3 {
    color: #00d1b2; /* Une touche de vert technologique */
    margin-top: 0;
}

.tuto-list {
    margin: 20px 0;
    padding-left: 20px;
}

.tuto-list li {
    margin-bottom: 10px;
    font-size: 0.95rem;
}

.btn-dark {
    display: inline-block;
    padding: 12px 25px;
    background-color: #ffffff;
    color: #2c3e50;
    text-decoration: none;
    font-weight: bold;
    border-radius: 4px;
    transition: background 0.3s;
}

.btn-dark:hover {
    background-color: #00d1b2;
    color: white;
}