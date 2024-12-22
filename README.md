<div align="center">
  <a href="https://terminal.sylvain.pro"><img src="https://terminal.sylvain.pro/images/logo.png" alt="Logo" width="25%" height="auto"></a>

  # Web Linux Terminal
  [![Version](https://custom-icon-badges.demolab.com/badge/Version%20:-v1.0.2-6479ee?logo=terminal.sylvain.pro&labelColor=23272A)](https://github.com/20syldev/terminal/releases/latest)
</div>



## À propos

Ce sous-domaine est un **terminal sur le web** construit en HTML, CSS et JavaScript. Il fournit une implémentation simple et fonctionnelle d'une interface de terminal qui permet aux utilisateurs d'exécuter des commandes, de naviguer dans le système de fichiers, etc.

## ✨ Fonctionnalités

- **Exécution de commandes** : Possibilité d'entrer des commandes et voir la sortie directement dans le terminal.
- **Navigation dans le système de fichiers** : Possibilité de naviguer dans les répertoires, lister les fichiers et effectuer des opérations de base sur les fichiers.
- **Historique des commandes** : Les utilisateurs peuvent accéder aux commandes précédemment exécutées à l'aide des touches flèche haut et flèche bas.
- **Autocomplétion** : Les utilisateurs peuvent utiliser la touche "Tab" pour compléter automatiquement les commandes et les chemins d'accès aux fichiers.

## 🚀 Utilisation

### 📝 Commands

> [!NOTE]
> Vous pouvez utiliser `help` pour afficher toutes les commandes disponibles.  
> Vous pouvez utiliser `sudo` avant une commande pour l'exécuter en tant qu'utilisateur root.  
> Vous pouvez utiliser `> [nom de fichier]` à la fin d'une commande pour enregistrer la sortie dans un fichier.

| Commande     | Description                             | Utilisation                 | Notes                                                                                     |
|--------------|-----------------------------------------|-----------------------------|-------------------------------------------------------------------------------------------|
| `adduser`    | Ajouter un nouvel utilisateur           | `adduser [username]`        |                                                                                           |
| `alias`      | Créer un alias pour une commande        | `alias [name] [command]`    |                                                                                           |
| `cat`        | Afficher le contenu d'un fichier        | `cat [filename]`            |                                                                                           |
| `cd`         | Change the current directory            | `cd [directory]`            | Utiliser `..` vous fait remonter d'un répertoire, et `~` vous ramènes au répertoire home. |
| `clear`      | Effacer le contenu du terminal          | `clear`                     |                                                                                           |
| `color`      | Changer la couleur du terminal          | `color (color)`             |                                                                                           |
| `cp`         | Copier un fichier ou un répertoire      | `cp [source] [destination]` |                                                                                           |
| `curl`       | Récupérer le contenu d'une URL          | `curl [url]`                | Il n'est pas possible d'utiliser le user-agent curl puisqu'il s'agit d'un terminal web.   |
| `date`       | Afficher la date et l'heure actuelle    | `date`                      |                                                                                           |
| `echo`       | Afficher du texte dans le terminal      | `echo [text]`               |                                                                                           |
| `exit`       | Fermer le terminal                      | `exit`                      | Si vous êtes utilisateur `root`, vous déconnecte.                                         |
| `help`       | Lister toutes les commandes             | `help`                      |                                                                                           |
| `javascript` | Ouvrir une console JavaScript           | `javascript (code)`         |                                                                                           |
| `ls`         | Lister le contenu d'un répertoire       | `ls`                        |                                                                                           |
| `mkdir`      | Créer un nouveau répertoire             | `mkdir [directory]`         |                                                                                           |
| `mv`         | Déplacer un fichier ou un répertoire    | `mv [source] [destination]` |                                                                                           |
| `nano`       | Ouvrir l'éditeur de texte               | `nano [filename]`           | Instable                                                                                  |
| `neofetch`   | Afficher les informations du système    | `neofetch`                  | Disponible seulement pour chrome et safari.                                               |
| `passwd`     | Changer le mot de passe                 | `passwd (username)`         | Ne pas entrer de nom d'utilisateur changera le mot de passe de l'utilisateur actuel.      |
| `pwd`        | Afficher le chemin absolu du répertoire | `pwd`                       |                                                                                           |
| `rm`         | Supprimer un fichier ou un répertoire   | `rm [file]`                 |                                                                                           |
| `screenshot` | Prendre une capture d'écran du terminal | `screenshot`                |                                                                                           |
| `sh`         | Lancer un shell                         | `sh [file]`                 |                                                                                           |
| `stats`      | Afficher les statistiques du terminal   | `stats (params)`            |                                                                                           |
| `su`         | Changer d'utilisateur                   | `su (username)`             | Ne pas entrer de nom d'utilisateur changera l'utilisateur pour `root`.                    |
| `touch`      | Créer un nouveau fichier                | `touch [filename]`          |                                                                                           |
| `tree`       | Afficher l'arborescence du répertoire   | `tree`                      |                                                                                           |
| `unalias`    | Supprimer un alias                      | `unalias [name]`            |                                                                                           |
| `userdel`    | Supprimer un utilisateur                | `userdel [username]`        |                                                                                           |
| `usermod`    | Modifier un utilisateur                 | `usermod [username]`        |                                                                                           |
| `whoami`     | Afficher l'utilisateur actuel           | `whoami`                    |                                                                                           |
| `wget`       | Télécharger un fichier via une URL      | `wget [url]`                |                                                                                           |
> `[]` signifie obligatoire, `()` signifie facultatif
