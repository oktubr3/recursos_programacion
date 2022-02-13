## Subir archivo a Github
```
git init
git add "Nombre del archivo" o git add .    // Añade todo
git status -s   // Para verificar si se agrego el archivo
git commit -m "Comentario"
```
- Entrar a Github -> Nuevo Repositorio
```
git remote add origin "liga"
git push origin master
```

## Actualizar de local a Github
```
git add .
git commit -m "comentartio"
git push
```

## Actualizar de Github a local
- editar en github
- iniciar bash en carpeta
```
git pull
```

## Tags Especificar versiones
```
git tag v1.0.0 -m "comentario"
git push --tags
```

## Verificar los commit
```
git log --oneline
```

## Ejecutar por ejemplo si se nos Borró una carpeta por accidente
```
git checkout --.
```

## Restaurar borra lo nuevo "forma local"
```
git reset --hard    // Commit de referencia (No debe llevar ni parentesis ni corchetes)
```

## Modificar comentario de un commit
```
git commit --amend 
:i
- Editar nombre
- ESC
:wq
```

### RAMAS
## Crear rama
```
git branch branchName
git log --oneline o git branch  // Confirma visualmente la creación de la rama
```

## Moverse de Rama
```
git checkout    // nombre de la rama a la que se mueve "No debe llevar ni parentesis ni corchetes"
git branch  // para confirmar la ubicaciond e la rama
```

## Moverse a master
```
git checkout master
```

## Unir ramas
```
git merge (nombre de la rama a unir "No debe llevar ni parentesis ni corchetes")
```