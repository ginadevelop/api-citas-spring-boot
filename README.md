> [!NOTE] 
> **Group Members**

 *Gina Ardila Zuñiga*

 *Esteban Mendez Martinez*

# API

API-REST basada en el modelo cliente-servidor para gestionar y persistir citas médicas en un hospital. La aplicación web (REST API) permite recibir información de pacientes y doctores a través de formularios, almacenando estos datos en una base de datos. La implementación se realiza en Java y la API ofrece operaciones CRUD (Crear, Leer, Actualizar y Eliminar) para manipular la información de manera completa y eficiente.

**También se especifica el método de rutas correspondiente**

- *Create = post* 

- *Read = get*

- *Update = put*

- *Delete = delete*

## INSTALACIÓN - CONFIGURACIÓN
Para usar el proyecto en su repositorio local, siga cuidadosamente las indicaciones, teniendo en cuenta que debe clonar el repositorio
inicialmente, luego siga las instrucciones indicadas:

- Instalar las dependencias del proyecto
```code
    mvn clean install
```
- Luego inicializar el proyecto
```code
    mvn spring-boot:run
```

## TECNOLOGIAS 

[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)]() [![Springboot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=Spring&logoColor=white)]() [![Postman](https://img.shields.io/badge/Postman-F6BB43?style=for-badge&logo=Postman&logoColor=white&labelColor=10101)]() [![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white&labelColor=101010)]() [![Github](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)]() [![Xampp](https://img.shields.io/badge/XAMPP-FB7A24?logo=xampp&logoColor=fff&style=flat-square)]()

----

#### *Doctores*
```http
  GET      /api/doctores
  GET      /api/doctores/{id}
  POST     /api/doctores/{body}
  PUT      /api/doctores/{id}
  DELETE   /api/doctores/{id}
```


#### *Pacientes*
```http
  GET      /api/pacientes
  GET      /api/pacientes/{id}
  POST     /api/pacientes/{body}
  PUT      /api/pacientes/{id}
  DELETE   /api/pacientes/{id}
```

#### *Cita*
```http
  GET      /api/citas   
  GET      /api/citas/{data}
  POST     /api/citas/{id}
  PUT      /api/citas/{id}
  DELETE   /api/citas/{id}
```



### Ejemplo para el uso de parametros
#### Get item {id} 

```http
  GET /api/consultorio/${id}
```

| Parámetro | Tipo     | Descripción                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `int` | **Required**. Id del recurso |

-----

### PRUEBAS - API

# Citas

<hr>

# Paciente

![Gif pacientes](https://media.giphy.com/media/HY3zbRaDzNJlpw0FRK/giphy.gif)

![Xampp gif pacientes](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExN2EzdmhiMTJzbTNwZWpxOWFkNG1vNWtpZzlqb2JwY29oczA3cHQ0OCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/kuPxZ4aNhbiRbwO4d4/giphy.gif)

<hr>

# Doctores

![Gif doctores](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExaWN3MTU2YnQ1Mm05d3JleWx1djViMmdscHJ2M2lscXUwNGdoZmU3eCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/uuzv5pQZXRwcUn2oYM/giphy.gif)

![Xampp gif doctor](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExc2x5NmxyaTc0ZDZvNm5hbWhuYmdtNnU3OTY1Z2drNnBld3Z3MW1mcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/oAJE0alCwJXciu4pCX/giphy.gif)





