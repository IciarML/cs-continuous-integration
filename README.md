# Ejemplo de Integración Continua con GitHub Actions


Este proyecto ofrece una Calculadora hecha en Java


##


## Ejercicio 2


El proyecto solo pasa los tests en Java 21, en las versiones 11 y 17 falla. Probablemente falle porque el archivo pom.xml del proyecto Maven especifica que necesita Java 21, y al intentar ejecutarlo con Java 11, Maven da un error de compilación.


`<properties>`

   `<project.build.sourceEncoding>UTF-8</project.build.sourceEncoding>`
		
   `<maven.compiler.source>21</maven.compiler.source>`
		
   `<maven.compiler.target>21</maven.compiler.target>`
		
   `<junit.version>6.0.1</junit.version>`
		
`</properties>`


<img width="650" alt="image" src="https://github.com/user-attachments/assets/fd45f2c3-7cbc-40fa-8489-ac6f28d649d8" />
