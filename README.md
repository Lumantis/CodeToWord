![Cover](https://github.com/Lumantis/CodeToWord/blob/main/Codetoword.png)
# Code To Docx

Ce programme permet de créer un document Word contenant le contenu des fichiers de code d'un répertoire sélectionné.

## Utilisation

1. Exécutez le programme en utilisant `Python 3`.
2. Sélectionnez un répertoire contenant les fichiers de code que vous souhaitez inclure dans le document.
3. Cliquez sur le bouton "Créer Document" pour générer le document Word.
4. Choisissez l'emplacement et le nom du fichier de sortie dans la boîte de dialogue de sauvegarde.
5. Le document Word sera créé avec succès.

## Prérequis

- `Python 3.x` installé sur votre système.
- Les packages suivants doivent être installés :
  - `tkinter`
  - `docx`
  - `tqdm`
  - `ttkbootstrap`
  - `Pillow`

Vous pouvez installer les packages requis en utilisant la commande suivante :

`pip install -r requirements.txt`

Assurez-vous d'exécuter cette commande dans un environnement virtuel ou avec les privilèges administratifs si nécessaire.

## Patchnotes

### Version 1.1 (16 juin 2023)

- Optimisation du code pour améliorer les performances et la lisibilité.
- Utilisation d'imports spécifiques pour les modules utilisés.
- Utilisation de listes en compréhension pour la récupération des fichiers à traiter.
- Utilisation de context managers pour ouvrir les fichiers.
- Gestion améliorée des erreurs lors de la lecture des fichiers.
- Utilisation de constantes pour les extensions de fichiers.
- Utilisation de méthodes spécifiques pour les objets Paragraph.
- Amélioration de l'interaction avec l'utilisateur en utilisant des fenêtres de dialogue modales.
- Utilisation de la méthode `filetypes` de `asksaveasfilename` pour spécifier les types de fichiers autorisés.
- Utilisation d'une feuille de style pour la fenêtre principale.

### Version 1.0 (12 mai 2023)

- Fonctionnalité de base : création d'un document Word à partir des fichiers de code d'un répertoire sélectionné.
