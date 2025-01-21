# Challenge Hub

## Descripción

Challenge Hub es una API que permite gestionar tópicos mediante operaciones CRUD (Crear, Leer, Actualizar y Eliminar). La API sigue las mejores prácticas del modelo REST, incluye validaciones según las reglas de negocio y un sistema de autenticación para restringir el acceso a la información.

---

## Tecnologías Utilizadas

- **IDE:** IntelliJ IDEA
- **Lenguaje:** Java 17
- **Base de Datos:** MySQL Workbench 8.0 CE
- **Framework:** Spring Boot
- **Testing:** Omnia
- **Generador de contraseñas en hash:** [bcrypt-generator.com](https://bcrypt-generator.com/)

---

## Funcionalidades

Nuestra API ofrece las siguientes funcionalidades principales:

1. **Crear un nuevo tópico:** Permite a los usuarios crear un nuevo registro en la base de datos.
2. **Mostrar todos los tópicos:** Recupera y lista todos los tópicos creados.
3. **Mostrar un tópico específico:** Permite acceder a los detalles de un único tópico.
4. **Actualizar un tópico:** Facilita la modificación de los datos de un tópico existente.
5. **Eliminar un tópico:** Permite eliminar un tópico de la base de datos.

---

## Características

- **API REST:** Las rutas están implementadas siguiendo las mejores prácticas de arquitectura REST.
- **Validaciones:** Reglas de negocio implementadas para garantizar la consistencia y calidad de los datos.
- **Base de Datos:** Los datos se persisten en una base de datos MySQL para garantizar la integridad y recuperación.
- **Autenticación:** Servicio de autenticación y autorización que restringe el acceso a usuarios autenticados.

---

## Cómo Empezar

### Prerrequisitos

Asegúrate de tener instalados los siguientes componentes:

- Java 17
- MySQL Workbench 8.0 CE
- IntelliJ IDEA o un IDE de tu elección
- Maven configurado en tu máquina

### Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/Cheryl-MPP/forohub.git
