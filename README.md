# Comandos GIT personal

Comandos para facil acceso personal

[by @RouterUIZ007]

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

## Eliminar comiit remoto
### reset hasta al commit <commit> válido
```git
git reset <commit> --hard
```
### nuevo push con la opción -f para forzar la sobreescritura del historial
```git
git push -f origin master
```

## Fuentes
* [Eliminar comiit remoto](https://es.stackoverflow.com/questions/624/c%C3%B3mo-eliminar-commits-del-historial-que-ya-fueron-subidos-al-origen)
