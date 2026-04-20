# Glossaire Gestion de Projet 

## Cahier des charges (CDC)
Document qui décrit le besoin du client : contexte, objectifs, parties prenantes, besoins fonctionnels, contraintes et priorisation. C’est le point de départ de l’analyse fonctionnelle et organisationnelle.  

## Grille fonctionnelle – « le quoi »
Lecture du CDC centrée sur ce que le système doit faire : grandes fonctionnalités, parcours utilisateurs, données manipulées, IN/OUT, méthode de priorisation (ex. MoSCoW) et zones floues. Sert de base au PBS.  

## Grille organisationnelle – « le qui »
Lecture du CDC centrée sur les acteurs : parties prenantes, qui décide, qui utilise, qui paie, niveaux de pouvoir et d’autonomie, tensions entre acteurs. Sert de base à l’OBS.  

## C4 Model (Context / Container / Component / Code)
Modèle de niveaux de zoom :  
- C1 Context : vision globale du système dans son environnement (note de cadrage).  
- C2 Container : grands blocs (produits, services) = PBS / OBS.  
- C3 Component : lots de travail concrets = WBS / RACI.  
- C4 Code : tâches techniques, user stories, tickets.  

## Note de cadrage
Synthèse courte au niveau C1 : pourquoi le projet existe, pour qui, périmètre IN/OUT, principaux livrables et jalons, contraintes clés, parties prenantes majeures. Sert de base commune à tout le monde au lancement.  

## PBS – Product Breakdown Structure
Découpage du projet par livrables (ce qu’on livre) au niveau Container : grands blocs comme « Vitrine publique », « Intranet », « Base de données », « Infrastructure », « Mise en route ». Chaque bloc reste une « boîte noire ».  

## OBS – Organization Breakdown Structure
Découpage par acteurs (qui est impliqué) : collectif MJC, CA, équipes salariées, bénévoles, publics, prestataire… On précise leurs rôles, niveaux de décision et intérêts.  

## WBS – Work Breakdown Structure
Découpage du travail en lots concrets au niveau Component : chaque lot est un résultat tangible (écran, module, script, environnement…), pas une tâche du type « écrire », « configurer ». Le WBS descend à l’intérieur des blocs du PBS.  

## RACI
Matrice qui croise WBS (lignes) et OBS (colonnes) pour clarifier les responsabilités :  
- R = Responsible (réalise le travail)  
- A = Accountable (décide / valide)  
- C = Consulted (consulté avant)  
- I = Informed (informé après)  

## Dépendance entre lots
Lien logique entre deux lots du WBS : un lot ne peut pas commencer ou finir tant qu’un autre n’a pas commencé ou fini. Types vus :  
- FD (Fin–Début) : le plus courant, B commence quand A finit.  
- DD (Début–Début) : A et B démarrent ensemble.  
- FF (Fin–Fin) : A et B doivent finir ensemble.  

## Chemin critique
Suite de lots dépendants qui donne la durée minimale du projet. C’est le chemin le plus long dans le diagramme de dépendances. Tout retard sur un lot du chemin critique décale la date de fin du projet.  

## Marge
Temps pendant lequel un lot peut glisser sans retarder la date de fin globale. Les lots sur le chemin critique ont une marge de 0. Les autres peuvent avoir quelques jours de marge.  

## Approche prédictive
Approche où on planifie beaucoup en amont, avec un périmètre et un planning assez figés (cycle en V). Adaptée quand le besoin est stable, bien défini, et que les changements sont rares.  

## Approche agile (Scrum)
Approche itérative en sprints courts avec revues régulières et backlog priorisé. Adaptée quand le besoin est incertain ou évolutif (ex. e‑commerce du chocolatier), et qu’on veut absorber les changements progressivement.  

## Approche hybride
Combinaison de prédictif et d’agile : certaines parties du projet sont cadrées et planifiées de façon rigide, d’autres sont gérées en itérations. Utile quand il y a des contraintes fortes (réglementaires, techniques) mais aussi des zones de forte incertitude.  

## MVP – Minimum Viable Product
Version minimale du produit qui permet déjà d’apporter de la valeur (ex. panier + paiement avant Noël pour le chocolatier), quitte à améliorer le design ou les fonctionnalités secondaires plus tard.  

## Perturbation / imprévu
Événement qui vient bousculer le plan (budget réduit, délai raccourci, retrait d’un partenaire, changement de techno…). Sert de base à la revue croisée : on évalue l’impact sur le chemin critique et on propose des arbitrages.  

## Boîte noire (réflexe de zoom)
Principe qui consiste à ne pas tout détailler d’un coup : à chaque niveau (Context / Container / Component), le niveau en dessous reste une « boîte fermée » qu’on n’ouvre que si c’est utile pour l’interlocuteur.  

## IN / OUT
Façon de cadrer le périmètre :  
- IN = ce qui est explicitement inclus dans le projet.  
- OUT = ce qui n’est pas prévu ou trop flou pour cette phase.  
On teste : « si on ne le fait pas, que se passe-t-il ? » pour trancher.  

## MoSCoW
Méthode de priorisation des besoins :  
- Must : indispensable.  
- Should : important mais pas vital.  
- Could : nice to have.  
- Won’t (ou Would) : explicitement hors périmètre pour maintenant.  