# Forum Berlingo
## Verrouillage centralisé
https://berlingoforum.com/thread-7251.html

*Traduit de l'anglais* [Original](../../../../en/cars/BerlingoI/CentralLocking)

**verrouillage centralisé** - *HansW* - `09-07-2013`

Salut
Mon partenaire de 2007 a le problème suivant :
Si j'appuie sur le bouton du porte-clés, il se verrouille (sauf la porte arrière) - si j'appuie sur le bouton de déverrouillage, rien ne se passe.
Si je tourne la clé dans la porte conducteur, pour verrouiller : la fermeture centralisée verrouille le reste des portes, (sauf la porte arrière).
Si je déverrouille la voiture avec la clé, seule la porte conducteur se déverrouille, les autres ne font rien. Il n'y a aucun clic.

J'ai démonté la porte arrière et j'ai mesuré les courants électriques.
Lors de la fermeture, je reçois une impulsion d'environ 9V entre les deux fils pendant environ 2-3 secondes.
A l'ouverture je n'en reçois aucun.

J'ai vérifié le solénoïde à l'extérieur de la voiture avec le chargeur de batterie, et cela fonctionne bien dans les deux sens, en changeant de polarité.

Ma question est:

Ces casiers électriques semblent essentiellement fonctionner de cette façon, c'est-à-dire que pour la fermeture et l'ouverture, la polarité est simplement inversée.
Dans l'ancienne génération de voitures, cette inversion était effectuée par le relais de verrouillage central.

dans les Berlingo's/partenaires, un tel relais existe-t-il et si oui où se trouve-t-il ?
Ou cette fonction est-elle intégrée au boîtier BSI et gérée électroniquement ?
Si c'est le cas, -- cela signifierait que le BSI est également défectueux, ---

**RE: verrouillage centralisé** - *mikeB* - `11-07-2013`

Salut. Mon Berlingo Multispace 2005 se comportait exactement comme le vôtre, c'est-à-dire qu'il se verrouillait mais ne se déverrouillait pas. La clé dans la porte du conducteur ne déverrouille que cette porte.
Le problème avec le mien était dans le BSI. Vous devez le supprimer complètement. Il existe un certain nombre de connecteurs multibroches, qui semblent tous différents. C'est une bonne chose dans la mesure où il est difficile de remonter de manière incorrecte, mais une mauvaise chose dans la mesure où ils se démontent tous différemment. Il faut être patient, surtout quand on travaille dans un si petit espace.

Tout d'abord, faites la procédure de déconnexion de la batterie (voir les autres discussions sur ce forum) puis retirez les connecteurs, puis retirez le BSI. Vous verrez que le BSI est contenu dans un boîtier en plastique en 2 parties. Retirez l'étui (nécessite des soins) qui laisse apparaître 2 planches l'une au-dessus de l'autre. Une carte contient l'ordinateur qui contient toute l'intelligence, l'autre a les relais qui font toutes les commutations et transportent les courants lourds nécessaires. Les cartes sont connectées par (de mémoire) 2 jeux de broches extensibles. Ces broches sont sujettes à un circuit ouvert, surtout si elles sont humides ou mouillées. Séparez les deux cartes (attention car elles sont délicates) et examinez minutieusement les broches et les douilles avec lesquelles elles s'engrènent. Assurez-vous qu'il n'y a aucune trace de corrosion dans les broches ou les douilles. Remonter à l'aide d'un lubrifiant électrique. J'ai utilisé le lubrifiant nettoyant pour interrupteurs Briggs SKL. Il empêche la corrosion et conduit l'électricité. Il y en a d'autres disponibles. Consultez le site Web du CPC (Farnell) pour plus d'informations à ce sujet.
Remontez soigneusement les cartes, puis les capots et réinsérez les connecteurs multibroches. J'étais ravi quand tout fonctionnait parfaitement. C'était il y a un an et ça marche toujours. J'espère que c'est le cas pour vous. Le problème était que les signaux de l'ordinateur n'atteignaient pas le relais qui ouvre les portes.

**RE : verrouillage centralisé** - *HansW* - `14-07-2013`

Merci Mike, - J'avais une idée similaire, mais j'ai maintenant une idée juste. Je dois y penser, - en termes de pire scénario, etc., mais cela semble être une chose faisable.
Je ferai rapport.
Je suis allé jusqu'à avoir les planches ici sur le bureau, mais je suis incapable de les séparer -- Ils semblent être liés ensemble, -- y a-t-il une astuce, et qu'est-ce que c'est pour les séparer sans endommager les planches ? le plastique noir reste-t-il avec le haut ou le bas ?
Entre-temps, j'ai découvert des traces d'oxydation sur une multiprise, j'ai donc nettoyé les broches et je vais maintenant voir, si c'était le problème, ---
Tous de retour, et pas d'amélioration,--

**RE: verrouillage centralisé** - *mikeB* - `14-07-2013`

Par plastique noir, je suppose que vous voulez dire les 2 couvercles. Je les ai trouvés assez difficiles à séparer, mais ils doivent être retirés pour révéler 2 cartes de circuits imprimés reliées entre elles par 2 jeux de broches expansibles.

