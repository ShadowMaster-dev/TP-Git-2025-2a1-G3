3. **Expliquez la différence entre `git reset` et `git revert`.**
    - Décrivez une situation où utiliser l’un serait risqué.

La commande git reset permet de revenir à un état antérieur du dépôt en déplaçant le pointeur HEAD et, selon l’option utilisée, en supprimant les commits suivants. Elle modifie donc l’historique.

À l’inverse, git revert crée un nouveau commit qui inverse les modifications d’un ou plusieurs commits précédents sans altérer l’historique.

Utiliser git reset est risqué sur une branche partagée, car cela peut effacer des commits déjà poussés et perturber le travail des autres développeurs. Dans ces cas, git revert est la solution la plus sûre.