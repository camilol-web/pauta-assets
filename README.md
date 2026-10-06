# pauta-assets

Fotos de propiedades para campañas de Meta Ads de **Camilo Lopera Real Estate**.

Este repositorio es **público a propósito**: Meta no recibe imágenes por API, va a
buscarlas a una URL pública. Las fotos que viven acá son las mismas que salen publicadas
en anuncios pagados, así que no exponen nada que no fuera a ser público de todos modos.

## ⚠️ Regla

Acá van **imágenes que de todos modos van a salir publicadas en un anuncio**: fotos de
propiedades en venta o alquiler, y creativos de campaña (carpeta `creativos-campanas/`).

El criterio es ese: si la imagen va a verse en un anuncio pagado, no expone nada nuevo.

**Nunca:** documentos, contratos, datos de clientes, cédulas, precios internos,
comisiones, ni nada del vault. Si tenés dudas sobre si algo va acá, no va.

## Cómo se usan

Las URLs directas tienen esta forma:

```
https://raw.githubusercontent.com/camilol-web/pauta-assets/main/<carpeta>/<archivo>.jpg
```

## Formatos

Meta rechaza el 4:3 que sale de cámara y de dron. Cada foto se guarda recortada:

| Sufijo | Ratio | Tamaño | Para |
|---|---|---|---|
| `-1x1` | 1:1 | 1080×1080 | Feed y carrusel |
| `-4x5` | 4:5 | 1080×1350 | Feed vertical (ocupa más pantalla) |

Falta `-9x16` (1080×1920) para stories y reels: **no se puede recortar desde una foto
horizontal sin destruirla**. Esas hay que tomarlas verticales desde el inicio.

## Propiedades

- `clinica-escazu/` — Clínica odontológica equipada, Escazú (Plaza La Paco). Venta $330,000.
- `alquiler-tres-apartamentos/` — Tres apartamentos en alquiler, oct-2026:
  Condominio Aviva (Santa Ana, ₡650.000), Bosques del Café (Guachipelín, ₡700.000)
  y Río Oro (Santa Ana, ₡700.000).
