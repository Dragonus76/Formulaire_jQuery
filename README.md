# Formulaire_jQuery
jQuery
Le but de ce travail pratique est de réaliser un formulaire interactif, que l'on animera grâce à jQuery. Ce sera un formulaire très basique, avec quatre ou cinq champs au maximum, qui verront leur style CSS changer suivant l'action de l'utilisateur. Le but est en fait de vérifier les informations entrées : nombre de caractères, vérifier que la confirmation du mot de passe est identique à celui-ci, vérifier si tous les champs sont remplis, etc.

Objectif concret
Ce formulaire devra contenir quatre champs :

un champ text pour le pseudonyme ;

un champ password pour le mot de passe ;

un deuxième champ password pour la confirmation du mot de passe ;

et un dernier champ text pour ce que vous voulez, comme l'adresse e-mail par exemple.

De même, deux boutons devront permettre respectivement d'envoyer les données, et de vider les champs. Pas de langage serveur pour ce TP : tout devra se dérouler dans le côté client. Évidemment, vous devrez vous assurer par la suite, lorsque vous coderez pour des projets destinés au grand public, que les données sont bonnes du côté serveur, c'est très important car le JavaScript peut être contourné !

Pour le moment, le but est juste de vous faire pratiquer. Vous devrez vous assurer que l'utilisateur rentre les bonnes infos, de la bonne manière :

tous les champs devront contenir au moins 5 caractères ;

le mot de passe et la confirmation devront être bien sûr identiques ;

si les champs sont vides lors de l'envoi, on affiche un message d'erreur.

Pour indiquer l'erreur au visiteur, il vous suffira d'utiliser CSS : une bordure de champ de couleur rouge ferait par exemple l'affaire. De la même manière, si le champ est bon, vous pourriez changer la couleur du champ adéquat en vert.

Méthodes requises
Pour pouvoir réaliser cela, vous allez devoir user des évènements, vous ne pourrez rien faire sans. De même, la manipulation du CSS doit être maîtrisée afin de pouvoir animer les champs. N'oubliez pas que vous devez traiter tous les cas, car il ne faut jamais faire confiance à l'utilisateur.
