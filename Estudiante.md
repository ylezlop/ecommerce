# Base de datos de Estudiantes  

En MySQL se crea una tabla Estudiante que almacena datos como id, 
nombre(s), apellido paterno, apellido materno, fecha de nacimiento, edad 
y matrícula.  

## Parámetros  

* idEstudiante INT AUTO_INCREMENT PK
* nombres VARCHAR(100) NOT NULL
* apellido_paterno VARCHAR(50) NOT NULL
* apellido_materno VARCHAR(50) NOT NULL
* fecha_nacimiento DATE NOT NULL
* edad INT NOT NULL
* matricula VARCHAR(9) NOT NULL

## Código en MySQL

CREATE TABLE Estudiantes (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nombres VARCHAR(100) NOT NULL,
    apellido_paterno VARCHAR(50) NOT NULL,
    apellido_materno VARCHAR(50) NOT NULL,
    fecha_nacimiento DATE NOT NULL,
    edad INT NOT NULL,
    matricula VARCHAR(20) UNIQUE NOT NULL
);
