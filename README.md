# TCG Ligue F1 — Distribution iOS

Ce repo contient uniquement l'app iOS compilée (non signée) et le fichier
"source" AltStore/SideStore pour l'installer — pas le code source du jeu
(qui reste privé dans le repo principal `TCG-Ligue-F1`).

## Installer l'app

1. Installe **SideStore** sur ton iPhone (voir [sidestore.io](https://sidestore.io))
2. Dans SideStore, ajoute cette source :
   ```
   https://raw.githubusercontent.com/Hugoambiehl/TCG-Ligue-F1-iOS/main/source.json
   ```
3. Installe "TCG Ligue F1" depuis la source

## Mettre à jour une nouvelle version

Remplacer `ios/TCG-Ligue-F1.ipa` par le nouveau build (produit par Codemagic,
workflow `ios-unsigned` dans le repo principal), et mettre à jour
`source.json` (`version`, `date`, `size`, `localizedDescription`).
