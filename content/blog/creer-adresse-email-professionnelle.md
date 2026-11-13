---
title: "Comment créer une adresse e-mail professionnelle ?"
translationKey: "create-business-email-address"
date: 2026-11-14T08:00:00+01:00
lastmod: 2026-11-14T08:00:00+01:00
description: "Créer une adresse e-mail professionnelle : nom de domaine, choix de la messagerie, réglages DNS (MX, SPF, DKIM, DMARC) et prix relevés."
categories: ["Cloud et Hébergement"]
tags: ["adresse e-mail professionnelle", "nom de domaine", "messagerie", "DNS", "TPE"]
author: "thomas-durand"
image: "/images/blog/creer-adresse-email-professionnelle.jpg"
imageAlt: "Touches de clavier blanches formant le mot EMAIL sur un fond gris"
imageCredit: "Photo : Miguel Ángel Padriñán Alba, Unsplash (recadrée)"
faq:
  - question: "Comment créer une adresse e-mail professionnelle ?"
    answer: "Il faut trois éléments : un nom de domaine au nom de l'entreprise, un service de messagerie qui héberge les boîtes, et des enregistrements DNS qui relient les deux (MX pour recevoir, SPF, DKIM et DMARC pour l'authentification). D'après les pages relevées le 13 novembre 2026, un domaine en .fr coûte 4,99 € HT la première année chez OVHcloud, et une boîte Zimbra Starter 0,30 € HT par mois. Les suites Google Workspace et Microsoft 365 incluent aussi une adresse professionnelle, à partir de 6,07 € HT (Microsoft 365) et 6,80 € (Google Workspace) par utilisateur et par mois en engagement annuel (relevé du 9 novembre 2026)."
  - question: "Peut-on avoir une adresse e-mail professionnelle gratuite ?"
    answer: "Une adresse au nom de l'entreprise suppose au minimum l'achat d'un nom de domaine. Chez OVHcloud, l'offre d'hébergement gratuite de la gamme Eco, incluse avec chaque nom de domaine acheté, comprend une adresse e-mail (relevé du 29 octobre 2026). Une adresse sur un domaine de messagerie gratuite, comme Gmail ou Outlook.com, n'est pas une adresse au nom de l'entreprise."
  - question: "Combien coûte une adresse e-mail professionnelle ?"
    answer: "Selon les relevés de novembre 2026 : de 0,30 € HT par mois et par compte (OVHcloud Zimbra Starter, 15 Go) à 1,82 € HT (Zimbra Pro, 50 Go), dès 1,50 € HT par mois chez Infomaniak (Service Mail, paiement annuel), et à partir de 6,07 € HT par utilisateur et par mois pour Microsoft 365 Business Basic ou 6,80 € pour Google Workspace Business Starter, qui ajoutent une suite bureautique. Le nom de domaine s'ajoute : 4,99 € HT la première année pour un .fr chez OVHcloud, puis 7,79 € HT."
  - question: "À quoi servent les enregistrements SPF, DKIM et DMARC ?"
    answer: "Ils prouvent aux messageries des destinataires que les e-mails viennent bien du domaine de l'entreprise. SPF liste les serveurs autorisés à envoyer, DKIM signe chaque message, DMARC indique quoi faire des messages qui échouent à ces contrôles. Sans eux, les e-mails risquent d'arriver en courrier indésirable et le domaine est plus facile à usurper."
  - question: "Quelle adresse choisir : prénom.nom@ ou contact@ ?"
    answer: "Les deux sont complémentaires. Une adresse nominative, comme prenom.nom@entreprise.fr, sert aux échanges personnels avec les clients. Une adresse générique, comme contact@ ou factures@, peut être partagée, survit aux départs et se transforme souvent en alias redirigé vers une ou plusieurs boîtes."
readingTime: true
---

> **En bref :**
> 1. Une **adresse e-mail professionnelle** repose sur trois éléments : un nom de domaine au nom de l'entreprise, un service de messagerie, et des enregistrements DNS (MX, SPF, DKIM, DMARC) qui relient les deux.
> 2. Le nom de domaine coûte 4,99 € HT la première année pour un .fr chez OVHcloud, puis 7,79 € HT au renouvellement (relevé du 13 novembre 2026).
> 3. Une messagerie seule coûte de 0,30 € HT par mois et par compte (OVHcloud Zimbra Starter) à 1,82 € HT (Zimbra Pro), ou dès 1,50 € HT par mois chez Infomaniak.
> 4. Les suites Microsoft 365 Business Basic (6,07 € HT) et Google Workspace Business Starter (6,80 €) ajoutent la bureautique et la visioconférence, par utilisateur et par mois en engagement annuel (relevé du 9 novembre 2026).

