# git-iv

Plugin para git para usar en la asignatura IV


## Instalación

Prerrequisitos: Perl y git instalados (Perl estará instalado en cualquier Linux
o Mac). `wget` estará probablemente instalado también en cualquiera de estos sistemas.

```
> cd ~/bin # O cualquier otro directorio en el path de ejecución
> wget https://raw.githubusercontent.com/JJ/IV/master/scripts/git-iv #O bajar el URL a ese directorio de cualquier otra manera
> chmod +x git-iv
```

Ya se puede usar a continuación. Por ejemplo

```
> git iv    # Para imprimir los subcomandos
> git iv -h # Ídem
> git iv objetivo 0    # Crea la rama del objetivo 0
> git iv sube-objetivo # Hace push del objetivo
```
