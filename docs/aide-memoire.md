# Aide-mémoire du terminal Linux

## **1. Se déplacer dans le terminal**

| Commande       | Ce qu'elle fait                                    | Exemple           |
| -------------- | -------------------------------------------------- | ----------------- |
| `pwd`          | Affiche le dossier où je me trouve                 | `pwd`             |
| `ls`           | Affiche les fichiers et dossiers                   | `ls`              |
| `ls -a`        | Affiche aussi les fichiers cachés                  | `ls -a`           |
| `ls -l`        | Affiche les fichiers avec leurs détails            | `ls -l`           |
| `ls -la`       | Affiche tous les fichiers avec leurs détails       | `ls -la`          |
| `cd dev`       | Entre dans le dossier dev                          | `cd dev`          |
| `cd ..`        | Remonte d'un niveau                                | `cd ..`           |
| `cd /`         | Va à la racine du système                          | `cd /`            |
| `cd ~`nn       | Retourne dans le dossier personnel                 | `cd ~`            |
| `cd -`         | Retourne au dossier précédent                      | `cd -`            |
| `cd Documents` | Entre dans le dossier Documents                    | `cd Documents`    |
| `clear`        | Nettoie l'écran du terminal                        | `clear`           |
| `tree`         | Affiche l'arborescence des dossiers                | `tree`            |
| `history`      | Affiche l'historique des commandes                 | `history`         |
| `whoami`       | Affiche le nom de l'utilisateur connecté           | `whoami`          |
| `date`         | Affiche la date et l'heure                         | `date`            |
| `cal`          | Affiche le calendrier                              | `cal`             |
| `man ls`       | Affiche le manuel d'une commande                   | `man ls`          |
| `exit`         | Ferme le terminal                                  | `exit`            |
| `Tab`          | Complète automatiquement une commande ou un chemin | `cd Doc` puis Tab |

## **2. Fichiers et dossiers**

| Commande   | Ce qu'elle fait                       | Exemple                       |
| ---------- | ------------------------------------- | ----------------------------- |
| `touch`    | Crée un fichier vide                  | `touch test.txt`              |
| `mkdir`    | Crée un dossier                       | `mkdir projet`                |
| `mkdir -p` | Crée plusieurs dossiers imbriqués     | `mkdir -p projet/css/images`  |
| `cp`       | Copie un fichier                      | `cp a.txt b.txt`              |
| `cp -r`    | Copie un dossier et son contenu       | `cp -r dossier1 dossier2`     |
| `mv`       | Déplace un fichier                    | `mv a.txt Documents/`         |
| `mv`       | Déplace un dossier / renomme          | `mv ancien.txt nouveau.txt`   |
| `rm`       | Supprime un fichier                   | `rm test.txt`                 |
| `rmdir`    | Supprime un dossier vide              | `rmdir projet`                |
| `rm -r`    | Supprime un dossier et son contenu    | `rm -r projet`                |
| `cat`      | Affiche le contenu d'un fichier       | `cat texte.html`              |
| `less`     | Affiche un fichier page par page      | `less texte.html`             |
| `nano`     | Ouvre un fichier dans l'éditeur Nano  | `nano index.html`             |
| `head`     | Affiche les 10 premières lignes       | `head fichier.txt`            |
| `tail`     | Affiche les 10 dernières lignes       | `tail fichier.txt`            |
| `file`     | Indique le type d'un fichier          | `file image.png`              |
| `find`     | Recherche un fichier ou dossier       | `find . -name "index.html"`   |
| `grep`     | Recherche un mot dans un fichier      | `grep "bonjour" texte.txt`    |
| `wc`       | Compte les lignes, mots et caractères | `wc texte.txt`                |
| `chmod`    | Modifie les permissions d'un fichier  | `chmod 755 script.sh`         |
| `ln -s`    | Crée un lien symbolique               | `ln -s fichier.txt raccourci` |
