# Aide-mémoire du terminal Linux

## Se déplacer

| Commande | Ce qu'elle fait                    | Exemple    |
| -------- | ---------------------------------- | ---------- |
| `pwd`    | Affiche le dossier où je suis      | `pwd`      |
| `cd`     | Change de dossier                  | `cd ~/dev` |
| `cd ..`  | Remonte d'un dossier               | `cd ..`    |
| `ls`     | Liste les fichiers                 | `ls`       |
| `ls -la` | Liste tout, même les cachés        | `ls -la`   |
| `ls -R`  | Liste tout, même les sous-dossiers | `ls -R`    |

## Fichiers et dossiers

| Commande   | Ce qu'elle fait                   | Exemple                            |
| ---------- | --------------------------------- | ---------------------------------- |
| `mkdir`    | Crée un dossier                   | `mkdir projet`                     |
| `mkdir -p` | Crée plusieurs dossiers d'un coup | `mkdir -p projet/assets/images`    |
| `touch`    | Crée un fichier vide              | `touch notes.txt`                  |
| `cp`       | Copie un fichier                  | `cp a.txt b.txt`                   |
| `cp -r`    | Copie tout un dossier             | `cp -r projet projet-sauvegarde`   |
| `mv`       | Déplace ou renomme                | `mv "mes documents" mes-documents` |
| `rm`       | Supprime un fichier               | `rm notes.txt`                     |
| `rm -rf`   | Supprime un dossier entier        | `rm -rf projet-sauvegarde`         |

## Lire et chercher

| Commande  | Ce qu'elle fait                   | Exemple                   |
| --------- | --------------------------------- | ------------------------- |
| `cat`     | Affiche tout le contenu           | `cat idees.txt`           |
| `less`    | Lit un long fichier page par page | `less logs/app.log`       |
| `head -3` | Affiche les 3 premières lignes    | `head -3 logs/app.log`    |
| `tail -3` | Affiche les 3 dernières lignes    | `tail -3 logs/app.log`    |
| `wc -l`   | Compte les lignes                 | `wc -l logs/app.log`      |
| `grep`    | Cherche un mot dans un fichier    | `grep ERROR logs/app.log` |
| `grep -r` | Cherche dans tout un dossier      | `grep -r TODO projet`     |
| `sort`    | Trie par ordre alphabétique       | `sort logs/warnings.txt`  |

## Redirection

| Commande | Ce qu'elle fait     | Exemple                      |
| -------- | ------------------- | ---------------------------- |
| `>`      | Crée et écrase      | `echo "Idée 1" > idees.txt`  |
| `>>`     | Ajoute sans effacer | `echo "Idée 2" >> idees.txt` |

## Divers

| Commande   | Ce qu'elle fait         | Exemple                        |
| ---------- | ----------------------- | ------------------------------ |
| `echo`     | Affiche un texte        | `echo "Bonjour"`               |
| `date`     | Affiche la date du jour | `date`                         |
| `clear`    | Efface l'écran          | `clear`                        |
| `tar -xzf` | Décompresse une archive | `tar -xzf exo-fichiers.tar.gz` |

## branches

| Commande      | Ce qu'elle fait                 | Exemple |
| ------------- | ------------------------------- | ------- |
| `git branch ` | liste les branches de mon depot |
| `git switch   |
