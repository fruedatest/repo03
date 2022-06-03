# Ejercicio 3: FAST FORWARD
## Crea un directorio llamado repo03, con un fichero readme.md vacío, haz un commit y subelo al repositorio remoto llamado repo03

```
	$ git init repo03
    $ nano readme.md
    $ git status
    $ git add readme.md
    $ git commit -m "commit001"
    $ git remote -v
    $ git remote add origin https://github.com/fruedatest/repo03.git
    $ git branch -M main
    $ git push -u origin main
```

## Crea una rama con tu nombre y fecha para editar el archivo
```
    $ git branch francisco03062022
    $ git checkout francisco03062022
```

## Haz un commit en tu rama
```
    $ git commit -m "commit011francisco"
```

## Fusiona tu rama con master

