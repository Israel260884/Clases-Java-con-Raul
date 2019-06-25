# Comandos de consola.

+ Para visualizar los directorios/archivos que contengan una carpeta/directorio se usa el siguiente comando:
```Shell
ls
```

+ Para visualizar en que ruta/unidad de nuestro sistema está posicionado el terminal, usamos el siguiente comando:
```Shell
pwd
```

+ Para limpiar la pantalla y ver lo que estamos escribiendo, usamos el siguiente comando:
```Shell
clear
```

+ Para ver las características de un comando, se usa el siguiente:
```Shell
man [nombre del comando]
```

+ Para agregar un archivo nuevo dentro de una carpeta, se usa el siguiente comando:
```Shell
touch [nombre del archivo nuevo]
```

+ Para cambiar de directorios o carpetas superiores, se escribe el siguiente comando:
```Shell
cd ..[nombre de la carpeta o unidad]
```

+ Para ingresar en un directorio/carpeta actual se escribe el siguiente comando:
```Shell
cd [nombre del directorio/carpeta/unidad]
```

+ Para retroceder un directorio/carpeta de la actual, se escribe el siguiente comando:
```Shell
cd  -[nombre del directorio/carpeta/unidad]
```

+ Para ingresar en un directorio en específico, se escribe el siguiente comando:
```Shell
cd [nombre del directorio 1/nombre del directorio 2/ nombre del directorio 3/.../nombre del directorio n]
```

+ Para crear un nuevo directorio/carpeta, se usa el siguiente comando:
```Shell
mkdir [nombre del nuevo directorio]
```
> Hay que tener en cuenta que lo crea dentro del **mismo directorio/carpeta**, asi que si deseamos crearlo en otra **ruta diferente**, se debe de incluir la ruta completa.
```Shell
mkdir /ruta del nuevo directorio 1/ ruta del nuevo directorio 2/.../ ruta del nuevo directorio n/...
```

+ Para mover un directorio/carpeta sin copiarlo, usamos el siguiente comando:
```Shell
mv [ruta origen] [nombre del archivo con extension] [ruta destino] [nombre del archivo con extension]
``` 

+ Para borrar un directorio o archivo, usamos el siguiente comando:
```Shell
rm [nombre del archivo con su extensión]
```

+ Si queremos borrar más archivos dentro del mismo directorio, se usa así:
```Shell
rm -r /nombre del directorio/
```

+ Para copiar un archivo, debemos primero indicar la ruta de origen del archivo a copiar y después indicar la ruta de destino **en ese orden**, lo usamos de la siguiente manera:
```Shell
cp [archivo origen/archivo con su extension /ruta del archivo destino/archivo con su extensión]
```
