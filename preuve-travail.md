une histoire incroyable commit screenshot :
>![alt text][screenshot-commit]

commande pour revenir sur une étape antérieure :

>```git checkout <ref commit>```

commande pour revenir sur la dernière version de la branche actuelle :

>```git checkout <branche>```

commande pour reset le HEAD de la branche sur un commit précis :
- avec les modifications actuelles

>```git reset --soft <ref commit>```

- sans les modifications actuelles

>```git reset --hard <ref commit>```

V1.0 tag screenshot :
>![alt text][screenshot-tag]

[screenshot-commit]: https://github.com/cnmichel/memo-git/blob/main/screen_git.png
[screenshot-tag]: https://github.com/cnmichel/memo-git/blob/main/screen_tag.png