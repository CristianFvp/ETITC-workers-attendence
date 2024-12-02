CREATE TABLE Materias (
    ID_Materia VARCHAR(10) PRIMARY KEY,
    materia VARCHAR(100)
);

CREATE TABLE Especialidades (
    ID_Especialidad VARCHAR(10) PRIMARY KEY,
    especialidad VARCHAR(100)
);

CREATE TABLE Empleados (
    ID_Empleados VARCHAR(10) PRIMARY KEY,
    nombre VARCHAR(50),
    apellido VARCHAR(50),
    numero_de_documento VARCHAR(20),
    genero VARCHAR(10),
    edad INT,
    estado_civil VARCHAR(20),
    direccion_de_vivienda VARCHAR(100),
    telefono VARCHAR(15),
    correo_electronico VARCHAR(100),
    nivel_de_educacion VARCHAR(50),
    sigue_estudiando VARCHAR(3)
);

CREATE TABLE Contratos (
    ID_Contrato VARCHAR(10) PRIMARY KEY,
    ID_Empleados VARCHAR(10),
    cargo VARCHAR(50),
    departamento VARCHAR(50),
    horario VARCHAR(20),
    salario DECIMAL(10,2),
    tipo_de_contrato VARCHAR(20),
    anos_experiencia INT,
    fecha_ingreso DATE,
    FOREIGN KEY (ID_Empleados) REFERENCES Empleados(ID_Empleados)
);

