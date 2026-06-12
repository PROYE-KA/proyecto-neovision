# Sistema-AutoStock

## AutoStock – Sistema de Gestión de Inventario para Refacciones Automotrices

Plataforma web para el control en tiempo real de entradas, salidas y alertas de reposición de inventario.

## Descripción del Proyecto

### Problema a Resolver

Una empresa dedicada a la venta de piezas automotrices pierde dinero de dos formas: compra de más y acumula stock muerto, o compra de menos y pierde ventas por falta de producto. El inventario se lleva en hojas de cálculo o en sistemas que nadie actualiza en tiempo real, así que nadie sabe realmente cuánto hay en bodega hasta que es tarde.

El resultado son pedidos urgentes, sobrecostos de almacenamiento y clientes que se van con la competencia.

### Objetivo General

Desarrollar una plataforma web que registre entradas y salidas de inventario en tiempo real, genere alertas automáticas de reposición y produzca reportes que le indiquen al negocio qué producto necesita y cuándo reabastecerlo, sin depender de alguien que recuerde actualizar una hoja de cálculo.

## Alcance Preliminar

* Registro de productos con categorías y proveedores.
* Control de entradas y salidas de inventario.
* Panel de alertas cuando el stock baja de la cantidad definida.
* Reportes de productos más vendidos y stock mínimo.
* Gestión de usuarios con roles.
* API REST para integración con sistemas de punto de venta.
* Módulo de exportación a Excel y PDF.

## Tecnologías

* Frontend: React 18 + Vite + Tailwind CSS
* Backend: Node.js + Express + JWT
* Base de datos: PostgreSQL 15
* Hosting: AWS EC2 + S3
* Repositorio: GitHub
* CI/CD: GitHub Actions

## Integrantes

| Nombre          | Rol             |
| --------------- | --------------- |
| Mario Puentes   | Project Manager |
| Edwin Garcia    | Dev OPS        |
| Jonatan Davila  | Frontend Dev    |
| Edwin Garcia    | Backend Dev     |
| Jovanny Esquivel| QA Engineer     |

## Estructura del Repositorio

```text
AutoStock/
├── Documentacion/
├── Codigo/
│   ├── frontend/
│   └── backend/
├── Recursos/
└── README.md
```

## Herramientas a usar
| Necesidad                                    | Herramienta       |
| -------------------------------------------- | ----------------- |
| Gestión de proyectos y seguimiento de tareas | Jira              |
| Comunicación rápida del equipo               | Discord           |
| Reuniones y colaboración                     | Microsoft Teams   |
| Control de versiones                         | Git               |
| Repositorio de código                        | GitHub            |
| Desarrollo Frontend                          | React + Vite      |
| Desarrollo Backend                           | Node.js + Express |
| Base de Datos                                | PHP / MYSQL       |

## Razón de Selección
Jira: permite organizar historias de usuario, tareas y dar seguimiento al avance del proyecto mediante metodologías ágiles.
Discord: facilita la comunicación inmediata entre los integrantes del equipo y la resolución rápida de dudas.
Microsoft Teams: se utiliza para reuniones virtuales, seguimiento de actividades y coordinación general del proyecto.
Git y GitHub: permiten el control de versiones y el trabajo colaborativo sobre el código fuente.
React + Vite: ofrecen un desarrollo rápido y eficiente para la interfaz de usuario.
Node.js + Express: permiten construir una API REST escalable y de alto rendimiento.
MySQL: sistema para la gestión de datos del inventario.

## Flujo de Trabajo

Las actividades y requerimientos se registran en Jira.
El equipo analiza y asigna tareas durante reuniones de seguimiento en Teams.
La comunicación diaria y resolución de dudas se realiza mediante Discord.
Cada desarrollador trabaja en una rama específica del repositorio.
Los cambios son enviados a GitHub mediante commits y push.
Se realizan revisiones del código antes de integrar los cambios a la rama principal.
Una vez aprobados, los cambios se fusionan en la rama principal y continúan las pruebas del sistema.


## Cómo correr el proyecto localmente

1. Clonar el repositorio:

   ```bash
   git clone https://github.com/equipo/autostock
   ```

2. Iniciar el backend:

   ```bash
   cd Codigo/backend
   npm install
   npm run dev
   ```

3. Iniciar el frontend:

   ```bash
   cd Codigo/frontend
   npm install
   npm run dev
   ```

4. Crear el archivo `.env` con las variables requeridas (ver `.env.example`).

2. cd Codigo/backend && npm install && npm run dev
3. cd Codigo/frontend && npm install && npm run dev
4. Crear archivo .env con las variables requeridas (ver .env.example)
