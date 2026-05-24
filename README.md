# Laboratorio en Inteligencia Artificial UNAL

Sitio web estático del Laboratorio en Inteligencia Artificial de la Universidad Nacional de Colombia, sede Manizales.

## Desarrollo local

```bash
npm install
npm run dev
```

Astro mostrará una URL local, normalmente `http://localhost:4321/LaboratorioIA_UNAL/`.

## Validación de producción

```bash
npm run build
npm run preview
```

El build se genera en `dist/`.

## Despliegue en GitHub Pages

1. Subir los cambios a `main` en `https://github.com/amalvarezme/LaboratorioIA_UNAL`.
2. Abrir el repositorio en GitHub.
3. Ir a `Settings > Pages`.
4. En `Build and deployment`, seleccionar `GitHub Actions`.
5. Esperar la ejecución del workflow `Deploy Astro site to Pages`.

El sitio quedará publicado en:

```text
https://amalvarezme.github.io/LaboratorioIA_UNAL/
```
