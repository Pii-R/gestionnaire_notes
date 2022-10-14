## Remarque sur ton code

Dans un premier temps, il faut s'assurer que les variables utilisées sont bien définis avant leur appel/utilisation. Tu te retrouves par moment à utiliser des variables pas encore définies ce qui causent des erreurs

Pour tester si une liste contient des éléments privilégier len(list). La méthode sum permet d'effectuer la somme sur un itérable comme une liste ou un générateur par exemple. Par contre il faut que le type d'objet supporte les opérations de somme (méthode spéciale __add__ https://www.codingem.com/python-__add__-method/)

Mettre des f string (f"var={var}) seulement lorsqu'on passe une variable dans la chaine de caractère sinon pas la peine

Pour comparer le type d'un objet utiliser la méthode isinstance https://www.w3schools.com/python/ref_func_isinstance.asp
## Quelques conseils

Il est intéressant de poser le problème à résoudre avant d'écrire du code. Essayer de mettre en pseudo code l'architecture du code voulu. Cela permet de déceler des points importants et d'éviter de revenir pleins de fois sur son code. S'assurer que son petit bout de code fonctionne avant d'aller plus loin

Pour chaque fonction/méthode importante créée mettre systématiquement un commentaire (ou docstrings) afin d'expliquer brièvement l'utilité de la fonction

Le typing (assigner le type d'un argument à côté de son nom) est très important pour se repérer et rendre bien plus lisible
Chose qui a été faite en majorité dans le fichier `Exercice pratique.ipynb`

Bien réfléchir aux noms des variables afin de décrire au mieux ce qu'elle représente, éviter de faire des diminutifs
par exemple : nom_professeur vaut mieux que nom_prof

Si jamais vous allez plus loin il serait intéressant de regarder les guides PEP de Python (bonnes pratiques en Python), comment tester son code (chose qui est faite dans la dernière partie de l'exercice) avec le module pytest et unittest
