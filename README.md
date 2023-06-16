![Cover](https://github.com/Lumantis/CodeToWord/blob/main/Codetoword.png)
# Code To Docx

Ce programme permet de créer un document Word contenant le contenu des fichiers de code d'un répertoire sélectionné.

## Utilisation

1. Exécutez `main.py` depuis votre console.
2. Sélectionnez un répertoire contenant les fichiers de code que vous souhaitez inclure dans le document.
3. Cliquez sur le bouton "Créer Document" pour générer le document Word.
4. Choisissez l'emplacement et le nom du fichier de sortie dans la boîte de dialogue de sauvegarde.
5. Le document Word sera créé avec succès.

## Prérequis

- Python 3.x installé sur votre système.
- Les packages suivants doivent être installés :
  - tkinter
  - docx
  - tqdm
  - ttkbootstrap
  - Pillow

Vous pouvez installer les packages requis en utilisant la commande suivante :

`pip install -r requirements.txt`

Assurez-vous d'exécuter cette commande dans un environnement virtuel ou avec les privilèges administratifs si nécessaire.

## Patchnotes

### Version 1.1 (16 juin 2023)

- Optimisation du code pour améliorer les performances et la lisibilité.
- Utilisation d'imports spécifiques pour les modules utilisés.
- Utilisation de méthodes spécifiques de `os` pour rejoindre les chemins de fichiers.
- Utilisation de constantes pour les valeurs littérales récurrentes.
- Ajout de vérifications pour le répertoire sélectionné (non vide).
- Utilisation d'annotations de type pour améliorer la lisibilité et la maintenance du code.
- Utilisation d'un gestionnaire de contexte pour la sauvegarde du document Word.
- Utilisation de noms de variables plus explicites.
- Utilisation d'une feuille de style pour l'interface utilisateur.
- Amélioration de la gestion des erreurs lors de la sauvegarde du document.

### Version 1.0 (15 juin 2023)

- Fonctionnalité de base : création d'un document Word à partir des fichiers de code d'un répertoire sélectionné.
