# ProjetFinal
Travail P85 ISI MTL
Membres : Charles-Élie Bédard, Francis Veilleux, Jorel Amthor

Lien des images de BG :
- http://jorelamthor.neocities.org/BG_Accueil.png > BG page d'acceuil
- http://jorelamthor.neocities.org/BG_Mac.PNG > BG page Mac
- http://jorelamthor.neocities.org/BG_Windows.png > BG page Windows

----- 14/03/2015:

Jorel : http://codepen.io/anon/pen/YPdWWO - Ajout d'un pied de page

Concept général :

-Width de 960 px. height à confirmer
-Bannière sur chaque page, en lien avec la page. Chaque bannière doit être placé au même endroit sur toute les
pages et doit contenir, SAUF pour la page acceuil : un logo en lien avec la page aligné a droite
et le nom de la page a gauche. Le logo doit " flotter " par dessus la zone de la bannière.
Pied de page identique sur chaque page.
La barre de navigation doit se retrouver en dessous de la bannière d'en-tête, les boutons doivent donc avoir un height
conséquent. ( À voir sur le rendu final )
Le contenu de la page doit s'aligner a gauche et a droite avec la dimension de la banniere, la barre de navigation va
donc dépasser un petit peu de chaque côté.
La bannière ne doit pas coller aux bords de la page en haut, mais le pied de page doit absolument coller aux bords de la
page en bas ( 0 margin, 0 padding )
Le texte dans les pages mac, windows et linux doivent s'afficher dans une zone au survol des bouton image correspondant,
et doivent rester en place si l'utilisateur clique dessus ( sur la page windowsaccueil.html classwindows8:hover divContenuW8 {visibility: visible;}
et sur une autre page windows
classwindowsXP:hover divContenuW8 {visibity: hidden;) divContenuWXP {visibility: visible;}

Concept Acceuil, même chose que pour le reste sauf :
3 logo des 3 OS sur la banniere, pas de texte.
3 div pour chacun des OS avec une image pour chaque OS, séparé.
Un paragraphe par div avec un ol de 2 li de caractéristique majeure, une courte discription, et un bouton/lien ( A voir )
genre " >> En savoir plus " qui mène sur les pages des OS ( l'acceuil sert comme un genre de newsfeed pour chaque OS )

