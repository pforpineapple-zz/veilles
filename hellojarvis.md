# Jarvis.io : Test (30-05-2016, Anas)

Jarvis est un assistant reminder sur Facebook Messenger.

## TEST

### OB

Très (très) sobre. Jarvis lâche un petit "Hey there" puis enchaîne directement 
sur la question "which city do you live in ?".

>Hey there, I need your timezone to get started. Which city do you live in?

Une fois la ville donnée, il donne un _design-feedback_ important en confirmant 
l'heure actuelle. Puis, il invite à tester avec une requête "copie-collable" et
un "help".

![1](images/hellojarvis.png)

### ENGAGEMENT

Plutôt bien fait. Assez sensible aux fotes d'arutrograf ("reming" ne marche
pas") mais il comprend "next tuesday" 

Le "Help" est un FAQ de CTAs. On peut avoir accès 

Aussi, la commande ne peut marcher qu'avec ses arguments. C'est à dire que 

>Remind me

renvoie le message de fail.

### JAMMABLE

 - Le Help en CTAs : Pour Facebook Users on pourraît penser à un truc similaire.
 - Feedback (équivalent current time) : L'heure n'étant pas notre requirement, 
on peut récupérer l'école ou la ville de l'utilisateur et répondre une anecdote
à son sujet.
