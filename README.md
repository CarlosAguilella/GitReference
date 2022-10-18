## Git config (user.name, user.email)

El comando `git config` sirve para mostrar el nombre o email 
de destinatario del archivo o carpetas en los que se trabaja.

```
git config
```

## Git commit

El comando `git commit` permite realizar una copia (o foto) 
del archivo actual en el que se esta trabajando. Se puede
enteder como el comando "guardar", git hub no modificara
estos cambios acaso que se vuelva a ejecutar este comando.

```
git comit
```

## git branch  (-f)

El comando `git branch` sirve para crear "ramas" de programación
alternativas, es decir, crea una versión del proyecto actual desde
el que trabajar sin alterar el programa principal. 

```
git branch
```


## git bisect

`git bisect` significa partir por la mitad y es justamente lo que va a hacer este comando: ir dividiendo toda la pila de commits en dos partes, una parte de la pila contendrá el error y otra parte no. Aunque algo así lo podríamos hacer de forma manual con git checkout esta herramienta es mucho más eficiente.

```
git bisect
```

## git checkout  (-b)

El comando `git checkout` sirve para "actualizar" la rama main
con la rama seleccionado, un ejemplo: Estando en la rama main queremos 
actualizarla con la rama Juanito, el comando seria git checkout -b Juanito.

```
git checkout -b
```

## git merge

El comando `git merge` sirve para fusionar la rama actual (en la que nos encontremos trabajando) y la rama seleccionada, por ejemplo: Si estamos en la rama master y deseamos implementar los cambios de la rama Parche emplearemos el comando git merge parche.

```
git merge
```

## git rebase

El comando `git rebase` se emplea para "actualizar" la master(o la base) del programa actual tras diferentes merge a lo largo de la vida del programa. Esto se hace para mejorar la visualización del programa.

```
git rebase
```

## git cherry-pick

El comando `git cheerry-pick` aplica los cambios introducidos en un merge anterior, es decir, si hemos realizado algun cambio en el master o rama del programa y decidimos descartar los cambios, podemos restaurar los cambios implementados anteriormente en algun git merge.

```
git cherry-pick
```

## git switch

`git switch` para cambiar entre ramas y poder crearlas si no existen. 

```
git switch
```

## git switch

`git tag` sirve básicamente como una rama firmada que no permuta, es decir, siempre se mantiene inalterable. Sencillamente es una cadena arbitraria que apunta a un commit específico. Puede decirse que un tag es un nombre que puedes usar para marcar un punto específico en la historia de un repositorio.

```
git tag
```

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



