# Descripcion de todas las relaciones

**Relación:** Es una asociación entre dos entidades. Por lo general, un verbo o preposición que conecta dos entidades implica una relación.

Existen tres tipos de Relaciones:
- Uno a Uno (1 : 1)

    Uno | Uno
    ----------- | ---------- 
    País | Jefe de Gobierno
    Vehículo | Patente
    Persona | DNI
    Sucursal | Automóvil
    País | Bandera

- Uno a Muchos (1 : n)

    Uno | Muchos
    ----------- | ---------- 
    Sucursal | Empleados
    Genero | Canciones
    País | Personas
    Productora | Películas
    Rango | Soldados

- Muchos a Muchos (n : m)
    - Equipos / Componentes
    - Peliculas / Actores
    - Peliculas / Salas de cine
    - Artículos / Proveedores
    - Cursos / Alumnos


# ¿Qué es un SGBD?

El **SGBD** es un Sistema de Gestión de Base de Datos, siendo un software que permite a los usuarios poder almacenar, consultar y manipular la información.

Para que el acceso a los datos por parte del usuario sea lo más rápido posible, al momento de realizar una petición de lectura, modificación, ingreso o eliminación de datos lógicos, el SGBD la transforma en comandos de bajo nivel que entiende el sistema de archivos del sistema operativo, que será quien realice finalmente la E/S al dispositivo de almacenamiento mediante los métodos de acceso definidos en el esquema interno de la base de datos.

Por otro lado, el SGBD debe traducir las consultas y actualizaciones de un lenguaje no procedural como SQL en una secuencia de operaciones eficientes de nivel físico.

El uso de un SGBD no solo tiene una mejor integración de los datos, sino mayor y mejor seguridad de estos, haciendo que el trabajo de los programadores sea más eficiente, ya que requiere menos trabajo, pudiendo realizar consultas más ágiles gracias al optimizador automático del SGBD.

Por último, mencionar y aclarar que el SGBD (como se pudo inferir anteriormente) no es una base de datos persé, sino solo un componente de esta.
Un **Sistema de Base de Datos** estaría formada de: Base de datos (datos + catálogo) + SGBD + Usuarios + Aplicaciones + Hardware


# Cuáles son los más famosos?
- Microsoft Access
- Microsoft SQL Server
- MySQL
- Oracle Database


# ¿En qué se diferencian las base de datos relacionales con las no relacionales?

**Bases de datos relacionales:** Contienen datos almacenados en estructuras formadas por tablas relacionadas entre sí, tienen un software especial para operarlas que se llama sistema de gestión de base de datos y actúa como interface entre los usuarios y los datos. En una base de datos relacional, cada fila de la tabla es un registro con un ID único llamado clave única (PK = Primary Key). Las columnas de la tabla contienen atributos de los datos y, por lo general, cada registro tiene un valor para cada atributo, lo que facilita el establecimiento de las relaciones entre los puntos de datos. La mayor ventaja de este tipo de base de datos es la escalabilidad.

**Bases de datos no relacionales:** La principal diferencia con las primeras, es que almacenan sus datos en forma no tabular, ya que pueden basarse en estructuras de datos como documentos. Un documento puede ser muy detallado y contener una variedad de diferentes tipos de información en diferentes formatos. Esta capacidad para organizar varios tipos de información en paralelo hace que las bases de datos no relacionales sean mucho más flexibles que las bases de datos relacionales.
