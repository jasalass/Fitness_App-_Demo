# 🏋️ Fitness App - Demo

**FitnessApp** es una aplicación web construida con **React + Supabase** que permite a los usuarios planificar, ejecutar y llevar un historial de sus entrenamientos semanales.
---

## 🚀 Demo en línea

👉 [Demo en Netlify](https://fitnessappdemo.netlify.app/login)

---

## 🎯 Funcionalidades principales

- Registro e inicio de sesión de usuarios
- Planificación de rutinas semanales por día
- Ejecución de rutinas con temporizador por ejercicio
- Pausar, reanudar y detener rutinas
- Registro automático de sesiones realizadas
- Historial de entrenamientos con detalle por ejercicio
- Interfaz limpia, moderna y responsiva

---

## 📂 Repositorios del proyecto

| Componente | Repositorio |
|------------|-------------|
| 🌐 Frontend | [jasalass/Fitness_Front](https://github.com/jasalass/Fitness_Front) |
| 🗄️ Backend  | [jasalass/Fitness_backend](https://github.com/jasalass/Fitness_backend) |

---

## 👤 Usuario de prueba

Puedes ingresar con esta cuenta para probar la app:

```
Correo:     demo@usuario.com
Contraseña: 123456
```

## ⚙️ Instalación local

### 1. Clona el frontend

```bash
git clone https://github.com/jasalass/Fitness_Front.git
cd fitness-app
npm install
```

### 2. Configura `.env` en el frontend

Crea un archivo `.env` y agrega tus claves de Supabase:

```env
REACT_APP_SUPABASE_URL=https://<TU_SUPABASE>.supabase.co
REACT_APP_SUPABASE_ANON_KEY=ey...
```

### 3. Ejecuta la app localmente

```bash
npm run dev
```

---

## 🛠 Configuración del backend (Supabase)

1. Crea un nuevo proyecto en [https://supabase.com](https://supabase.com)
2. Ingresa al SQL Editor
3. Copia y ejecuta el contenido de este archivo:
   👉 [esquema.sql en Fitness_backend](https://github.com/jasalass/Fitness_backend/blob/main/database/esquema.sql)

Esto creará las tablas, políticas RLS y estructura necesaria para que la app funcione correctamente.

---

## 🧠 Tecnologías utilizadas

- ⚛️ React
- 🟩 Supabase (PostgreSQL + Auth)
- 🎨 CSS vanilla + transiciones suaves
- 📡 REST API vía Supabase
- ☁️ Deploy en Netlify

---

## 📸 Capturas

![4](https://github.com/user-attachments/assets/08e0c7af-287e-45c7-afe2-521e95944646)
![3](https://github.com/user-attachments/assets/8a701bb5-98d0-4af1-bece-38bcfbc84b0a)
![2](https://github.com/user-attachments/assets/92b207a6-2d2e-49fd-aa5b-ce6553309fbb)
![1](https://github.com/user-attachments/assets/d6552e56-1d95-4197-91e2-daf1d46fb763)

---

## 💡 Créditos

Desarrollado por [@jasalass](https://github.com/jasalass) como proyecto demostrativo de aprendizaje con React + Supabase.

---
