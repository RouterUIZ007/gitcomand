# Comandos GIT (uso personal personal)

Comandos para facil acceso personal

[by @RouterUIZ007]
## Agregar a repo (new repo and project created)
### 
```git
git init
git add archivo_ruta
git commit -m "nombre_commit"
git branch -M nombre_rama
git remote add origin [ruta de repo.git]
git push -u origin nombre_rama
```

## Hacer commits
### Agregar cambios
```git
git add archivo_ruta
```
### Agregartodos los cambios
```git
git add .
```
### crear commit
```git
git commit -m "nombre_commit"
```
### crear commit --no-verify
```git
git commit --no-verify -m "nombre_commit"
```
### hacer push
```git
git push origin nombre_rama
```
#### recomendacion hacer pull despues
```git
git pull origin nombre_rama
```
## Crear Ramas
### Crear rama
```git
git branch nombre_rama
```
### cambiar a rama
```git
git checkout nombre_rama
```
### crear y cambiar a rama
```git
git checkout -b nombre_rama
```
## ver estatus y commits
### ver estatus
#### ver stages realizados
```git
git status
```
### ver commits en general
```git
git log
```
### ver resumen de commits 
```git
git log --oneline
```

## Eliminar ramas
### normal
```git
git branch -d nombre_rama
```
### forzar
```git
git branch -D nombre-rama
```
### eliminar una remota
```git
git push origin :nombre-rama
```
## Fuentes

* [Eliminar ramas locales y remotas](https://vabadus.es/blog/otros/trabajando-con-git-eliminar-ramas-locales-y-remotas)

## Eliminar commit remoto
### reset hasta al commit <commit> válido
```git
git reset num_commit --hard
```
### nuevo push con la opción -f para forzar la sobreescritura del historial
```git
git push -f origin nombre-rama
```

## Fuentes
* [Eliminar comiit remoto](https://es.stackoverflow.com/questions/624/c%C3%B3mo-eliminar-commits-del-historial-que-ya-fueron-subidos-al-origen)
