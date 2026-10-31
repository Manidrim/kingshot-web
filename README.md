# 👑 KingShot Web

Jeu de stratégie isométrique en HTML/CSS/JavaScript **pur** (aucune dépendance, aucun build).
Inspiré du jeu mobile *KingShot* : défends ta grande tour, capture les tours ennemies et **étends ton royaume** jusqu'à contrôler toute la carte !

## 🎮 Comment jouer

Ouvre `index.html` dans un navigateur, c'est tout. (Ou active GitHub Pages, voir plus bas.)

### Règles
- 🏹 Tes tours **bleues** tirent automatiquement des flèches sur les tours rouges.
- 🎯 **Glisse depuis une tour bleue** (maintenir → viser → relâcher) pour tirer un **obus de canon** : gros dégâts de zone, recharge 3 s. Attention aux dégâts collatéraux sur tes propres tours !
- 🏳️ Une tour ennemie tombée à 0 PV **change de camp** : son territoire devient bleu, ton royaume s'étend.
- 🪙 Ton territoire rapporte de l'or. Clique sur les pièces souriantes qui apparaissent pour un bonus.
- 🏗️ Avec l'or : améliore tes flèches, ta cadence, ta portée, répare la grande tour, ou **construis de nouvelles tours** sur des cases neutres collées à ton territoire.
- 💰 Les tours ennemies se régénèrent : n'attend pas trop pour frapper !
- 💀 Si ta **grande tour centrale** (avec couronne) tombe, la partie est perdue.
- 🏆 Objectif : capturer les **8 tours rouges** et contrôler 100 % du territoire.

## 🚀 GitHub Pages

1. Ouvre les **Settings** du dépôt
2. **Pages** → Source : *Deploy from a branch* → branche `main`, dossier `/ (root)`
3. Le jeu sera dispo sur `https://manidrim.github.io/kingshot-web/`

## 🛠️ Tech

- Canvas 2D avec projection isométrique
- Aucune image externe : tout est dessiné en code
- Sons générés en Web Audio API
- Compatible souris et tactile

*Fait avec l'aide de Vibe (Mistral AI).*
