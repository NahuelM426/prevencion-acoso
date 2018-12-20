
[![Waffle.io - Columns and their card count](https://badge.waffle.io/NahuelM426/prevencion-acoso.svg?columns=backlog)](https://waffle.io/NahuelM426/prevencion-acoso)
[![Build Status](https://travis-ci.org/NahuelM426/prevencion-acoso.svg?branch=master)](https://travis-ci.org/NahuelM426/prevencion-acoso)

# Prevención acoso

# Software necesario

## Explicar aquí cómo instalar lo siguiente:
* JDK 1.8

## Instalar open Java 8 en Ubuntu
  Ejecute los siguientes comandos para instalar Java 8 en Ubuntu y LinuxMint.
  ``` 
    sudo apt-get install openjdk-8-jre
  ``` 

   
 
## Maven
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


## MySQL
  La versión corta de la instalación es simple:
  ``` 
  sudo apt-get update
  sudo apt-get install mysql-server
  mysql_secure_installation
  ``` 
## Eclipse
  Para descarga Eclipse es necesario diregice a la pagina oficial de Eclipse
  ![image](https://user-images.githubusercontent.com/43456293/50297234-13aab380-045b-11e9-880e-423ab231ce2e.png)
  donde te aperecera para descagerlo tento para linix y Windows le das al boton Descagar.
  una ves descagado vas la carteta donde lo descagaste y clip derecho extraer aqui 
  vas a ver una archivo llamado (eclipse.inst) le das clip y seguis los procedimientos 
  Para Mas Detalles Dirigirce
  https://www.eclipse.org/downloads/index.php

# Configuración del entorno
## Crear la base de datos.
  Deves esta en una consola 
  ``` 
  .abrir Mysql -u root -proot
  .create database prevencionAcoso;
  .use prevencionAcoso;
  ``` 
## Cargar los datos iniciales.
 
  ir a la consola 
  ``` 
  show tables;
  select * from Telefono;
   ``` 
## Importar el proyecto en Eclipse.
  ---
  Para crear una proyecto nuevo
  Abrir Eclipse a la Izquierda arriba hay menu llamado File Entras 
  Te dirigis a donde deci Import ( te abre una nueva) hace clip en Mave y selecciona Existing Maven Projects
  Te abre una nueva ventana donde en la parte superior derecha veras un boton (Browse) y vas a donde hiciste el clon de         proyecto

  Como ejectuar los tesp
  
  --- 

