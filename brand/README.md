# Marca GTT

Todo sale de la web ([`GTT-TalentArena/gtt-talentarena.github.io`](https://github.com/GTT-TalentArena/gtt-talentarena.github.io)):
los colores, las fuentes, el balón y cada imagen de esta carpeta y de [`profile/assets`](../profile/assets). Para
regenerarlas, en el repo de la web:

```bash
npm run build
npm run serve                               # http://localhost:4173
npm run previews -- http://localhost:4173   # en otra terminal
```

## Idea

El sistema editorial del portfolio de Nhoa (papel, titulares gigantes, una palabra en otra voz y metadatos en mono)
vestido de blaugrana. Lema: **_Més que dades._** («Més que un club» + «More than a Hack»: más que datos).

## Equipación: Casa

| Papel | Tinta | Acento | Blau | Grana | Estadio (fondo oscuro) |
| :-- | :-- | :-- | :-- | :-- | :-- |
| `#f3eee6` | `#0b0e2c` | `#a50044` | `#1d3fc9` | `#a50044` | `#0b0e2c` |

En el campo: local `#6b8cff`, visitante `#ff4f8a`, balón `#e8ff2e`.

## Tipografía

Una sola en todas partes (web, log e imágenes): **Bricolage Grotesque** para titulares, **Instrument Serif** cursiva
para la palabra que cambia el tono, **Geist** para el texto y **Geist Mono** para etiquetas y datos.

## Imágenes animadas

`banner.svg` y `site.svg` son SVG animados, con la misma técnica que el `header.svg` de jimy-k4: fuentes embebidas
(solo los caracteres usados) y animaciones SMIL, que GitHub reproduce dentro de una imagen. El balón da una vuelta
cada 24 s y el anillo, cada 40 s; con «Reducir movimiento» se quedan quietos.

## El balón

Un icosaedro truncado (el balón clásico) dibujado como una malla de datos: pentágonos en blaugrana, hexágonos
abiertos, nodos en los vértices y la cara oculta en rayos X. En la web gira solo y se puede chutar; en el README
rueda en bucle. En el avatar hace de punto del logo `gtt`. No usar el escudo ni las tipografías del FC Barcelona.

## Archivos para subir a mano

GitHub no deja cambiar esto por API:

| Archivo | Dónde |
| :-- | :-- |
| [`avatar.png`](avatar.png) | Organización → Settings → Profile picture |
| [`social-org.png`](social-org.png) | `.github` → Settings → Social preview |
| [`social-challenge.png`](social-challenge.png) | `more-than-a-hack-2027` → Settings → Social preview |
| [`social-web.png`](social-web.png) | `gtt-talentarena.github.io` → Settings → Social preview |

Equipo independiente: no estamos afiliados al FC Barcelona, Metrica Sports ni Mobile World Capital Barcelona.
