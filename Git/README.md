# Comandos de Git
## Comandos iniciales de Git
+ Para visualizar los directorios/archivos que contengan una carpeta/directorio se usa el siguiente comando:
```Shell
ls
```

+ Para visualizar en que ruta/unidad de nuestro sistema está posicionado el terminal, usamos el siguiente comando:
```Shell
pwd
```

+ Para iniciar un proyecto nuevo, usando a GIT, usamos el siguiente comando:
```Shell
git init
```

+ Para clonar el repositorio en nuestra máquina local se usa el siguiente comando:
```Shell
git clone [la url del repositorio a clonar]
```

+ Para ver el estado del repositorio se usa el siguiente comando:
```Shell
git status
```

+ Para ver los commits que se han realizado, se usa el siguiente comando:
```Shell
git log
```

+ Para revertir o borrar los ultimos cambios, se usa el siguiente comando:
```Shell
git checkout [nombre del archivo o proyecto]
```

+ Para ver las diferencias de los cambios realizados en el archivo/proyecto, se usa el siguiente comando
```Shell
git diff [nombre del archivo/proyecto]
```

+ Para ver la rama (branch) del archivo/proyecto a la cuál estamos, se usa el siguiente comando:
```Shell
git branch
```

+ Para agregar una rama en nuestro archivo/proyecto, usamos el siguiente comando:
```Shell
git branch [nombre del archivo nuevo/proyecto nuevo]
```

+ Para cambiar de rama (branch) usamos el siguiente comando:
```Shell
git checkout [nombre de la rama del archivo/proyecto]
```

## Comandos para subir al repositorio (Servidor).
1. Primero debemos ver el estado de nuestro repositorio.
```Shell
git status
```

2. Debemos de agregar el nuevo/modificado estado, con el siguiente comando:
```Shell
git add [nombre completo y ruta del archivo tal cómo esta escrito]
```

2.1 Para agregar **TODOS** los cambios, se usa el siguiente comando:
```Shell
git add .
```

2.2 También se puede agregar los cambios en un archivo proyecto en específico:
```Shell
git add [nombre del archivo o proyecto]
```

3. Una vez que se aha agregados los cambios, se puede hacer el commit con el siguiente comando:
```Shell
git commit -m "[aquí va un mensaje que va clarificando lo que se realizó]"
```

4. Una vez que se tenga el commit, ya se puede realizar el push para ver los cambios.
```Shell
git push origin [el nombre de la rama]
```
