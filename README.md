# SkillUp Campus

Plataforma de cursos online desarrollada como proyecto de Simulación Laboral. Este repositorio centraliza el trabajo de todos los roles del equipo (backend, frontend, diseño, data, marketing, QA y PM).

## Integrantes

| Nombre | Rol |
|---|---|
| Belén Gebel | Project Manager |
| Brisa Naiara Giavedoni | Desarrolladora Backend (Node.js) |
| Gustavo Jimenez | Desarrollador Backend (Node.js) |
| Erika Helfenstern | Desarrolladora Frontend (React) |
| Juana Marianela Romero | Desarrolladora Frontend (React) |
| Jorgelina Baez | Diseñadora UX/UI |
| Maria Anabella Planes | Data Analyst |
| Sofia Sosa Velazquez | Data Analyst |
| Tobías Fabricio Escobar | Tester QA Manual |

## Decisiones técnicas

- **Backend:** Node.js + Express
- **Base de datos:** *A confirmar con el equipo técnico (PostgreSQL o MongoDB)*
- **Frontend:** React + Vite, Tailwind CSS
- **Control de versiones:** Git + GitHub, workflow de ramas por feature (`feature/nombre-de-la-feature`)
- **Gestión ágil:** Trello

## Estructura del repositorio

```
skillup-workspace/
├── backend/                  # API REST (Node.js + Express)
│   ├── src/                  # Controladores, modelos, rutas
│   ├── .env.example
│   └── package.json
├── frontend/                 # Aplicación Web (React)
├── docs/                     # Documentación general (pm, qa, api)
├── product_y_growth/         # Marketing, data, diseño
└── README.md
```

## Cómo levantar el backend localmente

```bash
cd backend
npm install
cp .env.example .env   # completar variables de entorno
npm run dev
```

El servidor quedará disponible en `http://localhost:3000` (o el puerto configurado en `.env`).

## Estado del proyecto

🚧 En desarrollo — Semana 1: definición de stack, estructura inicial y backlog técnico.