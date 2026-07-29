# LegTracker v3.0

A major update focused on quality of life, customization and stability. Thanks to everyone tracking their legendary collection with the addon.

## New features

**Options panel (gear icon, top right).** A proper settings panel is now available, with everything you need to adapt the addon to your screen and your playstyle:

- Display filters: hide items already obtained, hide items your class cannot equip, hide legacy items (old legendaries no longer obtainable today).
- Adjustable window scale, for a larger or a more discreet display.
- Adjustable background opacity.
- Position lock, to avoid moving the window by accident.
- Show or hide the minimap button.
- Automatically open the window at login.
- "Recenter" and "Default size" buttons to get back to a clean baseline in one click.

All settings are saved and reapplied automatically on load.

**Quick "Hide obtained" toggle.** An always visible checkbox above the list lets you hide or show legendaries you already own, without opening the Options panel. Perfect for focusing on what is left to do.

**Resizable window.** A grab handle in the bottom right corner lets you stretch the window to any size. The size is remembered, list rows widen with the window, and a "Default size" button resets everything in one click. The handle hides automatically when the window is locked.

**Close with Escape.** The window now closes with the Escape key, like standard game frames.

## Bug fixes

- Fixed text overlap in the detail panel: long descriptions (item source, component "how to obtain" text) no longer spill over the next section. The height is now measured precisely.
- The selection no longer jumps back to the first item on every bag or quest update: the item you are viewing stays displayed.
- More reliable hiding of the minimap button when TibiSuite is installed, regardless of addon load order.

## Optimizations

- List rows are now reused instead of being recreated on every refresh: lower memory usage over a long play session.
- Refreshes triggered by frequent events (bag and quest updates) are now batched to reduce load while the window is open.

## Note

Compatible with Midnight (12.0). Item IDs for upcoming Midnight and The War Within legendaries will be added as patches land.

---

# LegTracker v3.0 (Francais)

Grosse mise a jour axee sur le confort d'utilisation, la personnalisation et la stabilite. Merci a tous ceux qui suivent leur collection de legendaires avec l'addon.

## Nouveautes

**Panneau Options (roue crantee en haut a droite).** Un vrai panneau de reglages fait son apparition, avec tout ce qu'il faut pour adapter l'addon a votre ecran et a votre facon de jouer :

- Filtres d'affichage : masquer les objets deja obtenus, masquer ceux qui ne sont pas equipables par votre classe, masquer les objets legacy (anciens legendaires non obtenables aujourd'hui).
- Echelle de la fenetre reglable, pour un affichage plus grand ou plus discret.
- Opacite du fond reglable.
- Verrouillage de la position, pour eviter de deplacer la fenetre par accident.
- Affichage ou masquage du bouton minimap.
- Ouverture automatique de la fenetre a la connexion.
- Boutons "Recentrer" et "Taille par defaut" pour repartir d'une base propre en un clic.

Tous les reglages sont sauvegardes et reappliques automatiquement au chargement.

**Bouton "Masquer obtenus" en acces direct.** Une case a cocher toujours visible au-dessus de la liste permet de masquer ou reafficher instantanement les legendaires deja obtenus, sans passer par le panneau Options. Ideal pour se concentrer sur ce qu'il reste a faire.

**Fenetre redimensionnable.** Une poignee en bas a droite permet desormais d'etirer la fenetre a la taille de votre choix. La taille est memorisee, les lignes de la liste s'elargissent avec la fenetre, et un bouton "Taille par defaut" remet tout d'aplomb en un clic. La poignee disparait automatiquement quand la fenetre est verrouillee.

**Fermeture avec Echap.** La fenetre se ferme desormais avec la touche Echap, comme les fenetres standard du jeu.

## Corrections

- Correction d'un chevauchement de texte dans le panneau de detail : les descriptions longues (source de l'objet, "comment obtenir" des composants) ne debordent plus sur la section suivante. La hauteur est maintenant mesuree precisement.
- La selection ne saute plus toute seule vers le premier objet a chaque mise a jour de sac ou de quete : l'objet consulte reste affiche.
- Fiabilisation du masquage du bouton minimap lorsque TibiSuite est installe, quel que soit l'ordre de chargement des addons.

## Optimisations

- Reutilisation des lignes de la liste au lieu d'en recreer a chaque rafraichissement : moins de consommation memoire sur une longue session de jeu.
- Regroupement des rafraichissements declenches par les evenements rapides (mises a jour de sacs, de quetes) pour reduire la charge quand la fenetre est ouverte.

## Note

Version compatible Midnight (12.0). Les identifiants des futurs legendaires Midnight et de The War Within seront completes au fil des patchs.
