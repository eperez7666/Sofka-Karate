## Tabla de contenido
1. [Información general](#info-general)
2. [Tecnologías](#tecnologias)
3. [Instalación](#instalacion)
4. [Instrucciones para ejecutar los test](#ejec-test)
5. [Colaboración](#colaboracion)


### Inforación general
***
El presente proyecto utiliza el framework Karate para realizar pruebas automatizadas del API Rest "PetStore". Se realizaron cuatro casos de pruebas, que se describen a continuación. 
* Añadir una mascota a la tienda
* Consultar la mascota ingresada previamente (Búsqueda por ID)
* Actualizar el nombre de la mascota y el estatus de la mascota a “sold”
* Consultar la mascota modificada por estatus(Búsqueda por estatus)
## Tecnologias
***
Las tecnologias que se utilizaron para este proyectos son
* Máquina local, con sistema Operativo Windows 11
* [IntelliJ IDEA 2023.1.5](https://www.jetbrains.com/idea/download/?section=windows): Version 17.0.7
* [JDK](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html): Version 1.8
* [Maven](https://maven.apache.org/docs/3.9.2/release-notes.html): Version 3.9.4
* Karate: Version 1.3.1
## Instalación
***
El proyecto se encuentra en GitHub, para clonar el repositorio de debe realizar los siguientes pasos: 
```
$ cd ../path/to/the/file
$ git clone https://github.com/eperez7666/Sofka-Karate.git
```
Información adicional: Para concluir la instalación del proyecto, se debe:
```
* Abrir la aplicacion Intellij
* Ir a la opción Archivo
* Dar clic en la opción Abrir
* Elegir la carpeta que se clonó
```
## Instrucciones para ejecutar los test
* Ejecutar todas las pruebas del proyecto, se utiliza el comando:
```
mvn test
```
* Ejecutar primer caso de prueba:
```
 mvn test -Dtest=PetsRunner#firstTestCase
```
* Ejecutar segundo caso de prueba:
```
 mvn test -Dtest=PetsRunner#secondTestCase
```
* Ejecutar tercer caso de prueba:
```
 mvn test -Dtest=PetsRunner#thirdTestCase
```
* Ejecutar cuarto caso de prueba:
```
 mvn test -Dtest=PetsRunner#fourthTestCase
```
* Ubicación del reporte
```
 target/karate-reports/karate-summary.html
```

