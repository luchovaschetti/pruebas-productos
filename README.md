# pruebas-productos

Prototipos de productos propios. Se publica con GitHub Pages desde la carpeta `/docs`.

| Prueba | Carpeta | Qué hace |
|---|---|---|
| Tilde (nombre provisorio) | `docs/tilde/` | Lee facturas argentinas (QR de ARCA + texto del PDF), valida CUIT e importes y exporta a Excel. Todo corre en el navegador, sin backend. |
| Tilde Ganancias | `docs/ganancias/` | Clasifica las facturas del año por rubro del F.572, controla que estén a tu nombre y deja los datos listos para copiar en SiRADIG. |
| Hola | `docs/hola/` | Página de prueba estática, para comparar GitHub Pages con Cloudflare Pages. |

Para agregar una prueba nueva: crear `docs/<nombre>/index.html` y sumarla a `docs/index.html`.
