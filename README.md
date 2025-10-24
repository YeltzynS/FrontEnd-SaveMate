# 🛡️ SafeMate Frontend - Configuración Inicial

Este documento describe la configuración inicial del **frontend de SafeMate**, incluyendo el repositorio, la estructura del proyecto y las instrucciones para ejecutar el entorno local.

---

## 🧩 1. Repositorio y Trunk-Based Development

El proyecto **SafeMate Frontend** forma parte del repositorio [`SafeMate-IETI-2025`](https://github.com/tu-usuario/SafeMate-IETI-2025).

> **SafeMate** es una aplicación diseñada para ayudar a los usuarios a gestionar y optimizar sus hábitos de ahorro mediante inteligencia artificial.

### 🔹 Modelo de desarrollo: Trunk-Based Development

El proyecto sigue la metodología **Trunk-Based Development**, donde:
- Todos los desarrolladores trabajamos sobre una única rama principal: `main`.
- Las nuevas funcionalidades se desarrollan en **ramas cortas (feature branches)**.
- Cada cambio se integra rápidamente al trunk mediante **Pull Requests (PRs)** revisadas y aprobadas.
- Esto promueve la **integración continua**, la detección temprana de errores y la **entrega frecuente de valor**.

---

## 📁 2. Estructura Inicial del Proyecto Frontend

La estructura inicial del proyecto está pensada para mantener una organización clara y modular del código.

```bash
SafeMate-Frontend/
├── node_modules/          # Dependencias instaladas automáticamente
├── public/                # Archivos estáticos y plantilla index.html
├── src/                   # Código fuente del frontend
│   ├── assets/            # Imágenes e íconos
│   ├── components/        # Componentes reutilizables (Navbar, Card, etc.)
│   ├── pages/             # Vistas principales (Home, Dashboard, Login)
│   ├── services/          # Conexiones con el backend (API REST)
│   ├── App.jsx            # Componente raíz
│   ├── main.jsx           # Punto de entrada
│   └── styles/            # Estilos globales o configuración Tailwind
├── .gitignore
├── package.json           # Configuración del proyecto y dependencias
├── vite.config.js         # Configuración del entorno de desarrollo (si usas Vite)
└── README.md


💻 3. Instalación y Ejecución Local

Sigue los pasos a continuación para clonar, instalar y ejecutar el proyecto en tu entorno local.

🔹 Requisitos previos

Tener instalado Node.js (versión 18 o superior).

Tener npm o yarn como gestor de paquetes.

# 1. Clonar el repositorio
git clone https://github.com/tu-usuario/SafeMate-IETI-2025.git

# 2. Entrar al directorio del frontend
cd SafeMate-Frontend

# 3. Instalar las dependencias
npm install

# 4. Iniciar el servidor de desarrollo
npm run dev


