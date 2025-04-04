### Crear un repositorio

```shell
git init 
```

### Crear una rama (branch)

```shell
git branch <name>
git checkout -b <name>
```

### Eliminar una rama (branch)

```shell
git branch -D <name>
```

### Activar o cambiar a una rama (branch)

```shell
git checkout <name>
```

### Preparar los cambios a guardar

```shell
git add <name>
git add -A 
git add .
git add *
```

### Guardar los cambios 

```shell
git commit
git commit -m "Mensaje Descriptivo de los cambios"
```

### Fusionar ramas (merge)

```shell
git merge <branch>
```

### Bajar cambios repositorio remoto

```shell
git pull <remote> <branch>
```

### Subir cambios repositorio remoto

```shell
git push <remote> <branch>
```

### Añadir repositorio remoto

```shell
git remote add <name> <url>
```

### Modificar repositorio remoto

```shell
git remote set-url <name> <url>
```

### Eliminar vinculo repositorio remoto

```shell
git remote rm <name>
```