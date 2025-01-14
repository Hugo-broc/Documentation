---
description: >-
  Des messages nuisibles sur votre serveur ? Alors toutes ces commandes de
  DraftBot vont vous aider !
---

# Gestion des messages

### <mark style="color:purple;">Supprimer des messages</mark>

Vous pouvez effacer des messages avec la commande <mark style="color:orange;">/effacer messages \[nombre]</mark>. Cela supprimera alors le nombre de messages que vous aurez renseigné dans la slash commande.

Vous avez aussi 2 options à votre disposition :

* <mark style="color:orange;">\[recherche]</mark> pour supprimer des messages contenant un mot défini.
* <mark style="color:orange;">\[utilisateur]</mark> pour supprimer le nombre de messages, les plus résents, envoyés par cet utilisateur.

{% hint style="warning" %}
**DraftBot** peut supprimer des messages uniquement s'il dispose de la permission "_Gérer les messages_" sur votre serveur.
{% endhint %}

### <mark style="color:purple;">Supprimer tous les messages d'un salon</mark>

#### <mark style="color:purple;"></mark>:warning: Attention, cette action est <mark style="color:red;">**irréversible**</mark> !

La méthode pour supprimer tous les messages d'un salon est de supprimer le salon pour recréer exactement le même avec les mêmes permissions, nom, description... mais sans les messages.

Pour faire cela, vous pouvez utiliser la slash commande <mark style="color:orange;">/effacer channel</mark>. Si vous souhaitez vider un salon autre que celui où vous faites la commande, utilisez l'option <mark style="color:orange;">\[salon]</mark>.

{% hint style="warning" %}
**DraftBot** peut supprimer tous les messages d'un salon uniquement s'il dispose des permissions "_Gérer les messages_" et "_Gérer les salons_" sur votre serveur.
{% endhint %}

### <mark style="color:purple;">Supprimer les messages d'une conversation</mark>

Si vous avez une discussion indésirable sur votre serveur, nul besoin de supprimer tous les messages jusqu'à cette conversation. Vous pouvez alors utiliser la slash commande de **DraftBot** <mark style="color:orange;">/effacer conversation \[premier\_message] \[dernier\_message]</mark>.

> Vous pouvez compléter les cases de messages avec le lien du message ou son identifiant. Pour savoir comment trouver un identifiant, rendez-vous sur cette page : [Récupérer un identifiant](../autres/recuperer-un-identifiant.md)

{% hint style="warning" %}
**DraftBot** peut supprimer une conversation uniquement s'il dispose de la permission "_Gérer les messages_" sur votre serveur.
{% endhint %}

### <mark style="color:purple;">Copier un ou des messages</mark>

Si vous souhaitez copier un message venant d'un utilisateur dans un autre salon (ou dans le même salon), vous pouvez utiliser la slash commande <mark style="color:orange;">/copier \[salon] \[premier\_message]</mark>.

Si vous voulez copier plusieurs messages à la fois, alors vous pouvez utiliser en plus l'option <mark style="color:orange;">\[dernier\_message]</mark>.

> Vous pouvez compléter les cases de messages avec le lien du message ou son identifiant. Pour savoir comment trouver un identifiant, rendez-vous sur cette page : [Récupérer un identifiant](../autres/recuperer-un-identifiant.md)

{% hint style="warning" %}
**DraftBot** peut copier un ou des messages uniquement s'il dispose des permissions "_Gérer les webhooks_" et "_Gérer les messages_" sur votre serveur.
{% endhint %}

### <mark style="color:purple;">Déplacer un ou des messages</mark>

Il est possible avec **DraftBot** de déplacer un message dans un autre salon s'il n'est pas à sa place. Pour cela, vous pouvez utiliser la slash commande <mark style="color:orange;">/move \[salon] \[premier\_message]</mark>.

Si vous voulez déplacer plusieurs messages à la fois, alors vous pouvez utiliser en plus l'option <mark style="color:orange;">\[dernier\_message]</mark>.

> Vous pouvez compléter les cases de messages avec le lien du message ou son identifiant. Pour savoir comment trouver un identifiant, rendez-vous sur cette page : [Récupérer un identifiant](../autres/recuperer-un-identifiant.md)

{% hint style="warning" %}
**DraftBot** peut copier un ou des messages uniquement s'il dispose des permissions "_Gérer les webhooks_" et "_Gérer les messages_" sur votre serveur.
{% endhint %}

### <mark style="color:purple;">Citer un message</mark>

Si vous devez répéter plusieurs fois votre message sur votre serveur, alors **DraftBot** dispose d'une fonctionnalité faite pour vous ! Vous pouvez alors citer un message avec <mark style="color:orange;">/citer \[message]</mark>.

> Vous pouvez compléter les cases de messages avec le lien du message ou son identifiant. Pour savoir comment trouver un identifiant, rendez-vous sur cette page : [Récupérer un identifiant](../autres/recuperer-un-identifiant.md)

Si vous voulez citer un message d'un autre salon, vous pourrez alors utiliser l'option <mark style="color:orange;">\[salon]</mark>.

{% hint style="warning" %}
**DraftBot** peut citer un message uniquement s'il dispose de la permission "_Gérer les messages_" sur votre serveur.
{% endhint %}

### <mark style="color:purple;">Sauvegarder une conversation</mark>

Vous pouvez sauvegarder une conversation avec la slash commande <mark style="color:orange;">/sauvegarder conversation \[premier\_message] \[dernier\_message]</mark>.

Il vous suffira ensuite de la télécharger sur votre ordinateur pour l'ouvrir dans votre explorateur et pouvoir revoir la discussion.

Si vous souhaitez supprimer les messages concernés après la sauvegarde, vous pouvez ajouter l'option <mark style="color:orange;">\[supprimer\_conversation]</mark> en sélectionnant ensuite "Oui".

{% hint style="warning" %}
**DraftBot** peut sauvegarder une conversation uniquement s'il dispose de la permission "_Gérer les messages_" sur votre serveur.
{% endhint %}
