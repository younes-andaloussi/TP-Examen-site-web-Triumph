<div style="background:#f8fafc; color:#111827; padding:24px; border-radius:10px; border:2px solid #2563eb;">
  <h1 style="margin:0 0 10px 0; color:#111827;">Tutoriel Git et GitHub</h1>
  <p style="margin:0; color:#111827;">Cette documentation explique les étapes de versionnage du projet et sa préparation à la publication en ligne.</p>
</div>

<div style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:18px; margin-top:20px;">
  <h2 style="margin-top:0; color:#111827;">Sommaire des étapes</h2>
  <ul>
    <li style="color:#111827;"><a href="#etape-1--initialisation-du-depot-git" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 1 — Initialisation du dépôt Git</a></li>
    <li style="color:#111827;"><a href="#etape-2--premier-commit-du-projet" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 2 — Premier commit du projet</a></li>
    <li style="color:#111827;"><a href="#etape-3--creation-du-depot-github-et-synchronisation-du-projet" style="color:#1d4ed8; font-weight:700; text-decoration:underline;">Étape 3 — Création du dépôt GitHub et synchronisation du projet</a></li>
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

<div id="etape-2--premier-commit-du-projet" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 2 — Premier commit du projet</h2>

  <h3 style="color:#111827;">Objectif</h3>

  <p style="color:#111827;">Une fois le dépôt Git initialisé, il est nécessaire d’effectuer un premier enregistrement du projet. Cette opération est appelée <strong style="color:#111827;">commit</strong>.</p>

  <p style="color:#111827;">Un commit représente une sauvegarde de l’état du projet à un instant précis. Il permet de conserver une version de référence du site et constitue le point de départ de l’historique des modifications.</p>

  <p style="color:#111827;">À partir de ce moment, chaque évolution du projet pourra être enregistrée sous la forme d’un nouveau commit, facilitant ainsi le suivi du développement.</p>

  <h3 style="color:#111827;">Ajout des fichiers au suivi Git</h3>

  <p style="color:#111827;">Avant de pouvoir créer un commit, Git doit savoir quels fichiers doivent être intégrés au dépôt.</p>

  <p style="color:#111827;">L’ensemble des fichiers du projet est ajouté au suivi à l’aide de la commande suivante :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">git add .</code></pre>

  <p style="color:#111827;">Le point <code style="color:#111827;">.</code> indique à Git d’ajouter tous les fichiers et dossiers présents dans le répertoire courant.</p>

  <p style="color:#111827;">Cette commande ne crée pas encore de sauvegarde. Elle prépare simplement les fichiers qui feront partie du prochain commit.</p>

  <h3 style="color:#111827;">Création du premier commit</h3>

  <p style="color:#111827;">Une fois les fichiers ajoutés, le premier commit est créé avec la commande suivante :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">git commit -m "Initial commit - Site Triumph terminé"</code></pre>

  <p style="color:#111827;">Le paramètre <code style="color:#111827;">-m</code> permet d’associer un message descriptif au commit.</p>

  <p style="color:#111827;">Le message utilisé est :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">Initial commit - Site Triumph terminé</code></pre>

  <p style="color:#111827;">Ce premier commit représente la version initiale complète du site web.</p>

  <p style="color:#111827;">Il constitue la première référence de l’historique Git.</p>

  <h3 style="color:#111827;">Vérification du commit</h3>

  <p style="color:#111827;">Après la création du commit, la commande suivante permet de vérifier que le dépôt est propre :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">git status</code></pre>

  <p style="color:#111827;">Si toutes les opérations ont été effectuées correctement, Git affiche un message similaire à :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">On branch main

nothing to commit, working tree clean</code></pre>

  <p style="color:#111827;">Ce message confirme que tous les fichiers sont enregistrés dans le dépôt et qu’aucune modification n’est en attente.</p>

  <h3 style="color:#111827;">Importance du premier commit</h3>

  <p style="color:#111827;">Le premier commit marque le début de l’historique du projet.</p>

  <p style="color:#111827;">À partir de cette version, il devient possible de :</p>

  <ul>
    <li style="color:#111827;">conserver un historique complet des évolutions du site ;</li>
    <li style="color:#111827;">comparer différentes versions du projet ;</li>
    <li style="color:#111827;">revenir à une version précédente en cas d’erreur ;</li>
    <li style="color:#111827;">documenter précisément chaque modification apportée au code.</li>
  </ul>

  <p style="color:#111827;">Cette méthode de travail est utilisée quotidiennement dans les projets de développement professionnels.</p>

  <h3 style="color:#111827;">Résultat</h3>

  <p style="color:#111827;">À la fin de cette étape :</p>

  <ul>
    <li style="color:#111827;">Tous les fichiers du projet sont suivis par Git.</li>
    <li style="color:#111827;">Le premier commit est créé.</li>
    <li style="color:#111827;">Une première version stable du site est enregistrée.</li>
    <li style="color:#111827;">Le projet est prêt à être synchronisé avec un dépôt GitHub.</li>
  </ul>
</div>

