# macagraf.github.io — Portfolio de Maca

**Sitio publicado: https://macagraf.github.io**

Ilustración de línea fina: geometría sagrada y naturalismo para mural, editorial,
textil y pirograbado.

## Estructura

```
index.html            ← todo el sitio (HTML + CSS + JS, sin build)
assets/laminas/       ← fotos de obra y bocetos SVG de reemplazo
assets/video/         ← videos de proceso (mp4, sin audio)
```

## Poner tus obras

Sube cada foto a `assets/laminas/` con el nombre exacto y la foto reemplaza
al boceto automáticamente, sin tocar el código:

| Archivo | Proporción | Medida |
|---|---|---|
| `01-fruto-de-la-vida.jpg` | cuadrada 1:1 | 1400 × 1400 |
| `02-vesica-piscis.jpg` | cuadrada 1:1 | 1400 × 1400 |
| `03-pirograbado.jpg` | cuadrada 1:1 | 1400 × 1400 |
| `04-mural-mandarava.jpg` | horizontal 4:3 | 1195 × 896 |
| `04-mural-detalle.jpg` | vertical 3:4 | 1080 × 1440 |
| `05-mural-mandala.jpg` | horizontal 4:3 | 1195 × 896 |
| `prenda-franela.jpg` | vertical 400:520 | 1200 × 1560 |
| `prenda-sudadera.jpg` | vertical 400:520 | 1200 × 1560 |
| `prenda-camisa.jpg` | vertical 400:520 | 1200 × 1560 |

El video del mural Mandala va en `assets/video/mural-mandala.mp4` (720 × 1280,
29 s, 3,9 MB, sin audio). Se reproduce en loop cuando se elige la foto 02 y se
pausa al salir de pantalla. Su miniatura es `assets/laminas/05-mural-mandala-video.jpg`.

El marco de cada obra toma la proporción real de la foto (no la recorta), así que
conviene subirla ya encuadrada y con la proporción que figura en la tabla.

Nombres: minúsculas, con guiones, sin acentos y con extensión `.jpg`.
Peso: menos de 400 KB por imagen y 1600 px del lado más largo.

## Cambiar textos o datos

Abre `index.html` (botón del lápiz en GitHub) y usa Ctrl+F:

- `maca.grafvar@gmail.com` → correo de contacto (aparece dos veces: texto y `mailto:`)
- `https://www.instagram.com/maca.graf` → perfil de Instagram
- `https://www.tiktok.com/@macagraf` → perfil de TikTok
- `https://wa.me/584141415997` → WhatsApp (formato internacional sin `+` ni espacios)
- `Maca` → tu nombre o el de tu estudio

Cada cambio de commit tarda cerca de un minuto en reflejarse en el sitio.

## Tipografía

Space Grotesk (SIL OFL), servida por Google Fonts. Sin internet, el navegador
usa una del sistema y el resto del diseño no cambia.

## Historial

La versión anterior de este repositorio publicaba el manual de marca de MaCa.
Ese documento queda guardado en el historial de git.
