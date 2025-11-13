2. **Quelle est la différence entre `git fetch` et `git pull` ?**
    - Donnez un exemple concret où l’un est préférable à l’autre.

Reponse de Noah Pivetal : 
    
La commande git fetch permet de récupérer les dernières mises à jour du dépôt distant sans modifier la branche locale.

Alors que le git pull télécharge ces mises à jour et les fusionne automatiquement avec la branche courante.

Par exemple si je veux voir les nouveaux commits de mon groupe sans risquer de casser mon code, j’utilise git fetch.Alors que si je veux simplement mettre ma branche à jour avec la version distante, j’utilise la commande git pull.