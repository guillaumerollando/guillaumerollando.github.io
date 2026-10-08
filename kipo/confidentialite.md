---
layout: default
lang: fr
title: Politique de confidentialité — Kipo
app: Kipo
app_url: /kipo/
autre_langue: /kipo/privacy
autre_langue_nom: English
---

# Politique de confidentialité de Kipo

<p class="maj">Dernière mise à jour : 9 octobre 2026</p>

Kipo est une application Android et iOS pour organiser des événements et discuter en groupe, publiée par **{{ site.editeur }}** ({{ site.pays }}). Le responsable du traitement est **{{ site.responsable }}**, joignable à **[{{ site.contact }}](mailto:{{ site.contact }})**.

**En bref :** il faut un compte (e-mail, Google ou Apple). Tes messages sont chiffrés de bout en bout : nous ne pouvons pas les lire. Ils sont effacés de nos serveurs au bout de 7 jours. Pas de publicité, pas d'analyse de ton usage, pas de vente de données. Tu peux supprimer ton compte à tout moment depuis l'appli ou sur [kipo-app.fr/delete-account](https://kipo-app.fr/delete-account).

## 1. Les données de ton compte

- **Identité :** adresse e-mail, nom et prénom, photo de profil (facultative). Ton e-mail n'est jamais montré aux autres utilisateurs.
- **Connexion :** mot de passe (stocké chiffré par notre prestataire d'authentification, jamais en clair) ou identifiant Google / Apple.
- **Ta vie dans l'appli :** événements créés ou rejoints, réponses d'invitation, groupes, favoris, personnes rencontrées par QR code, utilisateurs que tu as bloqués, signalements que tu as faits.
- **Appareil :** jeton de notification (pour t'envoyer les alertes), adresse IP et type d'appareil dans les journaux techniques du serveur.

## 2. Tes messages et tes médias

- Les messages (texte, vocaux, photos, vidéos) sont **chiffrés sur ton téléphone** avant l'envoi (AES-256-GCM, clés échangées entre les membres). Nous stockons seulement des données illisibles pour nous.
- **Tout est effacé de nos serveurs au plus tard 7 jours après l'envoi.** Les messages que tu *enregistres* restent uniquement sur le téléphone des membres qui les ont reçus.
- Ta clé de chiffrement privée est conservée dans un coffre protégé par ton code PIN : nous ne connaissons pas ton PIN. Si tu l'oublies, nous ne pouvons pas récupérer tes anciens messages.
- Les sauvegardes automatiques Android sont désactivées pour Kipo.

## 3. Signalement et blocage

Tu peux bloquer un utilisateur (il ne peut plus t'écrire en message privé) ou le signaler. Un signalement contient le motif, ton commentaire éventuel et, si tu choisis de les joindre, quelques messages que tu as déchiffrés toi-même. Il est examiné par l'éditeur et n'est pas communiqué à la personne signalée. Nous pouvons suspendre ou supprimer un compte qui enfreint les [conditions](conditions).

## 4. Qui traite tes données (sous-traitants)

| Prestataire | Rôle | Données |
|---|---|---|
| **Supabase** (base de données et authentification, serveurs en France — région Paris ; stockage des fichiers) | Hébergement des données et connexion | Compte, événements, groupes, messages chiffrés, photos de profil et médias chiffrés |
| **Render** | Hébergement du serveur de l'application | Toutes les requêtes passent par lui (adresse IP, journaux techniques) |
| **Google Firebase Cloud Messaging** / **Apple Push** | Envoi des notifications | Jeton de notification, texte générique de l'alerte (jamais le contenu d'un message) |
| **Google / Apple** | Connexion « Se connecter avec… » (facultative) | Identifiant et e-mail du compte choisi |
| **event-to-calendar.com** | Bouton « Ajouter au calendrier » (facultatif) | Titre, description et lieu de l'événement que tu ajoutes |

Certains de ces prestataires peuvent traiter des données hors de l'Union européenne, avec des garanties contractuelles (clauses types de la Commission européenne). Nous ne vendons aucune donnée et n'affichons aucune publicité.

## 5. Autorisations Android / iOS

- **Appareil photo, micro :** prendre une photo, envoyer un message vocal, scanner un QR code.
- **Photos et vidéos :** choisir une image à envoyer ; enregistrer un média reçu dans ta galerie.
- **Notifications :** être prévenu d'un message, d'une invitation ou d'une annonce.

Aucune de ces autorisations n'est utilisée en arrière-plan à d'autres fins. Kipo n'accède ni à tes contacts, ni à ta position, ni à tes SMS.

## 6. Pourquoi ces données (bases légales)

| Usage | Base légale (RGPD) |
|---|---|
| Compte, événements, groupes, messages | Exécution du service que tu as demandé (contrat) |
| Notifications | Exécution du contrat ; tu peux les couper dans ton téléphone |
| Journaux techniques, sécurité, lutte contre les abus, signalements | Intérêt légitime de l'éditeur à protéger la plateforme et ses utilisateurs |
| Ajout au calendrier | Ton choix à chaque utilisation (consentement) |
| Obligations légales (réquisition judiciaire) | Obligation légale |

## 7. Combien de temps

| Donnée | Durée |
|---|---|
| Messages et médias envoyés | 7 jours maximum sur nos serveurs |
| Événements | Supprimés 7 jours après leur fin ; les « Souvenirs » (photos) restent seulement sur ton téléphone |
| Compte et profil | Jusqu'à la suppression du compte |
| Journaux techniques | Selon l'hébergeur (quelques semaines au plus) |
| Signalements | Le temps nécessaire à la sécurité de la plateforme |

## 8. Supprimer ton compte

*Profil › Modifier mon profil › Supprimer mon compte*, ou la page [kipo-app.fr/delete-account](https://kipo-app.fr/delete-account) si tu n'as plus l'application. Ton accès, ton nom, ton e-mail, ta photo, tes clés et tes liens avec les groupes et événements sont effacés. Le détail de ce qui peut subsister est sur cette page.

## 9. Âge minimum

Kipo est réservé aux personnes de **15 ans et plus**. Si tu penses qu'un enfant plus jeune a un compte, écris-nous : nous le supprimerons.

## 10. Tes droits

Tu peux accéder à tes données, les corriger, les effacer, les récupérer, limiter ou t'opposer à leur traitement, en écrivant à [{{ site.contact }}](mailto:{{ site.contact }}). Nous répondons sous un mois. Tu peux aussi déposer une réclamation auprès de la **CNIL** ([cnil.fr](https://www.cnil.fr)).

## 11. Modifications

Si cette politique change, la date ci-dessus change et, pour un changement important, l'application t'en informe.
