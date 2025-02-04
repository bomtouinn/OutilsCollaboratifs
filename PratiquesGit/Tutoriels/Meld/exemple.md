# Exemple d'utilisation de Meld

## Comparaison de fichiers texte

### Fichiers de départ

**fichier1.txt**
```txt
Bonjour,
Ce fichier contient une ligne en trop.
Il est utilisé pour démontrer Meld.

fichier2.txt

Bonjour,
Il est utilisé pour démontrer Meld.

Comparaison avec Meld

    Ouvrir Meld et choisir "Comparer des fichiers".
    Sélectionner fichier1.txt et fichier2.txt.
    Meld mettra en évidence la ligne manquante dans fichier2.txt.

Comparaison de dossiers

Supposons que nous ayons deux dossiers :

dossier1/
  ├── fichier_a.txt
  ├── fichier_b.txt

dossier2/
  ├── fichier_a.txt
  ├── fichier_c.txt

    Ouvrir Meld et choisir "Comparer des dossiers".
    Sélectionner dossier1/ et dossier2/.
    Meld affichera :
        fichier_a.txt : identique.
        fichier_b.txt : présent dans dossier1/ mais pas dans dossier2/.
        fichier_c.txt : présent dans dossier2/ mais pas dans dossier1/.

Fusion de fichiers

Avec Meld, on peut fusionner les différences en :

    Copiant une ligne d'un fichier à l'autre (→ ou Ctrl + Maj + →).
    Modifiant le texte directement dans Meld.
    Sauvegardant les fichiers modifiés.

Cela permet de combiner différentes versions de fichiers facilement.


---

Cet exemple montre une utilisation concrète de Meld avec des fichiers et des dossiers. 