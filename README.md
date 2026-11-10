# 🤖 Asistente Inteligente de IA "BIBLIO ASISTENTE"

Este proyecto consiste en el desarrollo de un asistente inteligente de consulta de biblioteca basado en Inteligencia Artificial (IA), diseñado para interpretar consultas de usuarios, procesar información y proporcionar respuestas de manera automatizada.

El agente se encuentra conectado a un archivo Excel que funciona como base de datos y simula la interacción de conexión a un Sistema General de Biblioteca conectado mediante una API, su función es consultar la información disponible en el archivo Excel y brindar respuestas claras al usuario, y su único privilegio otorgado es el realizar consultas.

El sistema busca facilitar el acceso a la información mediante el procesamiento de lenguaje natural, utilizando una arquitectura modular que permite organizar las funcionalidades y separar las responsabilidades de cada componente.

## 🎯 Objetivos

- Desarrollar un asistente virtual capaz de interpretar consultas.
- Procesar solicitudes mediante inteligencia artificial.
- Organizar y gestionar la información de manera estructurada.
- Proporcionar respuestas claras y contextualizadas.

## 📂 Documentación y navegación del código

A continuación se detallan los principales archivos y directorios del proyecto:

### Ir a Agente de IA
- [BiblioAsistente](https://opal.google/app/1AMFg4tZ7J08bxOLoVq7LbtXL4QBACK4g)

### Presentación
- [Ver presentación en power point](./Clases.pptx)

### Diagramas
- [Diagramas](./diagramas/)

### Archivo Excel que funciona como base de datos del Agente
- [Excel](./biblioteca.xlsx)

## 🔄 Flujo de funcionamiento

1. El Agente solicita un numero de DNI para iniciar consulta.
2. El sistema recibe entrada de datos.
3. Se verifica que se encuentre el usuario registrado.
3.1.a. Si se encuentra registrado pasa al paso 4.
3.1.b. En caso de no encontrarse, se informa que la persona se acerque a recepción para registrarse.
4. El sistema solicita un nombre de libro para buscar.
5. El sistema recibe ingreso de datos, y realiza la petición de busqueda a la base de datos del Sistema Gral de la Biblioteca.
6. El sistema devuelve el resultado al usuario.

## 👨‍💻 Autor

**Ezequiel Reyes**

Desarrollador web y estudiante de Analista en Sistemas.

[GitHub](https://github.com/EzeReyes)

---

*Proyecto desarrollado con fines educativos y de aplicación práctica de tecnologías de inteligencia artificial.*