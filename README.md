# Mapa interactiu i formulari de l'Horta de Lleida (PWA)

Aquest repositori conté una Progressive Web App (PWA) dissenyada i optimitzada per a dispositius mòbils (Android/iOS) i escriptori per a la consulta de mapes i l'enviament de formularis sobre l'Horta de Lleida.

## 🚀 Característiques
- **PWA Instal·lable:** Funciona com una aplicació nativa a Android.
- **Suport Offline:** Gràcies al Service Worker (`sw.js`), es desa en memòria cau per a un accés ràpid i funcionament sense connexió.
- **Geolocalització:** Botó d'accés directe per veure la teva posició en temps real sobre el mapa de l'Horta.
- **Formulari Adapta-Mòbil:** Interfície modal pensada per a pantalles tàctils (Mobile-First).

## 🛠️ Com publicar a GitHub Pages

1. Crea un nou repositori a [GitHub](https://github.com) anomenat `horta-lleida-mapa`.
2. Pujar tots els fitxers d'aquesta carpeta (`index.html`, `sw.js`, `manifest.json`, `icon.svg`).
3. Dins del repositori a GitHub:
   - Ves a **Settings** > **Pages**.
   - A **Source**, selecciona `Deploy from a branch`.
   - Trieu la branca `main` (o `master`) i la carpeta `/ (root)`.
   - Fes clic a **Save**.
4. En un o dos minuts, tindràs el teu enllaç actiu (p. ex., `https://el-teu-usuari.github.io/horta-lleida-mapa/`).
