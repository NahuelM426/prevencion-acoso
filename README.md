
[![Waffle.io - Columns and their card count](https://badge.waffle.io/NahuelM426/prevencion-acoso.svg?columns=backlog)](https://waffle.io/NahuelM426/prevencion-acoso)
[![Build Status](https://travis-ci.org/NahuelM426/prevencion-acoso.svg?branch=master)](https://travis-ci.org/NahuelM426/prevencion-acoso)

# Prevención acoso

## Software necesario

Explicar aquí cómo instalar lo siguiente:
* JDK 1.8
Paso 1 - Instalar open Java 8 en Ubuntu
  Debe habilitar un repositorio adicional en su sistema para instalar Java 8 en Ubuntu VPS. Después de eso, instale Java   8 en un sistema Ubuntu usando apt-get.
  
  Ejecute los siguientes comandos para instalar Java 8 en Ubuntu y LinuxMint.
  ``` 
    sudo apt-get install openjdk-8-jre
  ``` 

   
 
* Maven
  Instalar Apache Maven en Ubuntu con Apt
  
   Comience por actualizar el índice del paquete:
  ```  
    sudo apt update
  ``` 
  A continuación, instale Maven escribiendo el siguiente comando:
 ``` 
    sudo apt install maven
 ```  
  Verifique la instalación ejecutando el mvn -versioncomando:
  ``` 
    mvn -version
  ``` 


* MySQL
  La versión corta de la instalación es simple:
  ``` 
  sudo apt-get update
  sudo apt-get install mysql-server
  mysql_secure_installation
  ``` 
* Eclipse

  Como descargar Eclipse  
  ir https://www.eclipse.org/downloads/index.php

## Configuración del entorno

Explicar aquí cómo hacer lo siguiente:
* Crear la base de datos.
  Deves esta en una consola 
  ``` 
  .abrir Mysql -u root -proot
  .create database prevencionAcoso;
  .use prevencionAcoso;
  ``` 
* Cargar los datos iniciales.
  ir a la consola 
  ``` 
  show tables;
  select * from Telefono;
   ``` 
* Importar el proyecto en Eclipse.
  ---
  Para crear una proyecto nuevo
  Abrir Eclipse a la Izquierda arriba hay menu llamado File Entras 
  Te dirigis a donde deci Import ( te abre una nueva) hace clip en Mave y selecciona Existing Maven Projects
  Te abre una nueva ventana donde en la parte superior derecha veras un boton (Browse) y vas a donde hiciste el clon de         proyecto

  Como ejectuar los tesp
  
  --- 

