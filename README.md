# PokéApp

PokéApp est une application mobile sur les Pokémons, reliée à une API (PokéApi) à l’aide de la 
technologie cross platform Xamarin Forms en respectant le pattern MVVM (Model – View – ViewModel).

***

# Présentation 

Cette application est composée d’un menu de quatre onglets : 

- **PokéApp :** Contient la page d’accueil de l'application.
- **Pokédex :** Contient une liste de 50 pokémons récupérées depuis l’API.
- **PokéNew :** Permet d’ajouter un pokémon en entrant ses diverses caractéristique.
- **PokéDeck :** Contient une liste des pokémons favories.

Si l’application est à sa première installation alors à son démarrage, elle va aller récupérer
50 pokémons dans l’API et les enregistrent en base de données. Par la suite tous les
pokémons ajoutés via « PokéNew » seront enregistrés en base de données.
Lors de la fermeture et la réouverture de l’application les 50 pokémons ainsi que les
pokémons ajoutés par l’utilisateur vont apparaître dans la « Pokédex ».

***

# Rendu visuel
## I- PokéApp
PokéApp contient la page d’accueil de l'application. Celle-ci possède un titre, un logo et une description :

<img src="./image/accueil.png">

## II- Pokédex
Pokédex contient une liste des 50 premiers pokémons récupérées depuis l’API. On affiche le nom du pokémon,
avec son image associée, ses différents types ainsi que son rang :

<img src="./image/list.png">

On peut également effectuer une recherche. On recherche ici le pokémon "Dracaufeu" :

<img src="./image/recherche.png">

Si on clique sur le pokémon, alors on a accès à sa page de détail contenant les diverses caractéristiques 
relatives au pokémon séléctioné : 

<img src="./image/detail.png">


## III- PokéNew
PokéNew permet d’ajouter un pokémon en entrant ses diverses caractéristique. Dans un premier temps, on rentre
son image (pour cela , il suffit de cliquer sur la pokéball) : 

<img src="./image/ajout%20image.png">

On accède ainsi à notre galerie photo : 

<img src="./image/acces%20photo.png">

On sélectionne ensuite l'image souhaitée :

<img src="./image/selection%20de%20la%20photo.png">

On obtient ensuite son rendu : 

<img src="./image/rendu%20photo.png">

Ensuite, on rempli les caractéristiques de notre pokémon à savoir son nom, sa description, 
sa taille et son poids : 

<img src="./image/caractéristiques.png">

Puis, comme lors du premier ajout, on ajoute sa forme shiny (son évolution) : 

<img src="./image/forme%20shiny.png">

Ensuite, il nous faut sectionner son type. En effet, il existe 18 types de pokémons (Roche, Spectre,
Acier, Eau, Plante, Psy, Glace, Tenebre, Fée, Normal, Combat, Vol, Poison, Sol, Insecte, Feu, 
Electrik, Dragon). De plus un pokémon peut avoir jusqu'à deux types : 

<img src="./image/type.png">

<img src="./image/selection%20du%20type.png">

Enfin on ajoute les statistiques (varie de 0 à 250) du pokémon à savoir sa vie, sa puissance d'attaque,
sa défense, la puissance de son attaque sépciale, sa défense spéciale et enfin sa vitesse : 

<img src="./image/rendu%20type.png">

<img src="./image/state.png">

Si tous les champs ne sont pas remplis (à part le type2 qui est facultatif), alors un message d'erreur s'affiche :

<img src="./image/champs%20Requis.png">

Une fois les champs remplies, on ajoute le pokémon. Un pop-up de confirmation s'affiche alors :

<img src="./image/ajout%20ok.png">

On peut ensuite le visualiser à la fin de la liste dans le "Pokédex" : 

<img src="./image/ajout%20à%20la%20liste.png">

On peut également accèder à sa page de détail : 

<img src="./image/ellie%20detail.png">
 
## IV- PokéDeck

PokéDeck contient une liste des pokémons favories. Pour en ajouter un, il suffit de cocher le 
pokémon souhaité en consultant sa page de détail : 

<img src="./image/ajoutPokedeck.png">

Le pokémon s'est bien ajouté au PokéDeck :

<img src="./image/Poké%20deck.png">






