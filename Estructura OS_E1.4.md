# E1. Ejercicio 4. Estructura del sistema operativo.

## Introducción

Podemos dividir el sistema operativo en las siguientes partes:
- Núcleo
- administrador de memoria
- Gestor de entrada / salida
- administrador del sistema de archivos

## Contenidos

Analicemos el comportamiento del sistema operativo en cada módulo. Usaremos los comandos de Linux para ver qué está sucediendo en un sistema operativo Linux.

## Entrega

### Núcleo

1. **¿Dónde reside el kernel en el disco?** Escriba el comando con la salida y diga exactamente dónde está el kernel.


2. **¿Cómo podemos mostrar la versión real del kernel que está cargada en nuestro sistema?** Por favor muestra el resultado del comando


3. **¿Cómo podemos mostrar el hardware detectado por el kernel?** Por favor, muestre el resultado del comando.


4. **¿Cómo podemos mostrar los módulos (controladores) realmente en uso?** ¿Qué módulo se está utilizando para la tarjeta gráfica de video?



### Administrador de memoria

1. **¿Qué es la memoria 'caché' que muestra el comando 'free -m'?** Muestra también la salida del comando


2. **¿Qué es la memoria 'swap' que muestra el comando 'free -m'?**


3. **¿Cómo maneja el administrador de memoria un problema de falta de memoria?**


4. **¿Cómo podemos mostrar el 'puntaje de memoria' real de una instancia de Gimp que se está ejecutando?**



### Administrador de entrada / salida

1. **¿Cómo podemos enumerar todas las interrupciones que conoce nuestro sistema operativo?** Mostrar también el resultado del comando


2. **En los sistemas multiprocesador, ¿cómo distribuye el sistema operativo las interrupciones de forma predeterminada?** ¿Cómo podemos cambiar el comportamiento predeterminado?


3. **¿Cómo controla un sistema operativo un dispositivo que no tiene interrupciones?** Explique el proceso


4. **¿Qué ocurrirá si dos aplicaciones desean enviar datos a través de un dispositivo de red al mismo tiempo?**



### Administrador del sistema de archivos

1. **¿Cuál es la típica estructura de carpetas de Linux? ** Describe qué es y el uso de cada carpeta.**
- bin:  
- boot:  
- dev:  
- etc:  
- home:
- lib:  
- lib64:
- lost+found:
- media:
- mnt:
- opt:
- proc:
- root:
- run:
- sbin:
- srv:
- sys:
- tmp:
- usr:
- var:

2. **¿Cómo podemos:?**
- Mueva un archivo que reside en /usr/local/src/file.md a la carpeta / opt:
- Copie un archivo que reside en /usr/local/src/file.md a la carpeta / opt:
- Mueva un archivo en /usr/file.md a / usr / local si estamos actualmente en la ruta / usr / local:
- Cree el archivo .gitignore usando el comando 'tocar' y luego intente listarlo (ls). ¿Lo que pasa?
