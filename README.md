git config (user.name, user.email)
git commit
git branch  (-f)
git checkout  (-b)
git merge
git rebase
git cherry-pick
git switch
## git tag

`git tag` sirve básicamente como una rama firmada que no permuta, es decir, siempre se mantiene inalterable. Sencillamente es una cadena arbitraria que apunta a un commit específico. Puede decirse que un tag es un nombre que puedes usar para marcar un punto específico en la historia de un repositorio.

```
git tag```

## git bisect

`git bisect` significa partir por la mitad y es justamente lo que va a hacer este comando: ir dividiendo toda la pila de commits en dos partes, una parte de la pila contendrá el error y otra parte no. Aunque algo así lo podríamos hacer de forma manual con git checkout esta herramienta es mucho más eficiente.

```
git bisect
```

## git clone

El comando `git clone` es una utilidad de línea de comandos de Git que se utiliza para fijar como objetivo un repositorio existente con el fin de clonarlo o copiarlo.

```
git clone
```

## git remote add


El comando `git remote add` te permite crear, ver y eliminar conexiones con otros repositorios. Las conexiones remotas se asemejan más a marcadores que a enlaces directos con otros repositorios.

```
git remote add
```

## git pull

El comando `git pull` sirve para bajar los cambios de la repo remoto

```
git pull
```

## git push

El comando `git push` sirve para subir los cambios al repo remoto

```
git push
```



