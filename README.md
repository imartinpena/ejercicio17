Instrucciones para ejecutar el programa:

1º Paso: Empaquetar
	- mvn clean package

2º Paso: Ejecutar
	- Añadir contacto: java -cp target/libreta-1.0-SNAPSHOT.jar org.pr2.App add "Juan García Pérez" 65432145
	- Mostrar libreta: java -cp target/libreta-1.0-SNAPSHOT.jar org.pr2.App show
