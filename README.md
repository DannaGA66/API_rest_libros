API REST de Libros en Go
Un proyecto de API REST para gestionar libros (CRUD completo: Crear, Leer, Actualizar, Eliminar), desarrollado en Go (Golang) con una arquitectura en capas bien definida: store (datos) → service (negocio) → handler/controller (HTTP).

Descripción:
API_rest_libros es una API REST que permite gestionar un catálogo de libros con los campos ID, Title y Author. Está construido siguiendo las buenas prácticas de Go: separación de responsabilidades, inyección de dependencias y uso de interfaces para facilitar el testing y el cambio de almacenamiento.

Requisitos:
* Go 1.21+ instalado
* Terminal o editor (VS Code, GoLand, etc.)
Verifica tu versión:
go version
Cómo ejecutar:
go mod tidy
