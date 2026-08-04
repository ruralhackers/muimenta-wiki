# Muimenta Viva Wiki

Wiki operativa de **Muimenta Viva** (Carballeda de Avia, Ourense): onboarding de persoas residentes e guía do proxecto.

- **En vivo:** [https://muimenta-wiki.netlify.app](https://muimenta-wiki.netlify.app)
- **Repo:** [github.com/ruralhackers/muimenta-wiki](https://github.com/ruralhackers/muimenta-wiki)
- **Dominio previsto:** [wiki.muimentaviva.gal](https://wiki.muimentaviva.gal)
- **Web pública de candidaturas:** [muimentaviva.gal](https://muimentaviva.gal)
- **Idioma (v1):** galego

## Desenvolvemento

```bash
npm install
npm run dev
```

Abre `http://localhost:4321`.

## Build

```bash
npm run build
npm run preview
```

A saída estática queda en `dist/`. Despregue: Netlify (`netlify.toml`).

## Estrutura

- `src/layouts/WikiLayout.astro` — sidebar + prose
- `src/pages/` — páxinas da wiki (casa, vida diaria, residencias, comunidade, equipo…)
- Contido sintetizado a partir das reunións de coordinación e informes do proxecto (sen datos sensibles).

## Referencias de UX

- [wiki.anceu.com](https://wiki.anceu.com/) (sidebar / onboarding)
- [wiki.espacioarroelo.es](https://wiki.espacioarroelo.es/) (seccións de proxecto)
