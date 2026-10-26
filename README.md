# RespondeIA en Netlify (con Gemini, gratis)

1. Clave gratis: entra a https://aistudio.google.com > Get API key > Create API key. Cópiala.
2. Sube esta carpeta a un repo de GitHub.
3. En Netlify: Add new site > Import from Git > elige el repo (no cambies nada).
4. Site configuration > Environment variables > Add a variable:
   Key: GEMINI_API_KEY   Value: tu clave
   (Opcional: GEMINI_MODEL, por defecto gemini-flash-latest)
5. Deploys > Trigger deploy. Listo.

Con CLI: npm i -g netlify-cli && netlify deploy --prod
(Arrastrar y soltar la carpeta NO ejecuta funciones.)
Prueba local: netlify dev
