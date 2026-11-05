# 🖊️ Wavy Halftone Pro (4XIDRAW-LOGICIEL)

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/Vanilla-JavaScript-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![SVG Vector](https://img.shields.io/badge/Output-SVG%20Vector-orange.svg)](https://www.w3.org/Graphics/SVG/)
[![Stars](https://img.shields.io/github/stars/cbdu34/4XIDRAW-LOGICIEL?style=social)](https://github.com/cbdu34/4XIDRAW-LOGICIEL)

> **Transformez n'importe quelle image en lignes ondulées vectorielles ultra-détaillées (Wavy Halftone), prêtes pour les traceurs AxiDraw, la gravure laser et le plotter art.**

Une application web 100% côté client (aucun serveur requis) avec prévisualisation en temps réel sur Canvas, analyse automatique de contraste et export direct en **SVG vectoriel optimisé**.

▶️ **Démo en ligne : https://cbdu34.github.io/4XIDRAW-LOGICIEL/**

---

## ✨ Fonctionnalités

- ⚡ **100% Client-Side & Instantané :** Tout s'exécute directement dans le navigateur en HTML5/Canvas sans upload vers un serveur externe.
- 🎨 **Algorithme Wavy Halftone :** Modulation d'amplitude, de fréquence et d'espacement des lignes en fonction de la luminance de l'image.
- ✨ **Analyse & Optimisation Auto :** Un bouton d'analyse intelligente calcule le meilleur compromis (nombre de lignes, fréquence, contraste) selon les détails de votre photo pour éviter les tracés surchargés.
- 🖋️ **Export SVG prêt pour AxiDraw :** 
  - Tracés continus (`stroke` vectoriel sans remplissage).
  - Épaisseur de trait adaptable à la résolution.
  - Compatible direct avec Inkscape, AxiDraw, laser cutter et machines CNC.
- 🎛️ **Contrôles Complets :**
  - Nombre de lignes (10 à 300)
  - Amplitude & Fréquence des oscillations
  - Contraste de modulation & Seuil de densité
  - Échantillonnage, lissage et inversion de luminance (clair / sombre)

---

## 🚀 Utilisation Rapide

### Option 1 : Ouvrir directement dans le navigateur
Comme il s'agit d'une application standalone, il suffit d'ouvrir le fichier :
1. Clonez le dépôt :
   ```bash
   git clone https://github.com/cbdu34/4XIDRAW-LOGICIEL.git
   cd 4XIDRAW-LOGICIEL
   ```
2. Double-cliquez sur `index.html` ou ouvrez-le avec votre navigateur préféré :
   ```bash
   xdg-open index.html # ou firefox index.html / google-chrome index.html
   ```

### Option 2 : Version en ligne (GitHub Pages)
Aucune installation nécessaire : ouvrez directement **https://cbdu34.github.io/4XIDRAW-LOGICIEL/**.

---

## 🛠️ Guide d'utilisation

1. **Importez votre image** (formats PNG, JPG, WebP acceptés).
2. Cliquez sur **✨ Analyser & trouver le meilleur résultat** pour une configuration automatique optimale.
3. Affinez manuellement les réglages dans le panneau latéral si nécessaire.
4. Cliquez sur **💾 Télécharger le fichier SVG**.
5. Importez le fichier SVG dans **Inkscape** (avec l'extension AxiDraw) ou votre logiciel de FAO/découpe préféré.

---

## 🤝 Contribution & Support

Les suggestions d'algorithmes (cross-hatching, spirales, optimisation TSP des tracés) ou d'améliorations de l'interface sont les bienvenues ! 

⭐️ **Si cet outil vous est utile pour vos projets de dessin ou de découpe, laissez une étoile sur le dépôt !**

---

## 📄 Licence

Distribué sous licence MIT. Voir le fichier [LICENSE](LICENSE).
