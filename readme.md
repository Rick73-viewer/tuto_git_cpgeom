Tuto initiation git 

Prealable. Creation d'un repo distant sur la plateforme Github 
1.  Création d'un dossier sur le pc => pour le moment un dossier classique 
2. On crée le premier fichier readme.md (qui va être la page d'acceuil de notre repo)
3. On va initialiser ce dossier classique , comme un repo local avec la commande 
```git init```

cette commande entytraîne la création d'un sous répertoire  .git, notre dossier *"classique"* local est devenu un repository au sens git du terme

4. on va *"stagger"* le fichier readme.md

```git ad readme.md```

5. on *"commit"* avec l'option message -m (qui apparaîtra dans le repo github)

![](imag/mesage_commit.png)

```git commit -m "first commit"```

6. On renomme la branche principale en main (car git en local a créer la branche master, mais githug attend main  par convention)

7. on crée le lien de notre repo local avec le repo distant 

```git remote add origin https://github.com/Rick73-viewer/tuto_git_cpgeom.git``` 

8. On *"push"* le repo local vers le distant 

```git push -u origin main```

**Conclusion**
