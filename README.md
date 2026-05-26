# 🎓 Michael Zabala – Portafolio Académico

Portafolio personal desarrollado con [Astro](https://astro.build), desplegado en GitHub Pages. Documenta evidencias del curso de Bases de Datos: modelado E-R, normalización, SQL y proyecto final.

## 🚀 Stack

- **Framework:** Astro
- **Estilos:** Tailwind CSS
- **Diagramas:** Mermaid.js + Draw.io
- **Deploy:** GitHub Actions → GitHub Pages

## 📁 Estructura
src/
├── components/       # Header, Footer
├── layouts/          # BaseLayout
├── pages/
│   ├── index.astro
│   └── evidencias/
│       ├── index.astro
│       ├── modelado.astro     # Diagramas E-R y reducción a tablas
│       ├── normalizacion.astro
│       ├── sql.astro
│       └── proyecto.astro
public/
└── diagramas/        # Imágenes Draw.io

## 📚 Evidencias

| Sección | Contenido |
|---|---|
| **Modelado E-R** | Diagramas Draw.io y Mermaid, entidades, atributos y reducción a tablas |
| **Normalización** | Formas normales 1FN, 2FN, 3FN |
| **SQL** | Consultas, procedimientos y vistas |
| **Proyecto** | Diseño e implementación de base de datos completa |

## 🛠️ Desarrollo local

```bash
npm install
npm run dev
```

## 📦 Deploy

El despliegue es automático vía GitHub Actions al hacer push a `main`.
