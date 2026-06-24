<div style="background:#f8fafc; color:#111827; padding:24px; border-radius:10px; border:2px solid #2563eb;">
  <h1 style="margin:0 0 10px 0; color:#111827;">Documentation du projet</h1>
  <p style="margin:0; color:#111827;">Cette documentation explique les différentes étapes de création et d’amélioration du site.</p>
</div>

<div style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:18px; margin-top:20px;">
  <h2 style="margin-top:0; color:#111827;">Sommaire des étapes</h2>
  <ul>
    <li style="color:#111827;"><a href="#etape-1--preparer-limage-de-fond" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 1 — Préparer l’image de fond</a></li>
    <li style="color:#111827;"><a href="#etape-2--creer-la-zone-qui-recevra-limage-de-fond" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 2 — Créer la zone qui recevra l’image de fond</a></li>
    <li style="color:#111827;"><a href="#etape-3--appliquer-limage-de-fond-avec-css" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 3 — Appliquer l’image de fond avec CSS</a></li>
    <li style="color:#111827;"><a href="#etape-4--definir-la-hauteur-de-la-section-et-adapter-limage" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 4 — Définir la hauteur de la section et adapter l’image</a></li>
    <li style="color:#111827;"><a href="#etape-5--creer-le-menu-cliquable-par-dessus-limage" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 5 — Créer le menu cliquable par-dessus l’image</a></li>
    <li style="color:#111827;"><a href="#etape-6--organiser-le-menu-sous-forme-de-grille" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 6 — Organiser le menu sous forme de grille</a></li>
    <li style="color:#111827;"><a href="#etape-7--centrer-la-grille-du-menu-sur-limage" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 7 — Centrer la grille du menu sur l’image</a></li>
    <li style="color:#111827;"><a href="#etape-8--transformer-les-liens-en-veritables-boutons-de-navigation" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 8 — Transformer les liens en véritables boutons de navigation</a></li>
    <li style="color:#111827;"><a href="#etape-9--ajouter-un-effet-de-survol-aux-boutons-du-menu" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 9 — Ajouter un effet de survol aux boutons du menu</a></li>
  </ul>
  <p style="margin-bottom:0; color:#111827;"><strong style="color:#111827;">Note :</strong> d’autres étapes pourront être ajoutées plus tard dans ce sommaire.</p>
</div>

<div style="background:#ffffff; color:#111827; border:2px solid #93c5fd; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Intégration d’une image de fond pour le menu principal</h2>
  <p style="color:#111827;">Pour améliorer l’aspect visuel de la page d’accueil, une image de fond sera ajoutée dans la zone du menu principal.</p>
  <p style="margin-bottom:0; color:#111827;">Cette image servira uniquement de décoration graphique. Les boutons du menu seront ensuite placés par-dessus en HTML/CSS afin de rester réellement cliquables.</p>
</div>

<div id="etape-1--preparer-limage-de-fond" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 1 — Préparer l’image de fond</h2>
  <p style="color:#111827;">Avant de l’utiliser dans le code, l’image doit être placée dans le dossier prévu pour les images du site.</p>

  <h3 style="color:#111827;">Structure du projet</h3>

  <pre style="background:#f3f4f6; color:#111827; padding:16px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">/mon-site
