# Radar Madrid Río

App Android para seguir pisos en venta hasta 250.000 € y desde 50 m² cerca de Madrid Río (prioridad Carabanchel).

- **Descargar la app:** [RadarMadridRio.apk](https://github.com/davob93-art/radar-madrid-rio/releases/latest/download/RadarMadridRio.apk). Ábrelo desde el móvil y permite "instalar apps de origen desconocido".
- **Datos:** `data/pisos.json` y `data/meta.json`, actualizados cada mañana a las 8:45 por la revisión automática de Claude. La app los descarga al abrirse; no hace falta reinstalar para ver pisos nuevos.
- **Favoritos y descartados** se guardan solo en el móvil.
- **Código:** `android/` (app nativa con la interfaz en `android/app/src/main/assets/www/index.html`). Cada cambio en `android/` compila un .apk nuevo con GitHub Actions y lo publica en *Releases*.