<div id="etape-3--creation-du-depot-github-et-synchronisation-du-projet" style="background:#ffffff; color:#111827; border:2px solid #d1d5db; border-radius:10px; padding:22px; margin-top:24px;">
  <h2 style="margin-top:0; color:#111827;">Étape 3 — Création du dépôt GitHub et synchronisation du projet</h2>

  <h3 style="color:#111827;">Objectif</h3>

  <p style="color:#111827;">Après avoir créé le premier commit, le projet est prêt à être publié sur <strong style="color:#111827;">GitHub</strong>.</p>

  <p style="color:#111827;">GitHub permet d’héberger le dépôt Git en ligne afin de sauvegarder le projet, d’accéder à son historique depuis n’importe quel ordinateur et de faciliter les futures mises à jour.</p>

  <p style="color:#111827;">Cette étape consiste à créer un dépôt distant puis à le relier au dépôt Git local.</p>

  <h3 style="color:#111827;">Création du dépôt GitHub</h3>

  <p style="color:#111827;">Après s’être connecté à son compte GitHub, un nouveau dépôt a été créé.</p>

  <p style="color:#111827;">Les informations suivantes ont été renseignées :</p>

  <ul>
    <li style="color:#111827;"><strong style="color:#111827;">Nom du dépôt :</strong> TP-Examen-Triumph, ou le nom choisi pour le projet ;</li>
    <li style="color:#111827;"><strong style="color:#111827;">Visibilité :</strong> Public ;</li>
    <li style="color:#111827;"><strong style="color:#111827;">Description :</strong> présentation du projet, facultative.</li>
  </ul>

  <p style="color:#111827;">Lors de la création du dépôt, aucune initialisation automatique, comme un fichier README, une licence ou un fichier <code style="color:#111827;">.gitignore</code>, n’a été sélectionnée.</p>

  <p style="color:#111827;">Cette précaution permet d’éviter tout conflit avec le dépôt Git déjà créé localement.</p>

  <h3 style="color:#111827;">Liaison entre le projet local et GitHub</h3>

  <p style="color:#111827;">Une fois le dépôt GitHub créé, celui-ci a été associé au projet local.</p>

  <p style="color:#111827;">Cette opération établit un lien entre le dépôt présent sur l’ordinateur et le dépôt hébergé sur GitHub.</p>

  <p style="color:#111827;">La liaison est réalisée avec la commande suivante :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">git remote add origin https://github.com/NOM_UTILISATEUR/NOM_DU_DEPOT.git</code></pre>

  <p style="color:#111827;">Le terme <code style="color:#111827;">origin</code> désigne le dépôt distant principal avec lequel le projet sera synchronisé.</p>

  <h3 style="color:#111827;">Vérification du dépôt distant</h3>

  <p style="color:#111827;">Afin de vérifier que la liaison a été correctement établie, la commande suivante a été utilisée :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">git remote -v</code></pre>

  <p style="color:#111827;">Cette commande affiche l’adresse du dépôt distant utilisé pour les opérations d’envoi, avec <code style="color:#111827;">push</code>, et de récupération, avec <code style="color:#111827;">pull</code>.</p>

  <h3 style="color:#111827;">Premier envoi vers GitHub</h3>

  <p style="color:#111827;">Une fois la connexion établie, le premier envoi du projet a été effectué grâce à la commande :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">git push -u origin main</code></pre>

  <p style="color:#111827;">L’option <code style="color:#111827;">-u</code> définit la branche <code style="color:#111827;">main</code> comme branche de suivi par défaut.</p>

  <p style="color:#111827;">Ainsi, lors des prochaines mises à jour, la commande suivante suffira :</p>

  <pre style="background:#f3f4f6; color:#111827; padding:12px; border-radius:8px; border:1px solid #9ca3af; overflow:auto;"><code style="color:#111827;">git push</code></pre>

  <p style="color:#111827;">Toutes les modifications enregistrées par de nouveaux commits pourront alors être publiées automatiquement sur GitHub.</p>

  <h3 style="color:#111827;">Intérêt de la synchronisation</h3>

  <p style="color:#111827;">La synchronisation avec GitHub présente plusieurs avantages :</p>

  <ul>
    <li style="color:#111827;">sauvegarde du projet sur une plateforme distante ;</li>
    <li style="color:#111827;">partage du code source ;</li>
    <li style="color:#111827;">conservation de l’historique des versions ;</li>
    <li style="color:#111827;">possibilité de travailler depuis plusieurs ordinateurs ;</li>
    <li style="color:#111827;">préparation à la publication du site avec GitHub Pages.</li>
  </ul>

  <p style="color:#111827;">Cette méthode correspond au workflow utilisé dans la majorité des projets professionnels.</p>

  <h3 style="color:#111827;">Résultat</h3>

  <p style="color:#111827;">À la fin de cette étape :</p>

  <ul>
    <li style="color:#111827;">Un dépôt GitHub est créé.</li>
    <li style="color:#111827;">Le projet local est relié au dépôt distant.</li>
    <li style="color:#111827;">La première version du site est publiée sur GitHub.</li>
    <li style="color:#111827;">Les futures modifications pourront être envoyées simplement à l’aide de nouveaux commits suivis d’un <code style="color:#111827;">git push</code>.</li>
  </ul>
</div>
