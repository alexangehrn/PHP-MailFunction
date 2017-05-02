# Mail
Librairie d'envoi de mail en POO

## Fonctionnalités Générales

* Envoi de mail
* Multiples destinataires
* Multiples copies cachées
* Message en HTML ou texte
* Multiples pièces jointes

## Attributs de la class upload

    $_mail_expediteur => Correspond à l'adresse mail de l'expéditeur
    $_nom_expediteur  => Correspond au nom de l'expéditeur
    $_mail_destinataire => Correspond à l'adresse mail du/des destinataire/s
    $_mail_replyto => Correspond à l'adresse mail envers qui la réponse au mail doit être envoyée
    $_bcc => Correspond à l'adresse mail de/des copie/s cachée/s
    $_objet => Correspond à l'objet du mail
    $_text => Correspond au contenu du mail en texte brut
    $_html => Correspond au contenu du mail en HTML
    $_fichiers => Correspond à une/des pièce/s jointe/s
    $_message => Correspond au contenu global du mail
    $_frontiere => Correspond à la frontière de séparation des contenus
    $_headers => Correspond aux headers du mail
    
## Arguments de la methode construct

Cette methode va permettre de :

* Valider le format du mail de l'expéditeur et du replyTo
* Initialiser les propriétés: Mail de l'expéditeur, Nom de l'expéditeur, Mail du ReplyTo, frontière et headers

Attributs :

* $mail_expediteur
* $nom_expediteur
* $mail_replyto

## Methode ajouter_destinataire

Cette methode va permettre de:

* Valider le format du mail du/des destinataire/s
* Ajouter un ou des destinataire/s

Attribut :

* $mail

## Methode ajouter_bcc

Cette methode va permettre de:

* Valider le format du mail du/des copie/s cachée/s
* Ajouter unz ou des copie/s cachée/s

Attribut :

* $bcc

## Methode ajouter_pj

Cette methode va permettre de:

* Ajouter une ou des pièce/s jointe/s

Attribut :

* $fichiers

## Methode contenu

Cette methode va permettre de:

* Initialiser les propriétés: Objet, texte brut, html

Attributs :

* $objet
* $text
* $html

## Methode envoyer

Cette methode va permettre de:

* Initialiser les propriétés: Headers, Message
* Envoyer le mail

Aucun Attribut



