Proyecto Gestión de Eventos

Aplicación en ASP.NET para gestionar eventos, con base de datos en MongoDB.

Requisitos

.NET 6.0 o superior

MongoDB

Visual Studio o Visual Studio Code

Estructura
/Controllers
/Models
  Evento.cs
/Views
/wwwroot
appsettings.json
Instalación

Clonar el proyecto.

Configurar la cadena de conexión a MongoDB en appsettings.json, por ejemplo:

"ConnectionStrings": {
  "MongoDb": "mongodb://localhost:27017"
},
"DatabaseName": "EventosDB"

Compilar y ejecutar el proyecto con:

dotnet run
Base de datos

Colecciones principales:

Eventos

Usuarios (si aplica)

Contacto

María Belén González — Colegio Técnico Don Bosco, especialidad Desarrollo.
