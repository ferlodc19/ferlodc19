# 🏛️ Plataforma de Trámites

Un sistema web de registro y gestión de trámites institucionales. Este proyecto permite a los usuarios llenar un formulario estructurado, cargar documentos adjuntos y generar un folio único de seguimiento, además de contar con un panel de historial para visualizar y descargar reportes.

## ✨ Características Principales

- **Formulario Estructurado:** Captura de datos personales, económicos y de domicilio divididos en secciones claras.
- **Carga de Documentos:** Validación y almacenamiento de archivos requeridos (PDF y TXT).
- **Generación de Folio Único:** Asignación automática de un número de folio (ej. `TR-04154`) al completar el registro.
- **Historial de Trámites:** Vista de tabla minimalista (desktop) y tarjetas (móvil) ordenada por los registros más recientes.
- **Diseño Mobile-First:** Interfaz limpia, responsiva e institucional construida con Tailwind CSS.

## 🛠️ Tecnologías Utilizadas

**Frontend:**
- React 18
- TypeScript
- Tailwind CSS
- Vite
- React Router DOM

**Backend:**
- C# / .NET (ASP.NET Core Web API)
- Entity Framework Core (Code-First)
- PostgreSQL (Base de datos relacional)

## 🗄️ Estructura de la Base de Datos

El sistema utiliza una arquitectura relacional en PostgreSQL para mantener la integridad de los datos, separando la información en las siguientes tablas:
- `Registros` (Tabla principal con Folio y Fecha)
- `DatoPersonal`
- `DatoEconomico`
- `Domicilio`
- `Archivo` (Rutas de almacenamiento de los archivos locales)

## 🚀 Requisitos Previos

Antes de ejecutar el proyecto, asegúrate de tener instalado:
- [Node.js](https://nodejs.org/) (v18 o superior)
- [.NET SDK](https://dotnet.microsoft.com/) (v7 o v8)
- [PostgreSQL](https://www.postgresql.org/)

## ⚙️ Instalación y Configuración

Sigue estos pasos para correr el proyecto en tu entorno local:

### 1. Clonar el repositorio
```bash
git clone [https://github.com/TU_USUARIO/PlataformaTramites.git](https://github.com/TU_USUARIO/PlataformaTramites.git)
cd PlataformaTramites
