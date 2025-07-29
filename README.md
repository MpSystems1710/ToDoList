# 📝 ToDo App

Una aplicación web simple para gestionar tareas (ToDo List), desarrollada con **React** en el frontend y **Node.js + Express** en el backend.

## Características

- Agregar tareas
- Eliminar tareas
- Editar tareas (PUT disponible)
- API RESTful
- Estilo moderno y atractivo con diseño responsivo

## Estructura del proyecto

```
ToDo List/
├── backend/
│   ├──index.js              # Servidor Express
│   ├──tareas.json
├── frontend/
│   ├── public/
│   └── src/
│       ├── Assets/
│       ├── App.jsx           # Componente principal React
│       ├── App.css           # Estilos personalizados
│       ├── index.css
│       └── main.jsx
├── package.json              # Configuración general (frontend)
├── Tareas.json               # Es donde se almacenan las tareas creadas
├── README.md                 # Documentación
```

## Requisitos

- Node.js ≥ 16
- npm o yarn
- Navegador moderno

---

## Instalación y ejecución

### Parte 1: Backend (Node.js + Express)

```
1. Inicializa el proyecto

mkdir Backend
cd Backend
npm init -y
npm install express cors
npm install --save-dev nodemon
```

### Parte 2: Frontend (React.js con Vite o CRA)

```
1. Crear el proyecto con Vite

npm create vite@latest frontend -- --template react
cd frontend
npm install

1. Select a framework:
   │ React

2. Select a variant:
   │ JavaScript

```

## Damos click derecho sobre el backend y abrimos la terminal y ejecutamos este comando

```
npm run dev
```

El servidor se ejecutará en `http://localhost:3001`

## Damos click derecho sobre el frontend y abrimos la terminal y ejecutamos este comando.

```
npm run dev
```

La app se abrirá en `http://localhost:5173` (o el puerto que indique Vite/React)

## API Endpoints

| Método | Ruta              | Descripción                |
| ------ | ----------------- | -------------------------- |
| GET    | `/api/tareas`     | Obtener todas las tareas   |
| POST   | `/api/tareas`     | Crear nueva tarea          |
| PUT    | `/api/tareas/:id` | Editar una tarea existente |
| DELETE | `/api/tareas/:id` | Eliminar una tarea         |

---

## Tecnologías utilizadas

- **Frontend**: React, HTML, CSS
- **Backend**: Node.js, Express

---

## Autor

- **Luis Miguel Preciado Pérez**
- Tecnólogo en Análisis y Desarrollo de Software
- [Portafolio Web](https://curriculumvirtual-miguelpreciado.netlify.app/)
- Respositorio GitHub (https://github.com/MpSystems1710/)

---
