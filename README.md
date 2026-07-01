# Soirée Cinéma « Vingt Dieux » 🎬🍷

Support de **présentation orale** de Carla Poirier — *Projection insolite, se démarquer par l'œnotourisme événementiel au Domaine Rolet (Arbois, Jura)*.

## ▶️ Voir la présentation

La présentation est le fichier **[`index.html`](index.html)**. Trois façons de l'ouvrir :

1. **Lien en ligne** (à envoyer à quelqu'un pour tester) — voir la section *Lien à partager* ci-dessous.
2. **En local, hors-ligne** : télécharge le dépôt puis ouvre `index.html` dans ton navigateur (double-clic). ✅ Fonctionne **sans connexion Internet**.
3. **GitHub Pages** : pour obtenir une belle adresse publique permanente (voir plus bas).

## ⌨️ Raccourci clavier

| Touche | Action |
|--------|--------|
| **A** | Passer / quitter le **plein écran** |
| **← / →**, Espace, Page ↑/↓ | Naviguer entre les diapositives |

> Astuce présentation : ouvre la page, appuie sur **A** pour le plein écran, puis navigue avec les flèches.

## 🌐 Lien à partager

Pour la faire tester à quelqu'un **sans qu'il ait besoin d'un compte Claude**, deux options :

### Option recommandée — GitHub Pages (adresse propre et permanente)
Adresse : **https://pierreprz.github.io/Carla-pr-sentation-oral/**

Si elle affiche une erreur 404, active Pages une fois :
1. Dépôt GitHub → **Settings** → **Pages**
2. *Source* : **Deploy from a branch**
3. *Branch* : la branche du projet, dossier **/ (root)** → **Save**
4. Attends ~1 minute, puis rouvre l'adresse ci-dessus.

### Option instantanée (aucune configuration) — via githack
Sert directement `index.html` depuis ce commit du dépôt public :

```
https://raw.githack.com/pierreprz/Carla-pr-sentation-oral/d34fc31a801109265cad134c2a91ab0e238f2223/index.html
```

## 🛠️ Détails techniques

- `index.html` : la présentation complète exportée depuis Claude (autonome, images intégrées).
- `vendor/` : React, ReactDOM et Babel **inclus en local**. Le runtime les détecte et **n'appelle donc pas** le CDN `unpkg.com` → la présentation s'affiche **même hors-ligne**, sans dépendre d'Internet le jour J.
- Ajout d'un petit script : la touche **A** bascule en plein écran.