Les cartes de circuits imprimés sont fixées de manière décalée, c'est-à-dire pas exactement les unes sur les autres. Sur le bord supérieur de la carte supérieure, celle contenant les relais et les fusibles, vous verrez 2 lignes de 8 broches, chacune à environ 4 cm du bord de la carte. Vous devez insérer un outil plat entre les planches et le tordre lentement et avec précaution pour séparer les planches. J'ai utilisé une règle en bois de 1 pouce d'épaisseur. Une fois séparés, vous pouvez voir sur le plateau inférieur les broches d'expansion. Ceux-ci doivent être examinés à la loupe pour s'assurer qu'il n'y a PAS de corrosion. Les prises sur la carte supérieure doivent également être examinées de près. Ensuite, vaporisez avec Briggs etc. et remontez soigneusement.

Si vous avez déjà fait tout cela il est possible que vous ayez un relais défaillant. Ceux qui contrôlent la fermeture centralisée sont YH119 012-1z11-1A. L'un commande le verrouillage, l'autre le déverrouillage. Vous pouvez appliquer 12 volts à la bobine et vous devriez l'entendre cliquer. Vous pouvez tester la résistance entre les broches de contact pour voir laquelle, le cas échéant, est défectueuse. J'ai recherché YH119 sur Google et j'ai obtenu la spécification complète avec les détails de la broche. C'est un peu fastidieux, mais cela devrait produire le résultat souhaité. L'obtention d'un relais est probablement mieux réalisée en achetant une planche de ferraille et en les transpirant. Ce n'est pas une tâche facile et il faut un fer à souder d'au moins 100 watts de puissance. Mais je mettrais de l'argent sur les broches reliant les cartes. Les relais sont robustes et passent rarement en circuit ouvert.

La meilleure chose à faire est donc de séparer les planches et de bien regarder la corrosion. Le simple fait de séparer et de reconnecter les planches pourrait bien suffire. Persévérer! Ça en vaut la peine. Une réflexion après coup - si vous ne pouvez pas séparer les planches, cela suggère que les broches SONT corrodées ensemble. Cela vaut donc vraiment la peine d'être examiné de très près. Il faut absolument les séparer.

Une autre réflexion - si vous avez trouvé de la corrosion sur une multiprise, c'est la preuve qu'elle a été mouillée à un moment donné. Les broches DOIVENT être suspectes. Une autre observation - lorsque le porte-clés a été cliqué pour ouvrir les portes, les lumières ont clignoté mais aucun bruit ne provenait des portes. De plus, le hayon ne se fermait pas du tout.

**RE : verrouillage centralisé** - *HansW* - `14-07-2013`

Salut Mike
Bon j'ai réessayé et réussi!!!

J'ai une deuxième unité complète, où il n'y a pas de dégâts d'eau, -- donc mon plan était simplement de prendre la carte de relais complète et de la coller sur ma carte d'ordinateur, --

Je l'ai fait entre-temps, -- tous ensemble et ça MARCHE !
Donc, merci pour l'aide ici.

**RE: verrouillage centralisé** - *mikeB* - `14-07-2013`

Votre stratégie est au rendez-vous. Une nouvelle carte servo serait un bon moyen.

Pour séparer les planches, je suggère un outil plat et souple, légèrement plus large que la distance entre les planches. Lorsqu'il est inséré près des broches, il doit être possible de tordre l'outil et de forcer les planches à s'écarter. Ils ne sont PAS collés ou soudés. Les goupilles expansibles sont juste un ajustement serré. La corrosion aura tendance à lier les planches ensemble. Un agent de démoulage doux comme le WD 40 pourrait aider. Il faudra le vaporiser avec parcimonie puis attendre quelques dizaines de minutes pour que cela agisse, puis réessayer. Ils VONT et DOIVENT se démonter pour vérifier la corrosion. Je suis sûr que vous trouverez que c'est la cause de votre problème.

PS Avez-vous essayé de séparer les cartes sur votre BSI de rechange. Bonne pratique je pense !

**RE : verrouillage centralisé** - *HansW* - `14-07-2013`

affichage croisé - bien sûr, j'ai d'abord séparé la carte de rechange, - j'ai un peu rayé l'un des circuits, mais je l'ai isolé avec de la colle, - puis j'ai séparé la deuxième carte, nettoyé les broches avec du papier de verre 400 et les ai vérifiées avec le loupe, -- mettre l'ancienne carte informatique sur la nouvelle carte relais, -- presser avec deux morceaux de bois tendre et les rapprocher le plus possible.
Nous verrons comment cela résiste à l'épreuve du temps!
A recommander !

**RE: verrouillage centralisé** - *mikeB* - `17-07-2013`

Bravo, et je soupçonne que vous avez le sourire aux lèvres. Mon agent principal Citroën local a eu ma voiture pendant une journée et n'a pas pu trouver la panne. Avec l'aide et un schéma de circuit de Rustcrat (l'un des contributeurs très utiles sur ce forum), je suis arrivé à la même conclusion que vous. Et le mien fonctionne toujours après un an. Si cela se reproduit, je sais où chercher.

En toute justice pour le garage Citroën, ils ne m'ont pas facturé