# Dojo Multi-Threading

## Fonctionnement

Ce dojo est composé de petits exercices à réaliser prévus séquentiellement mais qui peuvent être réussis dans l'ordre désiré.

## Exercices

1. Créez un `List<Thread>` qui chacun attendent une durée aléatoire avant de se terminer. Le process se termine lorsque les threads associés sont terminés.
2. Créez un `ThreadPool` qui peuple une collection concurrente avec au moins 1 millions de valeurs.
3. A partir du code de l'exercice suivant, écrit un code dans le process (`Main`) qui fait la somme des valeurs de la liste peuplée par les threads pendant qu'ils la peuplent. Le programme se termine une fois la somme des valeurs affichée.