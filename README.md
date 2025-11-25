   # ConstruyeYa - Fullstack (React + Express + Supabase/Postgres)

Este repositorio contiene dos carpetas:

- backend/ - API con Express que gestiona autenticación y proyectos (usa Postgres/Supabase como BD)
- frontend/ - SPA con React Router y Tailwind para la UI

Siguientes pasos:
1. Crear tablas en Supabase con `backend/db_init.sql` o ejecutar en SQL editor.
2. Configurar variables de entorno en backend (.env): DATABASE_URL y JWT_SECRET
3. Ejecutar backend: npm install && npm run dev
4. Ejecutar frontend: cd frontend && npm install && npm run dev

Autor: Ivan Leyva - Universidad de la Costa (CUC)
