# Muimenta Viva Wiki

Wiki pública/operativa de **Muimenta Viva** (Carballeda de Avia, Ourense): onboarding de residentes temporais e guía do proxecto.

- **Idioma:** galego (`lang="gl"`)
- **Dominio previsto:** [wiki.muimentaviva.gal](https://wiki.muimentaviva.gal)
- **Stack:** Astro 5 (sitio estático)

## Desenvolvemento local

```bash
npm install
npm run dev
```

Abre a URL que indique o terminal (por defecto `http://localhost:4321`).

## Build

```bash
npm run build
npm run preview
```

A saída estática queda en `dist/`.

## Despregue

Sitio estático apto para Netlify, Cloudflare Pages ou similar.

1. Conectar o repositorio ou subir `dist/`.
2. Comando de build: `npm run build`
3. Directorio de publicación: `dist`
4. Apuntar o DNS de `wiki.muimentaviva.gal` ao provedor (CNAME / rexistros segundo o hosting).

O despregue a `wiki.muimentaviva.gal` farase nun paso posterior; este repo xa está preparado para publicar o estático.

## Estrutura

- `src/layouts/WikiLayout.astro` — layout con sidebar (escritorio) e menú móbil
- `src/components/` — Sidebar e listaxe da home
- `src/pages/` — contido en galego (proxecto, casa, vida diaria, residencias, comunidade, equipo, antes de irte)
- `src/styles/global.css` — tokens e tipografía (Fraunces + Source Sans 3)

## Contido

Redactado a partir de acordos operativos das reunións de coordinación e dos informes do proxecto. Non inclúe política local, salarios nin información sensible.
