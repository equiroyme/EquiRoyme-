# EquiRoyme

**Trouvez votre cheval. Préparez la route.**

EquiRoyme est une plateforme de vente, d’hébergement et de transport de chevaux en France. Annonces vérifiées, documents de santé, essais, écuries étapes et transport : tout le parcours d’achat au même endroit.

👉 **Voir le site : [https://equiroyme.fr](https://equiroyme.fr)**

> ⚠️ Ceci est un **prototype**. Les chevaux, écuries et transporteurs affichés sont des exemples. Le paiement, la vérification d’identité et l’envoi des messages sont simulés.

---

## Fonctionnalités

### Pour les acheteurs
- **Carte de France** des chevaux à vendre ou à louer et des écuries étapes
- **Recherche détaillée** : achat ou location, catégorie (Pro → Pro, Pro → Amateur, Amateur → Amateur), discipline, race, sexe, débourrage, niveau d’épreuve, âge, taille (poneys A à D, chevaux), prix, distance
- **Chevaux sur ma route** : on indique un départ, une arrivée et un détour maximum, et l’app montre les chevaux le long du trajet
- **Fiche cheval** : 4 photos et 2 vidéos, caractéristiques, vendeur (qui peut rester anonyme), zone approximative
- **Documents de santé** (radios, visite vétérinaire, ostéopathe, dentiste, papiers SIRE) réservés aux membres Premium
- **Tournée d’essais** : plusieurs essais organisés sur une journée, avec ordre des visites, horaires, kilomètres et coût estimé, et réponses des vendeurs
- **Favoris et alertes** par e-mail et notification (Premium)

### Pour les vendeurs
- **Dépôt d’annonce** depuis le téléphone, avec **tous les champs facultatifs**
- Choix d’**afficher son nom ou de rester anonyme**
- Documents **visibles (Premium)** ou **envoyés sur demande**
- Mise en avant **« À la une »** (annonce sponsorisée)

### Services
- **Écuries étapes** : une nuit pour les chevaux pendant le trajet (box paille, copeaux, foin compris, pré), avec calcul du prix et demande de réservation
- **Transport** : demande de devis auprès de transporteurs partenaires
- **Messagerie** : échanges avec les vendeurs, demandes d’essai et de documents, contrat de vente

## Offres

| Offre | Pour qui | Principaux avantages |
|---|---|---|
| **Gratuit** | Tout le monde | Recherche, carte, publication d’annonces, messagerie |
| **Premium Acheteur** | Acheteurs | Documents de santé, alertes e-mail et notification, tournées d’essais, contrat prérempli |
| **Premium Vendeur** | Vendeurs | Annonce à la une, statistiques, remontée automatique |
| **Pro** | Écuries, éleveurs, marchands, transporteurs | Agenda d’essais, acompte pour bloquer un essai, page vitrine, acheteurs vérifiés |

Les tarifs sont en cours de définition.

## Installer l’application sur son téléphone

1. Ouvrir le site dans le navigateur du téléphone.
2. Menu du navigateur → **« Ajouter à l’écran d’accueil »**.
3. EquiRoyme s’ouvre alors en plein écran, comme une application.

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | Toute l’application (une seule page) |
| `manifest.webmanifest` | Nom, couleurs et icônes pour l’installation sur téléphone |
| `sw.js` | Charge toujours la dernière version et permet un usage hors connexion |
| `icon-180.png`, `icon-192.png`, `icon-512.png` | Icônes de l’application |
| `CNAME` | Nom de domaine du site (GitHub Pages) |

## Mettre à jour le site

1. **Add file → Upload files**, déposer le nouveau `index.html`.
2. Vérifier que le fichier s’appelle exactement `index.html` (le renommer si besoin).
3. **Commit changes** : le site est à jour en une ou deux minutes.

---

© EquiRoyme — tous droits réservés.
