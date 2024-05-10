# Sistema-de-Transporte-Masivo-Base-de-Datos-PostgreSQL
PostgreSQL – Es un motor de Base de Datos. Es una entidad modelo relacional. 
Tres conceptos importantes entorno a una base de Datos son:
-	Motor
-	Lenguaje 
-	Servidor
El motor es el que permite estructurar toda la información dentro de un servidor. El servidor es básicamente un equipo que tiene un procesador y una ram.
La base de Datos es como uno accede usando el lenguaje estándar siendo SQL.
# PostgreSQL soporta distintos tipos de Datos: 
### Principales
-	Númericos
-	Monetarios
-	Texto 
-	Binarios ( 1 o 0)
-	Fecha/Hora
-	Boolean ( True or False)
  
### Especiales 
-	Geométricos (x y y permiten calcular distancia)
-	Dirección de Red (Almacena Ips y permite realizar cálculos de máscaras de red)
-	Texto tipo bit ( Permite hacer cálculos  en otros sistemas  como hexadecimal o binario)
-	XML, JSON ( Apis se comunicacan usando el lenguaje XML o Json)
-	Arreglos ( Se refiere a vectores y matrices y se puede operar con ellos.

# Introducción del Proyecto

El presente proyecto tiene como objetivo crear un sistema de Transporte Masivo utilizando PostgreSQL con el fin de relacionar. Pensar en la cantidad enorme de personas que mueve, trenes que tiene, todos los distintos trayectos, toda la información de las personas que están en los trenes, en las estaciones. 
Modelación del Sistema y todos sus componentes  
## 1.	Identificación de entidades
Las entidades establecidas para la base de Datos fueron:
- Pasajeros
-	Estación
-	Trenes
-	Viaje ( la relación entre las personas y los trayectos se llama viaje. Me dice que personas están montadas en que trayecto. 
-	Trayectos (nos asocia la relación entre estación y tren) Ya que un tren va de una estación a otra. Un trayecto no necesariamente tiene pasajeros
## 2.	Identificación de los atributos
Los atributos establecidos para la entidad Pasajero fueron los siguientes
-	Id
-	Nombre
-	Dirección_residencia
-	Fecha_nacimiento
### Los atributos establecidos para la entidad estación fueron los siguientes
-	Id
-	Nombre
-	Dirección
### Los atributos establecidos para la entidad tren fueron los siguientes
-	Id
-	Modelo
-	capacidad
###	Los atributos establecidos para la entidad viaje fueron los siguientes
-	Id
-	Id_pasajero
-	Id_trayecto
-	Inicio
-	Fin

