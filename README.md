# AgroSmart — Landing MVP

Landing page para validar el interés en **AgroSmart**, una plataforma de monitoreo agrícola inteligente que ayuda a agricultores a gestionar cultivos, riegos y recibir recomendaciones personalizadas desde el celular.

## Objetivo del MVP

Capturar registros de interés (early access) antes del desarrollo del producto completo, midiendo la demanda real con una landing estática, rápida y optimizada para SEO.

## Stack

- [Astro](https://astro.build) — generación de sitio estático
- CSS vanilla (sin frameworks)
- Deploy en Vercel / Netlify

## Estructura

```
src/
├── components/
│   ├── Navbar.astro
│   ├── Hero.astro
│   ├── Benefits.astro
│   ├── Testimonials.astro
│   ├── Signup.astro
│   └── Footer.astro
├── layouts/
│   └── Layout.astro      # Head, SEO, OG tags
├── pages/
│   └── index.astro
└── styles/
    └── global.css
public/
└── favicon.svg           # Ícono de hoja AgroSmart
```

## Comandos

| Comando           | Acción                                        |
| :---------------- | :-------------------------------------------- |
| `npm install`     | Instala dependencias                          |
| `npm run dev`     | Servidor local en `localhost:4321`            |
| `npm run build`   | Build de producción en `./dist/`              |
| `npm run preview` | Preview del build antes de desplegar          |