## Pourquoi créer une adresse e-mail professionnelle

**Créer une adresse e-mail professionnelle** au nom de l'entreprise, comme contact@entreprise.fr, change la façon dont les messages sont perçus. Un devis envoyé depuis une adresse personnelle sur une messagerie gratuite inspire moins confiance qu'un message envoyé depuis le domaine de l'entreprise.

L'adresse professionnelle appartient aussi à l'entreprise. Quand un salarié part, sa boîte peut être conservée, redirigée ou archivée. Les échanges avec les clients ne disparaissent pas avec un compte personnel.

Le nom de domaine sert enfin au site web. Une même identité, le nom de domaine, réunit le site et les adresses e-mail.

## Les trois éléments d'une adresse e-mail professionnelle

| Élément | Rôle | Exemple |
|---|---|---|
| Nom de domaine | L'identité de l'entreprise sur internet, la partie après le @ | entreprise.fr |
| Service de messagerie | Le serveur qui stocke les boîtes et envoie les messages | OVHcloud, Infomaniak, Google Workspace, Microsoft 365 |
| Enregistrements DNS | Les réglages qui indiquent où livrer les e-mails et prouvent leur authenticité | MX, SPF, DKIM, DMARC |

Les trois peuvent être achetés chez le même prestataire, ce qui simplifie les réglages. Ils peuvent aussi être séparés : un domaine chez un registraire, une messagerie chez un autre éditeur.

## Étape 1 : choisir et acheter un nom de domaine

Le nom de domaine est la partie après le @. Il reprend en général le nom de l'entreprise ou de la marque, avec une extension comme .fr ou .com.

D'après la page de l'extension .fr d'OVHcloud, consultée le 13 novembre 2026, un domaine en .fr coûte 4,99 € HT la première année, puis 7,79 € HT au renouvellement. Un .com coûte 8,49 € HT, puis 14,29 € HT au renouvellement. Ces prix sont annuels.

Quelques règles pour choisir :

- **Court et facile à épeler** : il sera dicté au téléphone et tapé à la main.
- **Sans tirets ni chiffres ambigus**, sources d'erreurs de saisie.
- **Vérifier les marques existantes** avant l'achat, pour éviter un conflit avec une marque déposée.
- **Prévoir le renouvellement automatique** : un domaine expiré coupe à la fois le site et les e-mails.

## Étape 2 : choisir le service de messagerie

Trois familles d'offres permettent d'héberger des adresses professionnelles.

### Les adresses incluses dans un hébergement web

Beaucoup d'hébergeurs incluent des boîtes mail dans leurs offres d'hébergement de site. Le comparatif du [meilleur hébergeur web]({{< relref "meilleur-hebergeur-web.md" >}}) détaille, à la date du 29 octobre 2026, le nombre de boîtes incluses selon les offres. OVHcloud y propose notamment une offre gratuite de la gamme Eco, incluse avec chaque nom de domaine, qui comprend une adresse e-mail.

### Les messageries professionnelles seules

Des offres dédiées hébergent uniquement les e-mails, avec plus de stockage et de fonctions.

| Offre relevée | Prix | Stockage | Points notables |
|---|---|---|---|
| OVHcloud Zimbra Starter | 0,30 € HT par mois et par compte | 15 Go | Webmail Zimbra, calendriers, tâches et contacts |
| OVHcloud Zimbra Pro | 1,82 € HT par mois et par compte | 50 Go | Synchronisation ActiveSync, stockage de fichiers, suite bureautique en ligne |
| Infomaniak Service Mail | Dès 1,50 € HT par mois (paiement annuel) | Stockage mail illimité | Messagerie développée et hébergée en Suisse |
| Infomaniak kSuite Standard | 1,58 € HT par utilisateur et par mois (paiement annuel) | Stockage mail illimité, 50 Go de fichiers | 2 adresses par utilisateur |

