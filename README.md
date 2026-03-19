# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

```
JobSphere
├─ components.json
├─ eslint.config.js
├─ index.html
├─ jsconfig.json
├─ netlify.toml
├─ package-lock.json
├─ package.json
├─ postcss.config.js
├─ public
│  ├─ banner.png
│  ├─ companies
│  │  ├─ amazon.svg
│  │  ├─ atlassian.svg
│  │  ├─ google.webp
│  │  ├─ ibm.svg
│  │  ├─ meta.svg
│  │  ├─ microsoft.webp
│  │  ├─ netflix.png
│  │  └─ uber.svg
│  ├─ hired.png
│  ├─ logo.png
│  └─ _redirects
├─ README.md
├─ src
│  ├─ api
│  │  ├─ apiApplication.js
│  │  ├─ apiCompanies.js
│  │  └─ apiJobs.js
│  ├─ App.css
│  ├─ App.jsx
│  ├─ components
│  │  ├─ add-company-drawer.jsx
│  │  ├─ application-card.jsx
│  │  ├─ apply-job.jsx
│  │  ├─ created-applications.jsx
│  │  ├─ created-jobs.jsx
│  │  ├─ Header.jsx
│  │  ├─ JobCard.jsx
│  │  ├─ ProtectedRoute.jsx
│  │  ├─ ThemeProvider.jsx
│  │  └─ ui
│  │     ├─ accordion.jsx
│  │     ├─ button.jsx
│  │     ├─ card.jsx
│  │     ├─ carousel.jsx
│  │     ├─ drawer.jsx
│  │     ├─ input.jsx
│  │     ├─ label.jsx
│  │     ├─ radio-group.jsx
│  │     ├─ select.jsx
│  │     └─ textarea.jsx
│  ├─ data
│  │  ├─ companies.json
│  │  └─ faq.json
│  ├─ hooks
│  │  └─ useFetch.js
│  ├─ index.css
│  ├─ layouts
│  │  └─ AppLayout.jsx
│  ├─ lib
│  │  └─ utils.js
│  ├─ main.jsx
│  ├─ pages
│  │  ├─ JobListing.jsx
│  │  ├─ JobPage.jsx
│  │  ├─ LandingPage.jsx
│  │  ├─ MyJobs.jsx
│  │  ├─ Onboarding.jsx
│  │  ├─ PostJob.jsx
│  │  └─ SavedJobs.jsx
│  └─ utils
│     └─ supabase.js
├─ tailwind.config.js
└─ vite.config.js

```