|
|-- index.html
|-- css/
|   `-- style.css
|
`-- images/
    `-- fond-menu-triumph.png</code></pre>

  <p style="color:#111827;">L’image de fond est donc enregistrée dans le dossier :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">images/</code></pre>

  <p style="color:#111827;">avec un nom simple, sans espace, par exemple :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">fond-menu-triumph.png</code></pre>

  <p style="margin-bottom:0; color:#111827;">Cela permet de l’appeler facilement depuis le fichier CSS.</p>
</div>

<div id="etape-2--creer-la-zone-qui-recevra-limage-de-fond" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 2 — Créer la zone qui recevra l’image de fond</h2>
  <p style="color:#111827;">L’image ne sera pas appliquée directement à toute la page. Elle sera placée dans un conteneur dédié qui accueillera également le menu principal.</p>

  <p style="color:#111827;">Dans le fichier <strong style="color:#111827;">index.html</strong>, créer une section dédiée au menu d’accueil :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:16px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">&lt;main&gt;

    &lt;section id=&quot;menu-principal&quot;&gt;

    &lt;/section&gt;

&lt;/main&gt;</code></pre>

  <h3 style="color:#111827;">Explication</h3>

  <ul>
    <li style="color:#111827;">La balise <code style="color:#111827;">&lt;main&gt;</code> contient le contenu principal de la page.</li>
    <li style="color:#111827;">La balise <code style="color:#111827;">&lt;section&gt;</code> permet de regrouper une partie logique du contenu.</li>
    <li style="color:#111827;">L’identifiant <code style="color:#111827;">menu-principal</code> servira à appliquer l’image de fond via le fichier CSS.</li>
    <li style="color:#111827;">Les boutons du menu seront ajoutés à l’intérieur de cette section lors des prochaines étapes.</li>
  </ul>

  <p style="margin-bottom:0; color:#111827;">À ce stade, la page contient simplement une zone vide destinée à recevoir l’image de fond et le futur menu de navigation.</p>
</div>

<div id="etape-3--appliquer-limage-de-fond-avec-css" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 3 — Appliquer l’image de fond avec CSS</h2>
  <p style="color:#111827;">Maintenant que la zone <code style="color:#111827;">menu-principal</code> existe dans le fichier HTML, nous allons lui attribuer l’image de fond.</p>

  <p style="color:#111827;">Dans le fichier <strong style="color:#111827;">css/style.css</strong>, ajouter le code suivant :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:16px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">#menu-principal
{
    background-image: url(&quot;../images/fond-menu-triumph.png&quot;);
}</code></pre>

  <h3 style="color:#111827;">Explication</h3>

  <ul>
    <li style="color:#111827;"><code style="color:#111827;">background-image</code> permet d’utiliser une image comme arrière-plan.</li>
    <li style="color:#111827;"><code style="color:#111827;">url()</code> indique l’emplacement du fichier image.</li>
    <li style="color:#111827;"><code style="color:#111827;">..</code> signifie que l’on remonte d’un dossier, depuis <code style="color:#111827;">css/</code> vers la racine du projet.</li>
    <li style="color:#111827;"><code style="color:#111827;">images/</code> correspond au dossier contenant les images.</li>
    <li style="color:#111827;"><code style="color:#111827;">fond-menu-triumph.png</code> est le nom de l’image utilisée.</li>
  </ul>

  <h3 style="color:#111827;">Résultat attendu</h3>

  <p style="color:#111827;">À ce stade, l’image est bien associée à la section <code style="color:#111827;">menu-principal</code>.</p>

  <p style="margin-bottom:0; color:#111827;">Cependant, elle risque de ne pas être visible correctement car la section ne possède pas encore de dimensions définies. Dans l’étape suivante, nous définirons la hauteur et le comportement de l’image afin qu’elle occupe correctement l’espace disponible.</p>
</div>

<div id="etape-4--definir-la-hauteur-de-la-section-et-adapter-limage" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 4 — Définir la hauteur de la section et adapter l’image</h2>
  <p style="color:#111827;">Pour que l’image soit visible correctement, il est nécessaire de donner une hauteur à la section et d’indiquer comment l’image doit s’adapter à l’espace disponible.</p>

  <p style="color:#111827;">Dans le fichier <strong style="color:#111827;">css/style.css</strong>, compléter la règle CSS :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:16px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">#menu-principal
{
    background-image: url(&quot;../images/fond-menu-triumph.png&quot;);

    height: 600px;

    background-size: cover;

    background-position: center;
}</code></pre>

  <h3 style="color:#111827;">Explication</h3>

  <p style="color:#111827;"><strong style="color:#111827;">height: 600px;</strong></p>
  <ul>
    <li style="color:#111827;">Définit une hauteur de 600 pixels pour la section.</li>
    <li style="color:#111827;">Sans hauteur, la section est vide et l’image ne peut pas s’afficher correctement.</li>
  </ul>

  <p style="color:#111827;"><strong style="color:#111827;">background-size: cover;</strong></p>
  <ul>
    <li style="color:#111827;">Agrandit automatiquement l’image afin qu’elle couvre toute la surface du conteneur.</li>
    <li style="color:#111827;">L’image conserve ses proportions et remplit entièrement la zone.</li>
  </ul>

  <p style="color:#111827;"><strong style="color:#111827;">background-position: center;</strong></p>
  <ul>
    <li style="color:#111827;">Centre l’image horizontalement et verticalement.</li>
    <li style="color:#111827;">La partie la plus importante de l’image reste visible même lorsque celle-ci est recadrée.</li>
  </ul>

  <h3 style="color:#111827;">Résultat attendu</h3>

  <p style="color:#111827;">À cette étape, la section <code style="color:#111827;">menu-principal</code> affiche correctement l’image de fond sur une hauteur de 600 px.</p>

  <p style="margin-bottom:0; color:#111827;">Le menu n’est pas encore présent. La prochaine étape consistera à créer un conteneur qui accueillera les boutons du menu au-dessus de l’image.</p>
</div>

<div id="etape-5--creer-le-menu-cliquable-par-dessus-limage" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 5 — Créer le menu cliquable par-dessus l’image</h2>
  <p style="color:#111827;">Maintenant que l’image de fond est affichée correctement, il faut ajouter le vrai menu HTML à l’intérieur de la section <code style="color:#111827;">menu-principal</code>.</p>

  <p style="color:#111827;">Dans le fichier <strong style="color:#111827;">index.html</strong>, modifier la section comme ceci :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:16px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">&lt;main&gt;

    &lt;section id=&quot;menu-principal&quot;&gt;

        &lt;div class=&quot;menu-accueil&quot;&gt;

            &lt;a href=&quot;histoire.html&quot;&gt;Histoire de Triumph&lt;/a&gt;
            &lt;a href=&quot;motos/bonneville.html&quot;&gt;Bonneville&lt;/a&gt;
            &lt;a href=&quot;motos/daytona.html&quot;&gt;Daytona&lt;/a&gt;
            &lt;a href=&quot;motos/street-triple.html&quot;&gt;Street Triple&lt;/a&gt;
            &lt;a href=&quot;motos/speed-triple.html&quot;&gt;Speed Triple&lt;/a&gt;
            &lt;a href=&quot;motos/tiger.html&quot;&gt;Tiger&lt;/a&gt;
            &lt;a href=&quot;motos/rocket.html&quot;&gt;Rocket&lt;/a&gt;
            &lt;a href=&quot;motos/thruxton.html&quot;&gt;Thruxton&lt;/a&gt;
            &lt;a href=&quot;motos/scrambler.html&quot;&gt;Scrambler&lt;/a&gt;
            &lt;a href=&quot;a-propos.html&quot;&gt;À propos du projet&lt;/a&gt;

        &lt;/div&gt;

    &lt;/section&gt;

&lt;/main&gt;</code></pre>

  <h3 style="color:#111827;">Explication</h3>

  <p style="color:#111827;">Les liens <code style="color:#111827;">&lt;a&gt;</code> sont placés dans une <code style="color:#111827;">&lt;div&gt;</code> portant la classe <code style="color:#111827;">menu-accueil</code>.</p>

  <p style="color:#111827;">Cette classe servira ensuite à organiser les liens sous forme de grille avec CSS.</p>

  <p style="color:#111827;">Les pages <code style="color:#111827;">histoire.html</code> et <code style="color:#111827;">a-propos.html</code> sont dans le même dossier que <code style="color:#111827;">index.html</code>, donc le lien est écrit directement.</p>

  <p style="color:#111827;">Les pages des motos sont rangées dans le dossier <code style="color:#111827;">motos</code>, donc le chemin doit commencer par :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">motos/</code></pre>

  <p style="color:#111827;">Exemple :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">&lt;a href=&quot;motos/bonneville.html&quot;&gt;Bonneville&lt;/a&gt;</code></pre>

  <p style="margin-bottom:0; color:#111827;">Le menu visible dans l’image de fond est uniquement décoratif. Les liens ajoutés ici seront les vrais boutons cliquables du site.</p>
</div>

<div id="etape-6--organiser-le-menu-sous-forme-de-grille" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 6 — Organiser le menu sous forme de grille</h2>
  <p style="color:#111827;">Pour obtenir un menu visuel proche d’un tableau, les liens seront organisés en deux colonnes grâce au CSS.</p>

  <p style="color:#111827;">Dans le fichier <strong style="color:#111827;">css/style.css</strong>, ajouter :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:16px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">.menu-accueil
{
    display: grid;

    grid-template-columns: 1fr 1fr;

    gap: 15px;
}</code></pre>

  <h3 style="color:#111827;">Explication</h3>

  <ul>
    <li style="color:#111827;"><code style="color:#111827;">display: grid;</code> transforme le menu en grille.</li>
    <li style="color:#111827;"><code style="color:#111827;">grid-template-columns: 1fr 1fr;</code> crée deux colonnes de même largeur.</li>
    <li style="color:#111827;"><code style="color:#111827;">gap: 15px;</code> ajoute un espace entre les boutons.</li>
  </ul>

  <h3 style="color:#111827;">Résultat attendu</h3>

  <p style="margin-bottom:0; color:#111827;">Les liens du menu ne seront plus affichés les uns sous les autres. Ils seront répartis en deux colonnes, comme un tableau de navigation.</p>
</div>

<div id="etape-7--centrer-la-grille-du-menu-sur-limage" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 7 — Centrer la grille du menu sur l’image</h2>
  <p style="color:#111827;">Actuellement, les liens sont bien présents, mais ils ne sont pas encore positionnés correctement.</p>
  <p style="color:#111827;">Nous allons centrer le bloc du menu au milieu de l’image de fond.</p>

  <p style="color:#111827;">Dans le fichier <strong style="color:#111827;">css/style.css</strong>, complète la règle <code style="color:#111827;">#menu-principal</code> comme ceci :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:16px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">#menu-principal
{
    background-image: url(&quot;../images/fond-menu-triumph.png&quot;);
    height: 500px;
    background-size: cover;
    background-position: center;

    display: flex;
    justify-content: center;
    align-items: center;
}</code></pre>

  <h3 style="color:#111827;">Explication</h3>

  <ul>
    <li style="color:#111827;"><code style="color:#111827;">display: flex;</code> permet d’utiliser Flexbox pour placer le contenu.</li>
    <li style="color:#111827;"><code style="color:#111827;">justify-content: center;</code> centre le menu horizontalement.</li>
    <li style="color:#111827;"><code style="color:#111827;">align-items: center;</code> centre le menu verticalement.</li>
  </ul>

  <h3 style="color:#111827;">Résultat attendu</h3>

  <p style="color:#111827;">Le bloc contenant les liens du menu sera placé au centre de l’image de fond.</p>
  <p style="margin-bottom:0; color:#111827;">À l’étape suivante, on transformera les liens en vrais boutons noirs avec bordures rouges.</p>
</div>

<div id="etape-8--transformer-les-liens-en-veritables-boutons-de-navigation" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 8 — Transformer les liens en véritables boutons de navigation</h2>
  <p style="color:#111827;">Maintenant que le menu est centré sur l’image, nous allons donner aux liens l’apparence de véritables boutons afin de se rapprocher du style présenté sur la maquette graphique.</p>

  <p style="color:#111827;">Dans le fichier <strong style="color:#111827;">css/style.css</strong>, ajouter la règle suivante :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:16px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">.menu-accueil a
{
    text-decoration: none;

    color: #FFFFFF;

    background-color: rgba(0, 0, 0, 0.80);

    border: 1px solid #D71920;

    padding: 15px;

    text-align: center;

    font-weight: bold;
}</code></pre>

  <h3 style="color:#111827;">Explication</h3>

  <p style="color:#111827;"><strong style="color:#111827;">text-decoration: none;</strong></p>
  <p style="color:#111827;">Supprime le soulignement des liens.</p>

  <p style="color:#111827;"><strong style="color:#111827;">color: #FFFFFF;</strong></p>
  <p style="color:#111827;">Affiche le texte en blanc.</p>

  <p style="color:#111827;"><strong style="color:#111827;">background-color: rgba(0, 0, 0, 0.80);</strong></p>
  <p style="color:#111827;">Ajoute un fond noir semi-transparent.</p>

  <p style="color:#111827;"><strong style="color:#111827;">border: 1px solid #D71920;</strong></p>
  <p style="color:#111827;">Ajoute une bordure rouge inspirée de l’identité visuelle Triumph.</p>

  <p style="color:#111827;"><strong style="color:#111827;">padding: 15px;</strong></p>
  <p style="color:#111827;">Ajoute un espace intérieur pour agrandir les boutons.</p>

  <p style="color:#111827;"><strong style="color:#111827;">text-align: center;</strong></p>
  <p style="color:#111827;">Centre le texte à l’intérieur des boutons.</p>

  <p style="color:#111827;"><strong style="color:#111827;">font-weight: bold;</strong></p>
  <p style="color:#111827;">Affiche le texte en gras.</p>

  <h3 style="color:#111827;">Résultat attendu</h3>

  <p style="color:#111827;">Les liens ne ressembleront plus à de simples liens HTML bleus.</p>
  <p style="margin-bottom:0; color:#111827;">Ils prendront l’apparence de véritables boutons de navigation noirs avec une bordure rouge et un texte blanc, en harmonie avec les couleurs du site.</p>
</div>

<div id="etape-9--ajouter-un-effet-de-survol-aux-boutons-du-menu" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 9 — Ajouter un effet de survol aux boutons du menu</h2>
  <p style="color:#111827;">Afin d’améliorer l’expérience utilisateur, un effet visuel sera appliqué lorsque le visiteur passera la souris sur un bouton du menu.</p>

  <p style="color:#111827;">Dans le fichier <strong style="color:#111827;">css/style.css</strong>, ajouter la règle suivante :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:16px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">.menu-accueil a:hover
{
    background-color: rgba(215, 25, 32, 0.90);

    color: #FFFFFF;

    transition: 0.3s;
}</code></pre>

  <h3 style="color:#111827;">Explication</h3>

  <p style="color:#111827;"><strong style="color:#111827;">:hover</strong></p>
  <p style="color:#111827;">Le pseudo-sélecteur <code style="color:#111827;">:hover</code> s’active lorsque la souris passe sur un élément.</p>

  <p style="color:#111827;"><strong style="color:#111827;">background-color</strong></p>
  <p style="color:#111827;">Le fond du bouton devient rouge Triumph.</p>

  <p style="color:#111827;"><strong style="color:#111827;">color</strong></p>
  <p style="color:#111827;">Le texte reste blanc afin de conserver une bonne lisibilité.</p>

  <p style="color:#111827;"><strong style="color:#111827;">transition</strong></p>
  <p style="color:#111827;">Crée une animation fluide lors du changement de couleur.</p>

  <h3 style="color:#111827;">Résultat attendu</h3>

  <p style="color:#111827;">Lorsque l’utilisateur passe la souris sur un bouton :</p>

  <ul>
    <li style="color:#111827;">le fond noir disparaît progressivement ;</li>
    <li style="color:#111827;">le bouton devient rouge ;</li>
    <li style="color:#111827;">le texte reste blanc ;</li>
    <li style="color:#111827;">la transition est fluide et moderne.</li>
  </ul>

  <h3 style="color:#111827;">Amélioration recommandée</h3>

  <p style="color:#111827;">Pour que l’animation fonctionne également lorsque la souris quitte le bouton, ajouter la propriété <code style="color:#111827;">transition</code> dans la règle principale des liens :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:16px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">.menu-accueil a
{
    text-decoration: none;
    color: #FFFFFF;
    background-color: rgba(0, 0, 0, 0.80);
    border: 1px solid #D71920;
    padding: 10px;
    text-align: center;
    font-weight: bold;

    transition: 0.3s;
}</code></pre>

  <p style="margin-bottom:0; color:#111827;">Cette méthode est la plus propre et la plus utilisée dans les sites web modernes.</p>
</div>
