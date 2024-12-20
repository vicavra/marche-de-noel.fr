<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Marché de Noël</title>
    <!-- Style interne -->
    <style>
        /* Styles de base */
        body {
            margin: 0;
            font-family: 'Georgia', serif;
            background-color: #b22222; /* Fond rouge */
            color: #fff; /* Texte en blanc */
            line-height: 1.6;
        }
        header {
            background-color: #8b0000; /* Rouge foncé */
            text-align: center;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            text-align: center;
            background-color: #a52a2a; /* Brun rougeâtre */
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .hero {
            text-align: center;
            padding: 100px 20px;
            background: rgba(0, 0, 0, 0.5);
        }
        section {
            padding: 20px;
            max-width: 1100px;
            margin: 20px auto;
            background-color: #fff;
            color: #333;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.2);
        }
        section h2 {
            text-align: center;
            color: #b22222;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            gap: 20px;
        }
        .product {
            background-color: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 10px;
            width: 300px;
            text-align: center;
            padding: 15px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            width: 100%;
            border-radius: 10px 10px 0 0;
        }
        .product h3 {
            color: #8b0000;
            font-size: 1.5em;
            margin: 10px 0;
        }
        .product p {
            font-size: 1em;
            margin-bottom: 15px;
        }
        footer {
            background-color: #8b0000;
            color: darkolivegreen;
            text-align: center;
            padding: 10px 0;
        }
        #contact {
            text-align: center;
        }
        #contact p {
            font-size: 1.2em;
        }
        #contact a {
            color: #b22222;
            font-weight: bold;
            text-decoration: italic;
        }
        #contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <!-- En-tête -->
    <header>
        <h1>Marché de Noël en Ligne</h1>
        <p>Découvrez nos produits festifs disponibles en décembre !</p>
        <p> Le Marché de Noël en ligne vous offre une expérience unique pour préparer vos fêtes de fin d'année en toute sérénité.</p>
    </header>

    <!-- Navigation -->
    <nav>
        <a href="#accueil">Accueil</a>
        <a href="#produits">Nos Produits</a>
        <a href="#musique">Musique de Noël</a>
        <a href="#histoire">Histoire</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Section Accueil -->
    <div class="hero" id="accueil">
        <h2>Bienvenue au Marché de Noël</h2>
        <p>Découvrez des biscuits délicieux, des cadeaux uniques et des décorations faites maison pour les fêtes !</p>
    </div>

    <!-- Section Produits -->
    <section id="produits">
        <h2>Nos Produits</h2>
        <div class="products">
            <!-- Produit 1 -->
            <div class="product">
                <img src="https://i.pinimg.com/736x/83/c9/6c/83c96c731667db929919a2a62ed07db4.jpg" alt="Biscuits de Noël">
                <h3>Biscuits de Noël</h3>
                <p>De délicieux biscuits faits maison pour régaler petits et grands.</p>
            </div>
            <!-- Produit 2 -->
            <div class="product">
                <img src="https://i.pinimg.com/736x/3e/67/ae/3e67aeb575cc94ec8b8243035a09421d.jpg" alt="Cartes de Noël">
                <h3>Cartes de Noël</h3>
                <p>Des cartes personnalisées pour vos êtres aimés.</p>
            </div>
            <!-- Produit 3 -->
            <div class="product">
                <img src="https://i.pinimg.com/736x/cb/2a/16/cb2a16fdfd134e1db071cbf2ae733733.jpg" alt="Décorations festives">
                <h3>Décorations Maison</h3>
                <p>Ajoutez de la magie à votre maison avec nos décorations uniques.</p>
            </div>  
        </div>
            <!-- Section Musique de Noël -->
    <section id="musique">
        <h2>Musique de Noël</h2>
       <section id="musique">
    <p>Plongez dans l’ambiance festive de Noël avec notre playlist spécialement sélectionnée :</p>
    <iframe style="border-radius:12px" 
        src="https://open.spotify.com/embed/playlist/37i9dQZF1DX5D4gDh3HAsM?utm_source=generator" 
        width="100%" height="352" frameBorder="0" allowfullscreen="" 
        allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" 
        loading="lazy">
    </iframe>
            <!-- YouTube Embed -->
    <h3>Playlist YouTube</h3>
    <iframe width="100%" height="315" 
        src="https://www.youtube.com/embed/Y3tfbmdbhTw" 
        title="YouTube playlist" 
        frameborder="0" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
    </iframe>
</section>
</section>
        
    <!-- Section Histoire -->
    <section id="histoire">
        <h2>Histoire de notre Marché de Noël</h2>
    <style>
    #histoire p {
        text-align: justify;
    }
</style>

        <p>
            Le Marché de Noël en ligne est né d'une volonté de prolonger la magie des fêtes tout en s'adaptant aux besoins modernes. 
         Dans le cadre d'un devoir maison pour le cours d'informatique appliquée, j’ai choisi de créer un site web dédié à un marché de Noël virtuel. Décembre étant à la fois un mois festif et marqué par des températures froides, ce projet a pour objectif de permettre au public de profiter de l’ambiance magique de Noël, même lors des journées les plus glaciales.

            Dès le début de ce projet, j’ai sollicité l’aide de ChatGPT pour m’accompagner dans la création du site. En quelques secondes seulement, il a intégré mes demandes spécifiques, telles que les sections du site, la couleur rouge emblématique de Noël, ou encore la police Georgia pour son élégance et son authenticité. Initialement, j'avais envisagé de créer une fonctionnalité permettant d’ajouter des articles au panier, mais étant donné qu’il ne s’agit pas d’un véritable site de commerce en ligne, cette option était difficile à implémenter. J’ai donc décidé de simplifier les commandes en indiquant qu’elles seraient réalisées via un mail, qui est, en réalité, mon adresse étudiante.

            L'une des premières difficultés que j’ai rencontrées concernait la gestion des images. J’ai dû parcourir une multitude de sources pour sélectionner les visuels à intégrer sur le site. Toutefois, certains d’entre eux étaient soumis à des droits d’auteur, ce qui m’a obligée à redoubler d’efforts pour trouver des alternatives libres de droits. De plus, j’ai veillé à utiliser des images ayant des dimensions uniformes (de type carré) afin d’assurer une présentation harmonieuse et esthétique.

            Lorsque j’ai souhaité enrichir le site, notamment avec une section dédiée à la musique de Noël, j’ai repris le format que ChatGPT avait initialement créé. En suivant cette même logique, j’ai manuellement ajouté une nouvelle section contenant un lien vers une playlist YouTube et une autre sur Spotify. Cette playlist permet aux visiteurs de plonger dans une ambiance festive et chaleureuse tout en explorant les produits proposés.

            Enfin, dans la section intitulée “L’histoire de notre marché”, j’ai souhaité raconter le processus créatif derrière ce projet. J’y détaille mes inspirations, les obstacles que j’ai rencontrés, ainsi que certaines idées ambitieuses que je n’ai finalement pas pu concrétiser. Cette démarche m’a permis de prendre du recul sur mon travail et de valoriser l’apprentissage que ce projet m’a apporté.
        </p>
    </section>   
    
    <!-- Section Contact -->
    <section id="contact">
        <h2>Contact</h2>
        <p>Nous sommes rejoignables par mail pour vos commandes :</p>
        <p><a href="mailto:victoria.avraamidou@etu.univ-poitiers.fr">marchedenoel.fr</a></p>
    </section>

    <!-- Pied de page -->
    <footer>
        <p>&copy; 2024 Marché de Noël | Joyeuses Fêtes !</p>
    </footer>    
<html>
