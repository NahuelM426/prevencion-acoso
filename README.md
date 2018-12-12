
[![Waffle.io - Columns and their card count](https://badge.waffle.io/NahuelM426/prevencion-acoso.svg?columns=backlog)](https://waffle.io/NahuelM426/prevencion-acoso)
[![Build Status](https://travis-ci.org/ingsw-sarmiento/libro-matriz-digital.svg?branch=master)](https://travis-ci.org/ingsw-sarmiento/libro-matriz-digital)

# Prevención acoso

## Software necesario

Explicar aquí cómo instalar lo siguiente:
* JDK 1.8
Paso 1 - Instalar Oracle Java 8 en Ubuntu
  Debe habilitar un repositorio adicional en su sistema para instalar Java 8 en Ubuntu VPS. Después de eso, instale Oracle Java   8 en un sistema Ubuntu usando apt-get. Este repositorio contiene un paquete llamado oracle-java8-installer, que no es un       paquete Java real.
  
  Ejecute los siguientes comandos para instalar Java 8 en Ubuntu y LinuxMint.
  
    sudo add-apt-repository ppa: webupd8team / java
    sudo apt-get update
    sudo apt-get install oracle-java8-installer
 Paso 2 - Verificar la instalación de Java
   El repositorio de apt también proporciona el paquete oracle-java8-set-default para configurar Java 8 como su versión          predeterminada de Java. Este paquete se instalará junto con la instalación de Java. Para asegurarse de ejecutar debajo        del comando.
   
   sudo apt-get install oracle-java8-set-default
   
   verifiquemos la versión instalada usando el siguiente comando.
   java -version

   versión java "1.8.0_191"
   Java (TM) SE Runtime Environment (compilación 1.8.0_191-b12)
   VM de servidor de 64 bits de Java HotSpot (TM) (compilación 25.171-b12, modo mixto)
   
 
* Maven
  Instalar Apache Maven en Ubuntu con Apt
  
   Comience por actualizar el índice del paquete:
    
    sudo apt update
  
  A continuación, instale Maven escribiendo el siguiente comando:
  
    sudo apt install maven
    
  Verifique la instalación ejecutando el mvn -versioncomando:
  
    mvn -version
  


* MySQL
  La versión corta de la instalación es simple:
  
  sudo apt-get update
  sudo apt-get install mysql-server
  mysql_secure_installation

* Eclipse
  Como descargar Eclipse  
  ir https://www.eclipse.org/downloads/index.php

## Configuración del entorno

Explicar aquí cómo hacer lo siguiente:
* Crear la base de datos.
  Deves esta en una consola 
  
  .abrir Mysql -u root -proot
  .create database nombreDeBase;
  .use nombreDeBase;
  
* Cargar los datos iniciales.
  ir a la Class DataGenerator 
    Ej: Telefono telefono = new Telefono();
	    	telefono.setNombre("Atención para mujeres en situación de violencia");
	    	telefono.setDescripcion("Si vos o alguien que conocés vive alguna situación de violencia, llamá gratis al 144 o buscá         algún centro de atención cercano.");
      	telefono.setNumero("144");
        
        telefonosHome.saveOrUpdate(telefono);
* Importar el proyecto en Eclipse.
  Entrar A Eclipse
  Ir A File 
      Import
      Abri la carpeta Maven (Existing Maven Projects)
      

