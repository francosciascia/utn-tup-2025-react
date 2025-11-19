🍽️ Recetas Franco – Aplicación de Recetas de Cocina

Aplicación web creada para el Trabajo Práctico de Programación IV (UTN).
Permite explorar un catálogo de recetas, ver detalles completos, buscar, filtrar y navegar con un diseño moderno usando Material UI.

Desarrollado por Franco Sciascia 👨‍🍳.

🚀 Funcionalidades Principales

Listado de recetas responsivo

Vista de detalle con ingredientes y pasos

Context API para estados globales

Navegación completa con React Router DOM

Buscador por título

Filtros por categoría / dificultad

Modo oscuro / claro

Botón "Compartir receta"

Página de Inicio

Footer informativo

Totalmente responsive

🧱 Estructura del Proyecto
src/
├── App.jsx
├── main.jsx
├── components/
│   ├── layout/
│   │   ├── Navbar.jsx
│   │   └── Footer.jsx
│   └── recetas/
│       ├── RecetaCard.jsx
│       ├── RecetasList.jsx
│       ├── RecetaDetalle.jsx
│       └── IngredientesList.jsx
├── contexts/
│   ├── RecetasContext.jsx
│   └── ThemeContext.jsx
├── pages/
│   ├── InicioPage.jsx
│   ├── RecetasListPage.jsx
│   └── RecetaDetallePage.jsx
├── data/recetas.json
└── styles.css

🛠️ Tecnologías Utilizadas

React 19

React Router DOM 7

Material UI 7

Context API

Vite

JavaScript moderno

▶️ Cómo Ejecutarlo
1️⃣ Instalar dependencias
npm install

2️⃣ Ejecutar entorno de desarrollo
npm run dev


Abrir:
http://localhost:5173

3️⃣ Build de producción
npm run build

📸 Capturas de Pantalla
🏠 Página de Inicio
<img src="./screenshots/inicio.png" width="600" />
🌙 Modo Oscuro
<img src="./screenshots/oscuro.png" width="600" />
🍽️ Listado de Recetas
<img src="./screenshots/recetotas.png" width="600" />
📄 Detalle de Receta
<img src="./screenshots/receta.png" width="600" />
📱 Vista Responsive
<img src="./screenshots/responsive.png" width="600" />
📦 Estado del Proyecto

✔ Completo
✔ Cumple requisitos
✔ Incluye extras
✔ Listo para ser entregado

👨‍💻 Autor

Franco Sciascia
GitHub: https://github.com/francosciascia

📄 Licencia

Proyecto de uso académico.
