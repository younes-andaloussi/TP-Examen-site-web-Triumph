<div style="background:#f8fafc; color:#111827; padding:24px; border-radius:10px; border:2px solid #2563eb;">
  <h1 style="margin:0 0 10px 0; color:#111827;">Tutoriel Git et GitHub</h1>
  <p style="margin:0; color:#111827;">Cette documentation explique les étapes de versionnage du projet et sa préparation à la publication en ligne.</p>
</div>

<div style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:18px; margin-top:20px;">
  <h2 style="margin-top:0; color:#111827;">Sommaire des étapes</h2>
  <ul>
    <li style="color:#111827;"><a href="#etape-1--initialisation-du-depot-git" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 1 — Initialisation du dépôt Git</a></li>
  </ul>
  <p style="margin-bottom:0; color:#111827;"><strong style="color:#111827;">Note :</strong> d’autres étapes pourront être ajoutées plus tard dans ce sommaire.</p>
</div>

<div id="etape-1--initialisation-du-depot-git" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 1 — Initialisation du dépôt Git</h2>

  <h3 style="color:#111827;">Objectif</h3>

  <p style="color:#111827;">Avant de publier le site web sur Internet, il est nécessaire de mettre en place un système de gestion de versions. Celui-ci permet de suivre l’évolution du projet, d’enregistrer les différentes modifications apportées au code source et de conserver un historique complet du développement.</p>

  <p style="color:#111827;">Pour ce projet, le système de gestion de versions <strong style="color:#111827;">Git</strong> a été utilisé afin de préparer le site à son hébergement sur <strong style="color:#111827;">GitHub</strong> et à sa publication avec <strong style="color:#111827;">GitHub Pages</strong>.</p>

  <h3 style="color:#111827;">Préparation du projet</h3>

  <p style="color:#111827;">Une fois le développement du site terminé, l’ensemble des fichiers a été regroupé dans un dossier unique contenant toutes les ressources nécessaires au fonctionnement du projet.</p>

  <p style="color:#111827;">L’arborescence principale comprend notamment :</p>

  <ul>
    <li style="color:#111827;">les pages HTML ;</li>
    <li style="color:#111827;">les feuilles de style CSS ;</li>
    <li style="color:#111827;">les images utilisées sur le site ;</li>
    <li style="color:#111827;">la documentation du projet.</li>
  </ul>

  <p style="color:#111827;">Cette organisation facilite la maintenance du site et constitue une base de travail adaptée à l’utilisation d’un système de gestion de versions.</p>

  <h3 style="color:#111827;">Ouverture du projet dans Visual Studio Code</h3>

  <p style="color:#111827;">Le dossier du projet a ensuite été ouvert dans <strong style="color:#111827;">Visual Studio Code</strong>, l’environnement de développement utilisé pour réaliser le site.</p>

  <p style="color:#111827;">Visual Studio Code permet notamment :</p>

  <ul>
    <li style="color:#111827;">la modification du code HTML et CSS ;</li>
    <li style="color:#111827;">la gestion des fichiers du projet ;</li>
    <li style="color:#111827;">l’intégration avec Git ;</li>
    <li style="color:#111827;">l’utilisation d’un terminal intégré pour exécuter les commandes Git.</li>
  </ul>

  <h3 style="color:#111827;">Initialisation du dépôt Git</h3>

  <p style="color:#111827;">Afin de commencer le suivi des versions, un dépôt Git a été initialisé dans le dossier du projet.</p>

  <p style="color:#111827;">Cette opération a été réalisée à l’aide de la commande suivante :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">git init</code></pre>

  <p style="color:#111827;">L’initialisation crée automatiquement un dossier caché nommé <code style="color:#111827;">.git</code> à la racine du projet.</p>

  <p style="color:#111827;">Ce dossier contient toutes les informations nécessaires au fonctionnement de Git, notamment la configuration du dépôt ainsi que les futures données liées à l’historique des versions.</p>

  <p style="color:#111827;">À partir de cette étape, le projet est reconnu comme un dépôt Git et peut être versionné.</p>

  <h3 style="color:#111827;">Vérification de l’initialisation</h3>

  <p style="color:#111827;">Une fois le dépôt créé, la commande suivante a été utilisée afin de vérifier que Git reconnaissait correctement le projet :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">git status</code></pre>

  <p style="color:#111827;">Cette commande permet d’afficher l’état actuel du dépôt et de vérifier que les fichiers du projet sont bien détectés par Git avant leur premier enregistrement.</p>

  <h3 style="color:#111827;">Avantages du versionnage</h3>

  <p style="color:#111827;">L’initialisation du dépôt Git constitue la première étape de la mise en place du versionnage.</p>

  <p style="color:#111827;">Elle offre plusieurs avantages :</p>

  <ul>
    <li style="color:#111827;">préparation du projet au suivi des versions ;</li>
    <li style="color:#111827;">possibilité d’enregistrer l’historique des modifications ;</li>
    <li style="color:#111827;">préparation à la synchronisation avec GitHub ;</li>
    <li style="color:#111827;">adoption d’une méthode de travail utilisée dans le développement professionnel.</li>
  </ul>

  <h3 style="color:#111827;">Résultat</h3>

  <p style="color:#111827;">À la fin de cette étape :</p>

  <ul>
    <li style="color:#111827;">Le projet est organisé dans un dossier unique.</li>
    <li style="color:#111827;">Le projet est ouvert dans Visual Studio Code.</li>
    <li style="color:#111827;">Un dépôt Git valide est initialisé.</li>
    <li style="color:#111827;">Git reconnaît correctement le projet.</li>
    <li style="color:#111827;">Le projet est prêt à recevoir son premier commit.</li>
  </ul>
</div>