Prix relevés le 13 novembre 2026. OVHcloud indique que sa messagerie est hébergée en France. Infomaniak indique que ses données sont exclusivement localisées en Suisse et que les boîtes sont sauvegardées dans 2 datacenters, avec des données restaurables sous 30 jours.

### Les suites bureautiques avec messagerie

Google Workspace et Microsoft 365 incluent une adresse professionnelle dans un ensemble plus large : bureautique, stockage, visioconférence et messagerie d'équipe. D'après les relevés du 9 novembre 2026, Google Workspace Business Starter coûte 6,80 € par utilisateur et par mois en engagement annuel (prix découverte pour les nouveaux clients), et Microsoft 365 Business Basic 6,07 € HT par utilisateur et par mois en paiement annuel.

Ces suites intègrent aussi une messagerie instantanée, comparée dans l'article [Slack, Microsoft Teams ou Google Chat]({{< relref "slack-teams-ou-google-chat.md" >}}).

## Étape 3 : configurer les enregistrements DNS

Une fois le domaine et la messagerie choisis, il faut les relier. Cela passe par la zone DNS du domaine, accessible chez le registraire. Quand domaine et messagerie sont chez le même prestataire, ces réglages sont souvent créés automatiquement.

| Enregistrement | À quoi il sert |
|---|---|
| MX | Indique le serveur qui reçoit les e-mails du domaine |
| SPF | Liste les serveurs autorisés à envoyer des e-mails au nom du domaine |
| DKIM | Ajoute une signature à chaque message pour prouver qu'il n'a pas été modifié |
| DMARC | Indique aux destinataires quoi faire d'un message qui échoue aux contrôles SPF et DKIM, et permet de recevoir des rapports |

Sans SPF, DKIM et DMARC, les e-mails risquent d'arriver en courrier indésirable chez les destinataires, et le domaine est plus facile à usurper par des escrocs. Infomaniak, par exemple, mentionne sur sa page Service Mail ses filtres SPF, DKIM et DMARC contre les usurpations.

Le site web et la messagerie partagent la même zone DNS. Une modification pour l'un, par exemple un changement d'hébergeur, ne doit pas supprimer les enregistrements de l'autre. Les différents types d'hébergement sont présentés dans l'article [mutualisé, VPS, dédié ou cloud]({{< relref "hebergement-mutualise-vps-cloud.md" >}}).

## Étape 4 : créer les boîtes, les alias et les règles

### Adresses nominatives et adresses génériques

Deux types d'adresses cohabitent en général :

- **Les adresses nominatives**, comme prenom.nom@entreprise.fr, pour les échanges personnels avec les clients et partenaires.
- **Les adresses génériques**, comme contact@, factures@ ou recrutement@, qui survivent aux départs et peuvent être traitées par plusieurs personnes.

Une adresse générique n'a pas toujours besoin d'une boîte payante : un **alias** redirige ses messages vers une ou plusieurs boîtes existantes.

### Éviter l'adresse fourre-tout

Certaines messageries proposent une adresse « catch-all » qui reçoit tous les messages envoyés à n'importe quelle adresse du domaine, même inexistante. Elle attire beaucoup de courrier indésirable et peut recevoir des messages qui ne sont pas destinés à l'entreprise. Mieux vaut créer explicitement chaque adresse utile.

### Configurer les appareils

