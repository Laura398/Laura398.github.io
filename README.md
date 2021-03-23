<!DOCTYPE html>
<html lang="fr">
    <head>
        <meta charset="utf-8" />

        <!--Viewport-->
        <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">

        <!--Metadescription-->
        <meta name="description" content="Vous cherchez le lieu parfait pour passer les meilleures vacances de votre vie ? Reservia est là pour vous !">
        
        <!--lien fichier CSS-->
        <link rel="stylesheet" href="reservia.css" />
        
        <!--Language-->
        <html lang="fr"></html>
        
        <!--link font awsome for icons-->
        <script src="https://kit.fontawesome.com/f8ffac71bf.js" crossorigin="anonymous"></script>
        
        <!--Favicon-->
        <link rel="shortcut icon" type="image/png" href="favicon.png" />
        
        <!--Titre-->
        <title>Reservia</title>
    </head>

    <body>

        <!-- HEADER: Title + nav + research form and filters-->

        <header>
            
            <div class="header">

                <!--Logo-->
                <p class="logo"><img src="images/logo/Reservia.svg" alt="logo" /></p>
                
                <!--Navigation-->
                <nav>
                    <ul>
                        <li><a href="#hab-ancre" title="Téléportez-vous">Hébergements</a></li>
                        <li><a href="#act-ancre" title="Téléportez-vous">Activités</a></li>
                        <li><a href="" title="Inscrivez-vous">S'inscrire</a></li>
                    </ul>
                </nav>


            </div>

            <!--Formulaire + Filtres-->
            <div class="header-main">

                <h1>Trouvez votre hébergement pour des vacances de rêve</h1>

                <p>En plein centre ville ou en pleine nature</p>

                <!--Formulaire-->
                <div class="custom-home-search">
                    <form method="post" action="traitement.php">
                        <p>
                            <i class="fas fa-map-marker-alt"></i>
                            <input type="search" name="lieu" id="lieu" placeholder="Marseille, France" />
                            <input type="submit" value="Rechercher" />
                        </p>
                    </form>
                </div>

                <!--Filtres-->
                <ul>
                    <li><b>Filtres</b></li>
                    <li><a href="" title="Filtrez votre recherche"><i class="fas fa-money-bill-wave"></i><b>Économique</b></a></li>
                    <li><a href="" title="Filtrez votre recherche"><i class="fas fa-child"></i><b>Familial</b></a></li>
                    <li><a href="" title="Filtrez votre recherche"><i class="fas fa-heart"></i><b>Romantique</b></a></li>
                    <li><a href="" title="Filtrez votre recherche"><i class="fas fa-dog"></i><b>Animaux autorisés</b></a></li>
                </ul>

                <!--Ligne informative-->
                <p><i class="fas fa-info"></i> Plus de 500 logements sont disponibles dans cette ville</p>

            </div>

        </header>

        <!--MAIN: main part, accomodations + Popular + Activities-->

        <main>

            <!--First section: accomodations + popular-->

            <section>

                <h2 class="invisible">Invisible</h2>

                <div class="section1">

                    <!--Article: Hébergements-->

                    <article>

                        <h2 id="hab-ancre">Hébergements à Marseille</h2>
                    
                        <div class="hab-conteneur">

                            <a href="" title="Découvrez le logement">
                                <figure><img class="pic" src="images/hebergements/marcus-loke-WQJvWU_HZFo-unsplash.jpg" alt="cannebiere" />
                                    <figcaption class="pic-text">
                                        <strong>Auberge la Cannebière</strong><br />
                                        Nuit à partir de 25€<br />
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star gray"></i>
                                    </figcaption>
                                </figure>
                            </a>
                            
                            <a href="" title="Découvrez le logement">
                                <figure><img class="pic" src="images/hebergements/fred-kleber-gTbaxaVLvsg-unsplash.jpg" alt="port" />
                                    <figcaption class="pic-text">
                                        <strong>Hôtel du port</strong><br />
                                        Nuit à partir de 52€<br />
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                    </figcaption>
                                </figure>
                            </a>
                            
                            <a href="" title="Découvrez le logement">
                                <figure><img class="pic" src="images/hebergements/reisetopia-B8WIgxA_PFU-unsplash.jpg" alt="mouettes" />
                                    <figcaption class="pic-text">
                                        <strong>Hôtel Les mouettes</strong><br />
                                        Nuit à partir de 76€<br />
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star gray"></i>
                                    </figcaption>
                                </figure>
                            </a>
                            
                            <a href="" title="Découvrez le logement">
                                <figure><img class="pic" src="images/hebergements/annie-spratt-Eg1qcIitAuA-unsplash.jpg" alt="mer" />
                                    <figcaption class="pic-text">
                                        <strong>Hôtel de la mer</strong><br />
                                        Nuit à partir de 46€<br />
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star gray"></i>
                                        <i class="fas fa-star gray"></i>
                                    </figcaption>
                                </figure>
                            </a>
                            
                            <a href="" title="Découvrez le logement">
                                <figure><img class="pic" src="images/hebergements/nicate-lee-kT-ZyaiwBe0-unsplash.jpg" alt="panier" />
                                    <figcaption class="pic-text">
                                        <strong>Auberge Le Panier</strong><br />
                                        Nuit à partir de 23€<br />
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star gray"></i>
                                    </figcaption>
                                </figure>
                            </a>
                            
                            <a href="" title="Découvrez le logement">
                                <figure><img class="pic" src="images/hebergements/febrian-zakaria-M6S1WvfW68A-unsplash.jpg" alt="amina" />
                                    <figcaption class="pic-text">
                                        <strong>Hôtel chez Amina</strong><br />
                                        Nuit à partir de 96€<br />
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                        <i class="fas fa-star blue"></i>
                                    </figcaption>
                                </figure>
                            </a>
                            
                        </div>

                        <p><a href="" title="Partez à la découverte de nos hébergements"><strong>Afficher plus</strong></a></p>

                    </article>

                    <!--Aside: Populaires-->
                    
                    <aside>
                            
                        <div class="aside-title-container">
                            <h2>Les plus populaires</h2>
                            <i class="fas fa-chart-line"></i>
                        </div>

                        <a href="" title="Découvrez le lieu">
                            <figure><img class="pic2" src="images/hebergements/emile-guillemot-Bj_rcSC5XfE-unsplash.jpg" alt="soleil" />
                                <figcaption class="text">
                                    <strong>Hôtel Le soleil du <br />matin</strong><br />
                                    Nuit à partir de 128€
                                    <br />
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star blue2"></i>
                                </figcaption>
                            </figure>
                        </a>

                        <a href="" title="Découvrez le lieu">
                            <figure><img class="pic2" src="images/hebergements/aw-creative-VGs8z60yT2c-unsplash.jpg" alt="eau" />
                                <figcaption class="text">
                                    <strong>Au cœur de l'eau Chambres d'hôtes</strong><br />
                                    Nuit à partir de 71€
                                    <br />
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star gray2"></i>
                                </figcaption>
                            </figure>
                        </a>

                        <a href="" title="Découvrez le lieu">
                            <figure><img class="pic2" src="images/hebergements/febrian-zakaria-sjvU0THccQA-unsplash.jpg" alt="bleu et blanc" />
                                <figcaption class="text">
                                    <strong>Hôtel Tout bleu et Blanc</strong><br />
                                    Nuit à partir de 68€
                                    <br />
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star blue2"></i>
                                    <i class="fas fa-star gray2"></i>
                                </figcaption>
                            </figure>
                        </a>

                    </aside>

                </div>

            </section>

            <!--Second section: Activities-->

            <section>

                <h2 id="act-ancre">Activités à Marseille</h2>

                <div class="section2">

                    <div class="act1">
                        <a href="" title="Découvrez l'activité">
                            <figure>
                                <img class="pic3" src="images/activites/reno-laithienne-QUgJhdY5Fyk-unsplash.jpg" alt="port" />
                                <figcaption class="p-act">Vieux Port</figcaption>
                            </figure>
                        </a>
                    </div>

                    <div class="column2">
                        <div class="act2">
                            <a href="" title="Découvrez l'activité">
                                <figure>
                                    <img class="pic4" src="images/activites/paul-hermann-QFTrLdQIRhI-unsplash.jpg" alt="fort" />
                                    <figcaption class="p-act">Fort de Pomègues</figcaption>
                                </figure>
                            </a>
                        </div>

                        <div class="act3">
                            <a href="" title="Découvrez l'activité">
                                <figure>
                                    <img class="pic5" src="images/activites/kevin-hikari-rV_Qd1l-VXg-unsplash.jpg" alt="iles" />
                                    <figcaption class="p-act">Îles du Frioul</figcaption>
                                </figure>
                            </a>
                        </div>
                    </div>

                    <div class="act4">
                        <a href="" title="Découvrez l'activité">
                            <figure>
                                <img class="pic6" src="images/activites/kilyan-sockalingum-NR8-cBCN3aI-unsplash.jpg" alt="parc" />
                                <figcaption class="p-act">Parc National des Calanques</figcaption>
                            </figure>
                        </a>
                    </div>

                    <div class="column4">
                        <div class="act5">
                            <a href="" title="Découvrez l'activité">
                                <figure>
                                    <img class="pic7" src="images/activites/florian-wehde-xW9e8gdotxI-unsplash.jpg" alt="notre-dame" />
                                    <figcaption class="p-act">Notre-Dame-de-la-Garde</figcaption>
                                </figure>
                            </a>
                        </div>

                        <div class="act6">
                            <a href="" title="Découvrez l'activité">
                                <figure>
                                    <img class="pic8" src="images/activites/lena-paulin-wH2-EJoDcV0-unsplash.jpg" alt="iles" />
                                    <figcaption class="p-act">Parc Longchamp</figcaption>
                                </figure>
                            </a>
                        </div>
                    </div>                   

                </div>

            </section>

        </main>

        <!--Footer-->

        <footer>

            <div class="footer">

                <ul>
                    <li><h3>A propos</h3></li>
                    <li><a href="" title="En savoir plus">Fonctionnement du site</a></li>
                    <li><a href="" title="En savoir plus">Conditions générales de vente</a></li>
                    <li><a href="" title="En savoir plus">Données et confidentialité</a></li>
                </ul>

                <ul>
                    <li><h3>Nos hébergements</h3></li>
                    <li><a href="" title="En savoir plus">Charte qualité</a></li>
                    <li><a href="" title="En savoir plus">Soumettre votre hôtel</a></li>
                </ul>

                <ul>
                    <li><h3>Assistance</h3></li>
                    <li><a href="" title="En savoir plus">Centre d'aide</a></li>
                    <li><a href="" title="En savoir plus">Nous contacter</a></li>
                </ul>

            </div>

        </footer>

    </body>
</html>    
