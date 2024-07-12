<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Conciergerie Airbnb</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #35424a;
            color: #ffffff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #e8491d 3px solid;
        }
        header a {
            color: #ffffff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        #showcase {
            min-height: 400px;
            background: url('showcase.jpg') no-repeat 0 -400px;
            text-align: center;
            color: #ffffff;
        }
        #showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        #showcase p {
            font-size: 20px;
        }
        #main {
            padding: 20px;
            background: #ffffff;
            margin-bottom: 20px;
        }
        #services, #pricing {
            padding: 20px 0;
        }
        .box {
            float: left;
            width: 30%;
            padding: 10px;
            text-align: center;
        }
        footer {
            padding: 20px;
            margin-top: 20px;
            color: #ffffff;
            background-color: #35424a;
            text-align: center;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1>Conciergerie Airbnb</h1>
            </div>
            <nav>
                <ul>
                    <li><a href="#services">Services</a></li>
                    <li><a href="#pricing">Tarifs</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <section id="showcase">
        <div class="container">
            <h1>Gérez Votre Propriété Airbnb Sans Soucis</h1>
            <p>Optimisez l'expérience de vos invités pour maximiser vos revenus locatifs.</p>
        </div>
    </section>
    
    <section id="main" class="container">
        <h2>Présentation</h2>
        <p>
            Dans notre conciergerie, nous comprenons l'importance de fournir une expérience exceptionnelle aux invités pour garantir des avis positifs et fidéliser les clients. Notre équipe est spécialisée dans la gestion de propriétés de location courte durée et s'engage à offrir un service personnalisé et de qualité supérieure.
        </p>
        
        <h2 id="services">Nos Services</h2>
        <div class="box">
            <h3>Gestion Complète</h3>
            <ul>
                <li>Accueil des invités et check-in/check-out</li>
                <li>Ménage et entretien</li>
                <li>Gestion des réservations</li>
                <li>Services supplémentaires</li>
            </ul>
        </div>
        <div class="box">
            <h3>Gestion Simplifiée</h3>
            <ul>
                <li>Accueil des invités</li>
                <li>Nettoyage</li>
                <li>Support invité</li>
            </ul>
        </div>
        <div class="box">
            <h3>Gestion Intermédiaire</h3>
            <ul>
                <li>Accueil des invités et check-in/check-out</li>
                <li>Ménage et entretien</li>
                <li>Support et maintenance</li>
            </ul>
        </div>
        
        <h2 id="pricing">Tarifs et Conditions</h2>
        <p>Nous proposons plusieurs options de tarification en fonction de vos besoins spécifiques :</p>
        <ul>
            <li><strong>Gestion complète</strong> : 25% des revenus locatifs par réservation</li>
            <li><strong>Gestion intermédiaire</strong> : 20% des revenus locatifs par réservation</li>
            <li><strong>Gestion simplifiée</strong> : 15% des revenus locatifs par réservation</li>
            <li><strong>Service à la carte</strong> : 50€ par check-in/check-out</li>
            <ul>
                <li>Studio ou T2 : 25€ (1H)</li>
                <li>T3 : 50€ (2H)</li>
                <li>T4: 75€ (3H)</li>
            </ul>
        </ul>
        <p>Les tarifs incluent tous les frais de déplacement et les équipements nécessaires. Un devis personnalisé sera établi après évaluation de votre propriété et de vos besoins spécifiques.</p>
        
        <h2>Engagement de Qualité</h2>
        <p>
            Nous nous engageons à :
            <ul>
                <li>Offrir un service fiable et de haute qualité</li>
                <li>Assurer la satisfaction de vos invités pour maximiser les avis positifs</li>
                <li>Protéger la confidentialité et la sécurité de votre propriété</li>
                <li>Maintenir une communication continue et transparente</li>
            </ul>
        </p>
        
        <h2>Conclusion</h2>
        <p>
            Nous serions ravis de collaborer avec vous pour maximiser le potentiel de votre propriété Airbnb et offrir une expérience inoubliable à vos invités. N'hésitez pas à nous contacter pour toute question ou pour discuter de vos besoins spécifiques.
        </p>
    </section>
    
    <footer>
        <p>Merci de votre attention et au plaisir de travailler avec vous.</p>
    </footer>
</body>
</html>
