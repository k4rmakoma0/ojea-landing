# Ojea: sitio web

Sitio de Ojea, el lector de RSS para Mac, iPhone, iPad, Apple Vision Pro y Apple Watch, en `ojea.alananaya.dev`.

HTML y CSS estáticos, sin paso de compilación, dependencias, scripts ni analíticas. Cualquier hosting estático sirve con la raíz de este repo.

| Página | Ruta |
|---|---|
| Inicio | `/` |
| Soporte | `/soporte/` |
| Aviso de privacidad | `/privacidad/` |

La dirección del aviso de privacidad es la que va en App Store Connect: `https://ojea.alananaya.dev/privacidad/`. La de soporte, `https://ojea.alananaya.dev/soporte/`.

Correos de contacto: `support@alananaya.dev` para soporte y `privacy@alananaya.dev` para privacidad.

Los colores salen del icono y de `Shared/Assets.xcassets` de la app. El icono está en `assets/img/icon.svg`; los PNG se generan a partir de él.

Para verlo en local:

```bash
python3 -m http.server 8000
```
