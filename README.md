# ProjetFinal
Travail P85 ISI MTL
Membres : Charles-Élie Bédard, Francis Veilleux, Jorel Amthor

TEMPORAIRE
Lien des images de BG :
- http://jorelamthor.neocities.org/BG_Accueil.png > BG page d'acceuil
- http://jorelamthor.neocities.org/BG_Mac.PNG > BG page Mac
- http://jorelamthor.neocities.org/BG_Windows.png > BG page Windows
Jorel : http://codepen.io/anon/pen/YPdWWO - pied de page
/TEMPORAIRE

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
=====================================================================================================
Légende du mockup( de haut en bas )

En vert transparent : les images de la banniere.
Elles sont situé a 20px du haut de la page et a -75px du haut de la banniere. La premiere est situé a 87.5 px a gauche
de la banniere ( left 87.5 top -75 ), la seconde est situé a 87.5px de la premiere image ( left 325 top -75 ) et la
derniere est située a 87.5 pixel de celle d'avant, ainsi qu'à 87.5px du bord droit de la banniere ( left 562.5 top -75 ).
Elles sont donc toutes espacés de 87.5 px. Taille : w150*h150

En bleu foncé : La bannière
Elle est situé a 60px a gauche du bord de la page et a 90px du top ( left 60 top 90). w800*h130

En noir : les boutons de navigations
Ils sont situés a 35px a gauche du bord de la page et a 205px du top. w850*h45

Le deuxieme wrapper c'est pas important car c'est propre au design de la page d'accueil, qui est unique, mais pour
le fun, je vous explique quand même; En beige clair c'est le 2eme wrapper a 10 px de la navibarre et a 10px du bord gauche
de la page ( c'est voulu qu'il soit dans le wrapper global ) il contient :

En rouge : L'espace dédié aux 3 paragraphe des 3 OS. ils sont espacé de 10px l'un de l'autre, et de 10px du bord
gauche de la page. Le premier est collé en haut a gauche du wrapper et tout les autres sont en fonction du wrapper
( absolu ). w900*h220

En vert transparent : Les images des 3 paragraphe des 3 OS. Ils sont collé a gauche de l'espace dédié aux paragraphes
( donc ils héritent du 10 px du bord gauche de la page ). Ils sont espacés de 10px les unes des autres. w250*h220

En doré : Le paragraphe, la zone d'écriture qui contiendra le blabla. ils sont a 250px de la zone dédié, et a 20 pixel
de la zone qui leur est dédié ( donc en gros 20px d'eloignement ( en rouge ) + 10px d'espace entre les zones ( en beige )
+ 20px avant l'autre texte ( en rouge encore ) = 50px d'ecart entre 2 paragraphes )( left 250 top 20 ). w650*h180

En noir en bas : Le pied de page. Il est a -50px en bas et a -10px a gauche du wrapper2 ( en rouge ).
Il est espacé de 10px avec le dernier paragraphe. w920*h60.

Vous avez juste a faire vos page en incluant dans toute : Banniere, Image de banniere, Navigation & Pied de page.
Vous pouvez evidement réutiliser mes <div> et le CSS correspondant, tout est écrit logiquement, vous devriez
pas avoir de mal a vous retrouver :)