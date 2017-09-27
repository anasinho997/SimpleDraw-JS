# simpledraw

 Trois boutons radio: un pour "Dessiner" (sélectionné initialement), un pour faire une "Sélection en rectangle", et un pour "Déplacer la sélection".

Lorsque le bouton "Dessiner" est sélectionné, un glissement avec la souris dessine un trait d'encre.

Lorsque le bouton "Sélection en rectangle" est sélectionné, l'utilisateur sera capable de faire un glissement pour sélectionner tous les traits d'encre dans le rectangle entre le point de départ et le point final du glissement. Un retour visuel montre le rectangle pendant le glissement, et par la suite un autre retour visuel montre les traits d'encre sélectionnés au moment du relâchement. À chaque fois que l'utilisateur effectue une sélection en rectangle, les traits anciennement sélectionnés sont déselectionnés par le systéme, pour permettre à l'utilisateur de recommencer une nouvelle sélection de zéro.

- Lorsque le bouton "Déplacer la sélection" est sélectionné, un glissement par l'utilisateur fait déplacer tous les traits sélectionnés de la même distance et dans la même direction que le curseur de souris.  (Check it here) => https://media.giphy.com/media/26vIdxry5sfkiBEha/giphy.gif


- Lorsque le bouton radio "Dessiner" est sélectionné, et la case à cocher "Symétrie" est cochée, tout nouveau trait dessiné crée (en même temps que son glissement) un deuxième trait réfléchi autour d'un axe vertical passant par le milieu du Canvas. (check it here) => https://media.giphy.com/media/xT9IgNCL0O7ae7nvHy/giphy.gif
