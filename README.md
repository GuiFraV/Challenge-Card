# Challenge-Card

Le but de ce challenge était de faire une page web via une maquette.

Languages utilisées :
HTML/CSS

Difficulté: 
Flex-box

Tout d'abord j'ai reset le css en utilisant le sélecteur universel "*" et en mettant la margin et le padding à 0, et le box-sizing en border-box. 

Ensuite j'ai placé dans le body l'image que l'on voit en arrière plan (la vague bleu). Pour ce faire j'ai mis dans le CSS un background-size: contain; et un background-repeat: no repeat; afin de m'assurer que l'image ne se répète pas et qu'elle soit entièrement comprise dans la largeur du body. 

Pour place l'élément card au centre de la page html j'ai mis dans l'élément parent (le body) une hauteur de 100vh pour prendre entièrement l'écran puis un display : flex me permettant de manipuler la #card. Pour la centrer j'ai utilisé les attributs justify-content: center; et align-items: center;.

La card est définit avec un background-color blanc une hauteur de 600px et une largeur de 400px. Les border-radius ont était définit à 7px. 

Afin de centrer les éléments à l'intérieur de la card j'ai utilisé un display flex que j'ai placé en colonne. 
Pour la partie image de la card j'ai utilisé une hauteur de 30% avec un background-size: cover; et un background-position: center center;. De plus, pour éviter d'avoir des border radius sur le bas de l'image j'ai utilisé les attributs border-top-left-radius et border-top-right-radius à 7px;.

L'order Summary, le lorem ipsum, l'annual plan, le proceed to payment et le cancel order ont étaient chacun placés dans des div individuelles. Ceci afin de centrer le tout via les attributs justify-content: center; space-around et align-items: center;. Ces attributs permettent de centrer sur l'axe vertical et horizontal.  

Bonus:
:hover
text-decoration
box-shadow

Résultat final :

<img width="1222" alt="ResultatChallenge" src="https://user-images.githubusercontent.com/91052075/136995917-f3168213-b54b-476f-a4b5-66c0208fa9c2.png">