Les messageries professionnelles se consultent par webmail, dans un logiciel comme Outlook ou Thunderbird, et sur mobile. OVHcloud indique que la synchronisation ActiveSync des e-mails, contacts et calendriers est proposée avec son offre Zimbra Pro (l'offre Business étant annoncée « bientôt disponible »), pas avec Zimbra Starter.

## Étape 5 : sécuriser les comptes de messagerie

La boîte e-mail est la clé de nombreux autres comptes : c'est elle qui reçoit les liens de réinitialisation de mot de passe. Sa protection est prioritaire.

1. **Activer la double authentification** quand le service la propose.
2. **Utiliser un mot de passe unique** par boîte, stocké dans un [gestionnaire de mots de passe en entreprise]({{< relref "meilleur-gestionnaire-mots-de-passe.md" >}}).
3. **Supprimer ou réattribuer les accès** dès le départ d'un salarié.
4. **Se méfier des e-mails d'hameçonnage** qui imitent la messagerie de l'entreprise.

Ces réflexes font partie des [bonnes pratiques de cybersécurité]({{< relref "cybersecurite-bonnes-pratiques-pme.md" >}}) à appliquer dans toute l'entreprise.

## Combien coûte une adresse e-mail professionnelle

| Besoin | Option relevée | Coût indicatif |
|---|---|---|
| Une seule adresse pour démarrer | Domaine .fr + Zimbra Starter (OVHcloud) | 4,99 € HT la première année + 0,30 € HT par mois |
| Plusieurs boîtes avec synchronisation mobile | Domaine + Zimbra Pro (OVHcloud) | 1,82 € HT par mois et par compte, plus le domaine |
| Messagerie hébergée en Suisse | Infomaniak Service Mail | Dès 1,50 € HT par mois en paiement annuel, plus le domaine |
| E-mail, bureautique et visioconférence | Microsoft 365 Business Basic | 6,07 € HT par utilisateur et par mois en paiement annuel |
| E-mail, bureautique et visioconférence | Google Workspace Business Starter | 6,80 € par utilisateur et par mois en engagement annuel (prix découverte) |

Les prix des messageries seules et du domaine ont été relevés le 13 novembre 2026, ceux de Microsoft 365 et Google Workspace le 9 novembre 2026. Ils peuvent évoluer : les pages des éditeurs font foi.

## Questions fréquentes

<details>
<summary>Comment créer une adresse e-mail professionnelle ?</summary>

Il faut trois éléments : un nom de domaine au nom de l'entreprise, un service de messagerie qui héberge les boîtes, et des enregistrements DNS qui relient les deux (MX pour recevoir, SPF, DKIM et DMARC pour l'authentification). D'après les pages relevées le 13 novembre 2026, un domaine en .fr coûte 4,99 € HT la première année chez OVHcloud, et une boîte Zimbra Starter 0,30 € HT par mois. Les suites Google Workspace et Microsoft 365 incluent aussi une adresse professionnelle, à partir de 6,07 € HT (Microsoft 365) et 6,80 € (Google Workspace) par utilisateur et par mois en engagement annuel (relevé du 9 novembre 2026).

</details>

<details>
<summary>Peut-on avoir une adresse e-mail professionnelle gratuite ?</summary>

Une adresse au nom de l'entreprise suppose au minimum l'achat d'un nom de domaine. Chez OVHcloud, l'offre d'hébergement gratuite de la gamme Eco, incluse avec chaque nom de domaine acheté, comprend une adresse e-mail (relevé du 29 octobre 2026). Une adresse sur un domaine de messagerie gratuite, comme Gmail ou Outlook.com, n'est pas une adresse au nom de l'entreprise.

</details>

<details>
<summary>Combien coûte une adresse e-mail professionnelle ?</summary>

Selon les relevés de novembre 2026 : de 0,30 € HT par mois et par compte (OVHcloud Zimbra Starter, 15 Go) à 1,82 € HT (Zimbra Pro, 50 Go), dès 1,50 € HT par mois chez Infomaniak (Service Mail, paiement annuel), et à partir de 6,07 € HT par utilisateur et par mois pour Microsoft 365 Business Basic ou 6,80 € pour Google Workspace Business Starter, qui ajoutent une suite bureautique. Le nom de domaine s'ajoute : 4,99 € HT la première année pour un .fr chez OVHcloud, puis 7,79 € HT.

</details>

<details>
<summary>À quoi servent les enregistrements SPF, DKIM et DMARC ?</summary>

Ils prouvent aux messageries des destinataires que les e-mails viennent bien du domaine de l'entreprise. SPF liste les serveurs autorisés à envoyer, DKIM signe chaque message, DMARC indique quoi faire des messages qui échouent à ces contrôles. Sans eux, les e-mails risquent d'arriver en courrier indésirable et le domaine est plus facile à usurper.

</details>

<details>
<summary>Quelle adresse choisir : prénom.nom@ ou contact@ ?</summary>

Les deux sont complémentaires. Une adresse nominative, comme prenom.nom@entreprise.fr, sert aux échanges personnels avec les clients. Une adresse générique, comme contact@ ou factures@, peut être partagée, survit aux départs et se transforme souvent en alias redirigé vers une ou plusieurs boîtes.

</details>
