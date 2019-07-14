# Portafolio de proyectos de clases Forge

## Para crear un repo

```bash
$ git init
```
## Pasos para guardar cada vez que termino un feature importante

```bash
$ git add --all
$ git commit -m "Mensaje del commit"
$ git push origin master
```

## Para poder pushear a remoto (Github)

```bash
$ git remote -v     # para poder ver si tienes la ruta de tu repositorio de github

# si no la tienes
$ git remote add origin <URL>
$ git push -u origin master
```

## Para usarlo en otra compu en la que no tengo el proyecto

```bash
$ git clone https://github.com/LuisaLicla/portafolio-forge.git
# Si ya tienes el proyecto, para jalar la ultima version
$ git pull origin master
```