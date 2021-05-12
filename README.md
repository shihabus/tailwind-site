Setup

1. Setup Vite

```bash
npm init @vitejs/app <app_name> -- --template vanilla
```

This will create a vanilla app with Vite set up

2. Add Tailwind as PostCSS plugin

```bash
npm install -D tailwindcss@latest postcss@latest autoprefixer@latest

npx tailwindcss init -p
```

3. Import Tailwindcss base

```bash
import "tailwindcss/tailwind.css"
```
