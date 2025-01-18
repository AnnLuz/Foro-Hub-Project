# Foro Hub - REST API

**Foro Hub** es una REST API diseñada para simular las principales funcionalidades de un foro, como el inicio de sesión de usuarios, la creación, actualización y eliminación lógica de tópicos en una base de datos. Este proyecto fue desarrollado como parte del programa de formación **Alura Latam ONE (Oracle Next Education)**, promoviendo prácticas modernas y seguras en el desarrollo de software.



## Descripción General

**Foro Hub** utiliza el **Spring Framework** para gestionar la creación de endpoints seguros y emplea **JWT (JSON Web Tokens)** para la autenticación de usuarios. La API permite:

- **Inicio de sesión seguro:** Los usuarios obtienen un token JWT para acceder a los recursos protegidos.
- **Gestión de tópicos:** Consultar, crear, actualizar y eliminar tópicos.
- **Persistencia de datos:** Cada tópico se almacena en una base de datos **MySQL** y registra la información del autor en acciones clave como creación y actualización.
- **Eliminación lógica:** Los tópicos no se eliminan físicamente de la base de datos, preservando así la integridad y trazabilidad de los datos.



## Requisitos Previos

Antes de comenzar, asegúrese de contar con los siguientes recursos instalados:

- **Java** (versión recomendada: 17 o superior).
- **Spring Framework** configurado en su entorno.
- **MySQL** para la gestión de bases de datos.
- **Postman** o cualquier cliente para pruebas de API.
- **Git** y una cuenta en **GitHub** para control de versiones.

## Buenas Prácticas Promovidas

- **Autenticación Segura:** Uso de JWT para proteger los endpoints y garantizar la privacidad de los usuarios.  
- **Integridad de Datos:** Implementación de eliminación lógica para preservar el historial de acciones.  
- **Modularidad:** Arquitectura basada en principios de separación de responsabilidades y reutilización de código.  
- **Documentación:** Código limpio y bien documentado para facilitar el mantenimiento y la escalabilidad.  



## Tecnologías y Herramientas Utilizadas

- **Lenguaje de programación:** Java  
- **Framework backend:** Spring Boot  
- **Base de datos:** MySQL  
- **Control de versiones:** Git y GitHub  
- **Cliente API:** Postman  
- **Autenticación:** JSON Web Tokens (JWT)  
- **IDE recomendado:** IntelliJ IDEA  



## Contacto

Si tienes preguntas, comentarios o deseas contribuir al proyecto, no dudes en contactarme a través de mi perfil en **GitHub** o mediante los canales de comunicación proporcionados en el repositorio.
