# Exercice Markdown : La Recette des Crêpes
## Ingrédients principaux
### Pour environ 12 à 15 crêpes, vous aurez besoin de :
	- 250g de farine de blé (type 45)
	- 4 œufs frais
	- 50cl de lait entier ou demi-écrémé
	- 1 pincée de sel
	- 2 cuillères à soupe de sucre (optionnel pour les crêpes sucrées)
	- 50g de beurre fondu

### Étapes de préparation
```mermaid
 stateDiagram-v2

    state "mettre la farine dans un contenant" as s1   
    state "ajout des oeufs" as s2
    state "lait" as e1
    state "melange du lait" as s3
    state "beure" as e2
    state "ajout du beure" as s5
    state "repos 30min" as s6
    state "yolo" as yolo
    state "melange a sec" as b1
    state "fin des crepes" as s7

    state b1 {
        s1 --> s2
        s2 --> s3
        s3 --> s5
        s5 --> s6
        s6 --> yolo
        e1 -->s3
        e2 --> s5
    }
    yolo --> s7
    s7 --> s1


```

Mélange à sec : Versez la farine et le sel dans un saladier. Creusez un puits au centre.
Ajout des œufs : Cassez les œufs un par un au milieu du puits.
Liquides : Commencez à mélanger doucement avec un fouet en ajoutant le lait progressivement pour éviter les grumeaux.
Finition : Ajoutez le beurre fondu et mélangez jusqu'à obtenir une pâte fluide.
Repos : Laissez reposer la pâte environ 30 minutes à température ambiante.
Astuces pour réussir
Le secret d'une crêpe sans grumeaux est de verser le lait très lentement au début en partant du centre.
Si la pâte est trop épaisse, n'hésitez pas à rajouter un petit filet d'eau ou de bière (pour plus de légèreté).
Tableau des garnitures populaires
Type	Garniture	Popularité
Sucré	Sucre || Miel	Incontournable
Sucré	Pâte à tartiner	Préféré des enfants
Salé	Oeuf & Jambon	Classique
Voici une recette autre recette marmiton


<!-- mettre une image de crêpe -->
<!-- [img_crepe_saler]: -->
<!-- [img_crepe_sucre]: -->
<!-- avoir un lien vers une recette marmiton -->
<!-- [link_marmiton]: -->
<!-- faire un mermaid avec la liste de courses https://mermaid.live/ -->
