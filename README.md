# GitTraining
Repository use to support training

- Création d'un repository git
    - `git init [ *nom référenciel* ]`
- Ajout d'une nouvelle version
    1. `git add *filename*`
    2. `git commit -m "*message de version*"`
- Visualisation de l'historique
    - historique complet `git log`
    - historique avec message sur une seule ligne `git log --oneline`
    - historique des x dernières version `git log -x`
    - historique dans l'ordre chronologique (par défaut c'est l'ordre inverse) `git log --reverse`
- Visualisation des differences
    - avec la derniere version `git diff` 
    - en n'affichant que les noms de fichiers modifier `git diff --name-only
    - en affichant les status des fichiers 
        - A : Ajouté
        - C : Copié
        - D : supprimé (Deleted)
        - M : Modifié
        - R : Renommé
        - ...        
    - d'un fichier particulier `git diff *filename*`
    - avec 1 version spécifique `git diff *ref*`
    - entre 2 versions `git diff *ref1..ref2` (notez la différence si vous inversez l'ordre des références)
    - en affichant les statistiques graphiquement les seuls fichiers modifier `git diff --stat` 