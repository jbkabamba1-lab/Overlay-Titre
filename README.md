Les deux fichiers sont overlay-intervenant et control-intervenant. Je les ai testés dans Chromium : le panneau commande bien l’overlay (affichage, masquage, préréglage) sans erreur JavaScript. Je ne les ai pas testés dans un vrai OBS.

Mise en place dans OBS

Mets les deux fichiers dans le même dossier.
Ajoute une source Navigateur, coche Fichier local, choisis overlay-intervenant.html, taille 1920×1080.
Ouvre le panneau avec Docks → Docks de navigateur personnalisés, avec l’URL file:///C:/ton/dossier/control-intervenant.html. Tu peux aussi l’ouvrir comme une page normale.

Si le panneau ne commande pas l’overlay, c’est probablement le partage de données entre les deux qui est bloqué dans ta version d’OBS. Dis-moi alors ce que tu observes.

Ce que tu peux régler

Contenu : nom, rôle et logo, plus une liste d’intervenants enregistrés. Un clic sur un nom le charge et l’affiche.
Graphisme :
deux modèles (carte avec liseré, ou nom sur fond de couleur) ;
les couleurs, la police, la forme du logo, les coins arrondis, la taille et la position (5 emplacements) ;
deux préréglages, Église et Commentateur.
Animation :
entrée et sortie choisies séparément : glissement, montée, fondu, zoom, rideau ou aucune ;
durée, type de mouvement et masquage automatique après N secondes ;
si un autre intervenant est déjà à l’écran, il sort avant que le nouveau n’entre.

Les réglages de style s’appliquent en direct. Le nom, le rôle et le logo ne partent à l’antenne qu’au clic sur Afficher, pour ne pas modifier le texte en cours de diffusion.

Les polices proposées sont celles déjà présentes sous Windows, donc aucune n’est chargée depuis Internet.
