# Changelog www.france-universite-numerique.fr


## 2.11 23/04/2015
- Merge edX au 31 mars 2015 + hotfixes
- Dashboard de répartition des réponses au quizz: affichage du plan sous forme d'arbre
    - affichage des distributions sous forme de camembert
- Dashboard enseignant de statistiques d'activité du wiki
- Backoffice: Optimisation du temps d'affichage de la liste des cours
- ORA2: possibilité de téléverser des images
- Bugfixes
    - liens conversations sur le profile utilisateurs forum
    - traductions
    - La prévisualisation de la page de news n'affiche plus l'article en cours de rédaction en double


## 2.10 09/03/2015
- Refactorisation du code permettant la consultation de la répartition des réponses aux quizz
- Ajout d'un commande permettant de désinscrire en masse des utilisateurs d'un cours
- Ajout à l'admin Django des exclusions temporaires: LoginFailures
- Ajout à l'admin Django des résultats de tâches Celery: TaskMeta et TaskSetMeta
- Bugfix stats utilisateurs du forum


## 2.9  26/03/2015
- Mise à jours edx-platform au 10 mars 2015
- Le xblock DMCloud supporte mieux les erreurs d'ID video (plus de blocage)
- Tri des cours par date dans le backoffice cellule d'appui
- Dans le forum, support des cohortes et de la validation des réponses par l'équipe pédagogique
- Les stats du forum pointent vers le profil l'utilisateur le plus actif
- Le dashboard enseignant permet maintenant aux enseignants d'ajouter des élèves aux cohortes


## 2.8 12/03/2015
- Téléchargement des résultat de quizz en CSV depuis le dashboard enseignant
- Flux RSS des cours disponibles
- Statistiques inscriptions, géographiques et forum au niveau globales (CA)
- Le téléchargement des réponses à l'évaluation par les pairs est maintenant asynchrone
- Les settings de développement sont maintenant dans le dépôt public `fun-apps`
- Refonte de l'organisation des settings par environnement: production dépôt privé `fun-config` et développement dépôt public `fun-apps`
- Bugfixes


## 2.7 26/02/2015
- Mise à jours edx-platform au 13 février 2015 (Aspen rc3)
- Modification du thème FUN pour être plus proche du thème edx; Largeur et menu du courseware
- Statistiques géographiques d'inscriptions par cours
- Téléchargement des réponses à l'évaluation par les pairs
- Export de la liste des cours au format CVS (CA)
- Bugfixes


## 2.6 5/02/2015
- Statistiques inscriptions, géographique et forum par cours pour l’équipe pédagogique.
- Génération d'un certificat de test (CA)

