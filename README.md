# Guía de DemonCraft

La guía para jugadores de **DemonCraft**: cómo entrar, los primeros minutos, el camino del cazador y el del demonio,
las respiraciones y cómo entrenar el aliento, la economía, las casas de alquiler, el Mercado, los clanes, los duelos,
los rangos de apoyo y todos los comandos.

**Léela aquí: https://slava1222.github.io/demoncraft-guia/**

*La noche es de los demonios. El amanecer, tuyo.*

- Servidor: `demoncraft.world`
- Launcher: https://github.com/slava1222/demoncraft-launcher/releases/latest
- Discord: https://discord.gg/mdwAvAMBvr

---

## Para quien la mantiene

La web se genera con [MkDocs](https://www.mkdocs.org/) y el tema
[Material for MkDocs](https://squidfunk.github.io/mkdocs-material/). El código está en `main` y la web publicada, en la
rama `gh-pages`.

### Verla en tu ordenador antes de subirla

```bash
pip install "mkdocs==1.6.1" "mkdocs-material==9.7.7" "mkdocs-glightbox==0.5.2"
mkdocs serve
```

Y abre http://127.0.0.1:8000/demoncraft-guia/. Los cambios se ven al guardar.

### Publicar un cambio

Sube el cambio a `main` y después publica la web (compila en modo estricto: si hay un enlace roto, no publica):

```bash
git push
mkdocs gh-deploy --force --strict
```

La web se actualiza en uno o dos minutos.

### Dónde está cada cosa

| Ruta | Qué es |
|---|---|
| `mkdocs.yml` | Título, menú (`nav`), colores y extensiones. |
| `docs/` | Las páginas, una por archivo `.md`. |
| `docs/assets/img/capturas/` | Capturas del juego (WebP). |
| `docs/assets/img/mapas/` | El mapa del mundo (normal y a tamaño completo). |
| `docs/assets/img/vip/` | Imágenes de los rangos de apoyo. |
| `docs/assets/css/demoncraft.css` | El estilo propio de la guía. |
| `overrides/home.html` | La portada (cabecera grande con la IP). |
| `includes/glosario.md` | Abreviaturas que muestran su significado al pasar el ratón. |

### Normas de estilo

- Resumida y práctica: lo que el jugador necesita para jugar. La historia se descubre jugando, no se cuenta aquí.
- Siempre la marca **DemonCraft**.
- Precios, tiempos y comandos tal como están en el juego. Si cambian en el servidor, se cambian aquí.
- Imágenes en WebP, como mucho 1.600 px de ancho, con texto alternativo.
