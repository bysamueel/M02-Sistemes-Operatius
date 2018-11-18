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

#uname -a  
  #Linux 3.2.45-smp i686  
    
      - Linux : nombre del kernel  
      - 3.2.45-smp : nº versión del kernel  
      - i686 : tipo de hardware de la màquina  

3. **¿Cómo podemos mostrar el hardware detectado por el kernel?** Por favor, muestre el resultado del comando.

  #lspci  
    
      00:00.0 Host bridge: Intel Corporation 4th Gen Core Processor DRAM Controller (rev 06)  
      00:02.0 VGA compatible controller: Intel Corp. Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller (rev 06)  
      00:03.0 Audio device: Intel Corporation Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller (rev 06)  
      00:14.0 USB controller: Intel Corporation 8 Series/C220 Series Chipset Family USB xHCI (rev 05)  
      00:16.0 Communication controller: Intel Corporation 8 Series/C220 Series Chipset Family MEI Controller #1 (rev 04)  
      00:1a.0 USB controller: Intel Corporation 8 Series/C220 Series Chipset Family USB EHCI #2 (rev 05)  
      00:1b.0 Audio device: Intel Corporation 8 Series/C220 Series Chipset High Definition Audio Controller (rev 05)  
      00:1c.0 PCI bridge: Intel Corporation 8 Series/C220 Series Chipset Family PCI Express Root Port #1 (rev d5)  
      00:1c.2 PCI bridge: Intel Corporation 8 Series/C220 Series Chipset Family PCI Express Root Port #3 (rev d5)  
      00:1c.3 PCI bridge: Intel Corporation 82801 PCI Bridge (rev d5)  
      00:1d.0 USB controller: Intel Corporation 8 Series/C220 Series Chipset Family USB EHCI #1 (rev 05)  
      00:1f.0 ISA bridge: Intel Corporation H81 Express LPC Controller (rev 05)  
      00:1f.2 SATA controller: Intel Corporation 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] (rev 05)  
      00:1f.3 SMBus: Intel Corporation 8 Series/C220 Series Chipset Family SMBus Controller (rev 05)  
      02:00.0 Ethernet controller: Realtek Semiconductor Co., Ltd. RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller (rev 06)  
      03:00.0 PCI bridge: Intel Corporation 82801 PCI Bridge (rev 41)

4. **¿Cómo podemos mostrar los módulos (controladores) realmente en uso?** ¿Qué módulo se está utilizando para la tarjeta gráfica de video?  

#lsmod   

[![Image from Gyazo](https://thumb.gyazo.com/thumb/200/eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpbWciOiJfZjVmZjBjYWUwMDkyOTMwMDllOTZjYThmMTJmNTI2MjEifQ.lb6myX18D3saXbvcDIudU1J0_JQmdmfHUs45PHGzHFc-png.jpg)](https://gyazo.com/45a5295496e7ad3d880d5d883e789929)
  
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
