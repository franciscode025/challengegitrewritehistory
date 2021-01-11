# THE Ultimate Hello World program

This program does exactly what it says





Etapes suivies pour modifier l'historique:

git rebase -i

Dans vim, j'ai choisi :
- "reword" pour le commit 3
- couper+coller pour changer l'ordre des commits 2 et 3
- "edit" pour changer l'auteur du commit 5, suivi d'un git commit --amend --author="Me, the ..."
- "drop" pour effacer le commit 6
- "reword" pour changer le message du commit 7
- "fixup" pour les commit 8 et 9, afin de garder leurs contenus mais pas les messages

Et enfin, j'ai fait un commit --amend --reuse-message=<hash> pour réutiliser le message du commit 10 dans le 11.


Merci pour ce petit challenge Mohamed.
