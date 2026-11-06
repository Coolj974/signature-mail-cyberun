# Signature e-mail Cyberun

Générateur de signature e-mail moderne et interactif aux couleurs de Cyberun (« Innovation & Tradition »).

![Aperçu du générateur](apercu.png)

## 🚀 Utilisation (employés)

1. Ouvrir le générateur : **https://coolj974.github.io/signature-mail-cyberun/**
2. Remplir prénom, nom, poste, e-mail et, si besoin, téléphone fixe, mobile, adresse sur 2 lignes (lieu, puis rue et ville – lien Google Maps automatique), horaires (une ligne par période, ex. `Vendredi  8h–13h`) et LinkedIn. Les champs vides n'apparaissent pas dans la signature.
3. Cliquer sur **Copier la signature**, puis la coller dans la messagerie :
   - **Gmail** : Paramètres → Voir tous les paramètres → Signature → Créer → Ctrl+V
   - **Outlook Web / nouvel Outlook** : Paramètres → Comptes → Signatures → Ctrl+V
   - **Outlook classique (Windows)** : Fichier → Options → Courrier → Signatures → Ctrl+V (ou bouton **Télécharger (.htm)**)
   - **Apple Mail** : Réglages → Signatures → Ctrl+V (décocher « Toujours utiliser ma police par défaut »)

💡 Lien pré-rempli : `https://coolj974.github.io/signature-mail-cyberun/?prenom=Jean&nom=Dupont&poste=Commercial&email=jean.dupont@cyberun.info`

## 📁 Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | Générateur (formulaire + aperçu + copie) |
| `signature-exemple.html` | Signature statique de référence |
| `logo-cyberun.svg` | Logo officiel (vectoriel) |
| `logo-cyberun.png` | Logo PNG HD (×3), utilisé quand le SVG n'est pas supporté |
| `logo-cyberun-sombre.svg/.png` | Logo tout bleu, affiché en mode sombre (Apple Mail, iOS, Outlook…) |
| `icons/` | Icônes PNG bleues (e-mail, téléphone, mobile, adresse, horaires, lecture), utilisées à la place des symboles Unicode que Gmail convertit en emojis |

## 🖼️ Logo SVG / PNG

La signature utilise `<picture>` : le **SVG** s'affiche dans Apple Mail, iOS et Outlook Mac/Web, et le **PNG HD** s'affiche automatiquement dans Gmail et Outlook Windows, qui ne supportent pas le SVG.

## 🎨 Personnalisation

En haut du script de `index.html`, l'objet `CONFIG` regroupe l'URL des logos, l'adresse du site et les couleurs (`#2581C4` → `#1B9CD8`).
