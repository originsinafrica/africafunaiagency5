# Import complet et ajustements Africafun AI Agency

## Résultat attendu
- Reprendre entièrement le site du dépôt GitHub sur la page d’accueil, avec ses contenus, interactions, styles et sections.
- Utiliser les quatre images fournies comme fichiers officiels du site, sans les recréer.
- Appliquer les trois ajustements demandés sans modifier le reste de l’identité visuelle.

## Modifications
1. **Import fidèle**
   - Reprendre la page complète, la navigation, les fiches interactives, la carte d’infrastructure, les horizons, les univers et le pied de page.
   - Conserver les polices, couleurs, textes, animations et interactions existantes.
   - Stocker les images fournies dans les ressources du projet et les relier aux emplacements correspondants.

2. **Images sur mobile**
   - Adapter l’image d’ouverture pour garder les personnages et le trésor visibles sur petit écran.
   - Recomposer les cartes « Zemzem » et « Les Trésors » afin que les images aient une hauteur naturelle et que les textes ne les masquent plus sur téléphone.
   - Recadrer l’image des trois statues pour préserver les trois personnages en format étroit.

3. **Constellation sur mobile**
   - Remplacer le large plan à défilement horizontal par une version compacte occupant la largeur du téléphone.
   - Garder les trois anneaux, les connexions et tous les nœuds, mais alléger les libellés dans le dessin pour qu’ils restent lisibles.
   - Agrandir les zones tactiles et afficher le nom, le rôle et les connexions dans la fiche sous la carte après sélection.
   - Conserver la version détaillée actuelle sur tablette et ordinateur.

4. **Corrections graphiques demandées**
   - Retirer « LE », « ST » et « RO » des trois cercles blancs des conseillers, tout en gardant les cercles cliquables.
   - Passer la section « Cercle 3 · Infrastructure créative » en bleu.
   - Passer la section « Message global » en bleu, avec des contrastes adaptés pour préserver la lisibilité.

## Vérification
- Contrôler la page complète sur téléphone et ordinateur.
- Tester la sélection des nœuds de la constellation et les fiches des huit intelligences.
- Vérifier que les quatre images s’affichent, que les textes ne se chevauchent pas et que la page se compile sans erreur.

## Détails techniques
- Le dépôt source utilise déjà la même base React/TanStack que le projet cible : aucune conversion fonctionnelle n’est nécessaire.
- Le site est statique et ne contient ni comptes utilisateurs, ni base de données, ni service externe à migrer.
- Les médias seront enregistrés comme ressources CDN du projet à partir des fichiers transmis.
