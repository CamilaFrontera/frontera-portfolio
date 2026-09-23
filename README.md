# Portfolio — Camila Frontera

Sitio personal construido con [Astro](https://astro.build).

## Estructura del proyecto

```text
/
├── public/
│   └── mi-foto.jpg
├── src
│   ├── components
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   ├── Education.astro
│   │   ├── Experience.astro
│   │   ├── Header.astro
│   │   ├── Skills.astro
│   │   └── Welcome.astro
│   ├── layouts
│   │   └── Layout.astro
│   └── pages
│       └── index.astro
└── package.json
```

## Comandos

Todos los comandos se ejecutan desde la raíz del proyecto:

| Comando                | Acción                                           |
| :---------------------- | :----------------------------------------------- |
| `pnpm install`           | Instala las dependencias                          |
| `pnpm dev`               | Levanta el servidor local en `localhost:4321`     |
| `pnpm build`             | Genera el sitio de producción en `./dist/`        |
| `pnpm preview`           | Previsualiza el build antes de deployar           |
| `pnpm astro ...`         | Ejecuta comandos de la CLI de Astro               |
