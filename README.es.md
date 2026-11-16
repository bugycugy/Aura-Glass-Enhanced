# Aura Glass

[🇹🇷 Türkçe](README.md) · [🇬🇧 English](README.en.md) · [🇪🇸 Español](README.es.md)

**Spotify, con un aspecto de cristal.** Cada canción transforma la aplicación con los colores de su portada.

Aura Glass es un tema para [Spicetify](https://spicetify.app) inspirado en el diseño Liquid Glass de Apple. La portada de la canción que suena se convierte en el fondo; los paneles se transforman en superficies de cristal esmerilado teñidas con esos colores. El reproductor flota como una cápsula junto a un disco de vinilo giratorio. Cambia la canción y cambia toda la paleta.

![Aura Glass](preview.png)

## Por qué te va a gustar

- **Cambia con tu música.** El fondo, el tono del cristal, los botones, la barra de progreso y el volumen se adaptan a la portada de cada canción.
- **Un reproductor con alma de vinilo.** La portada se convierte en un disco que gira y se detiene cuando pausas la reproducción.
- **Modo escaparate.** Pulsa `Alt + S` para convertir Spotify en una pantalla musical a pantalla completa, ideal para el salón o un segundo monitor. Incluye un vinilo giratorio, reloj, controles y letras sincronizadas. El verso actual se resalta y, al hacer clic en cualquier línea, la canción salta a ese momento.
- **Personalízalo sin tocar código.** Ajusta el color del cristal (tomado de la portada, cuatro paletas predeterminadas o un color propio), el desenfoque, la opacidad, el redondeo y el brillo desde el panel de ajustes. Los cambios se aplican al instante y se guardan.
- **Temporizador de apagado.** Elige 15, 30, 45 o 60 minutos, o el final de la canción actual. El volumen baja poco a poco antes de pausar la reproducción y después vuelve a su nivel anterior.
- **Bonito y legible.** El efecto de cristal se aplica a las barras laterales y los paneles, no encima de las listas. Si el color de la portada dificulta la lectura, el tema lo ajusta automáticamente.
- **Cuida tu ordenador.** Las animaciones se detienen cuando Spotify está en segundo plano. El modo de bajo consumo reduce el desenfoque y desactiva las animaciones.
- **Accesible.** Respeta las preferencias del sistema para reducir transparencias, aumentar el contraste y reducir el movimiento. El panel de ajustes y el modo escaparate se pueden manejar con el teclado.

## Capturas

### Un reproductor que cambia de color con cada portada

Los botones, los tiempos, la barra de progreso, el volumen y el botón de reproducción se adaptan a la portada. Aquí puedes ver el mismo reproductor con cuatro paletas distintas:

![Reproductor con cuatro paletas](capturas/colores.png)

### La portada convertida en un vinilo giratorio

Un disco redondo con una etiqueta central. Gira mientras suena la música y se detiene al pausarla.

![Portada con aspecto de vinilo](capturas/disco.gif)

### Modo escaparate (`Alt + S`)

Una vista a pantalla completa con la portada, el vinilo giratorio, el reloj y las letras sincronizadas. Los versos anteriores se atenúan, el actual se ilumina y los siguientes permanecen desenfocados.

![Modo escaparate](capturas/escaparate.png)

### Panel de ajustes

Color del cristal, desenfoque, opacidad, redondeo, brillo, efectos y temporizador de apagado. Sin modificar código.

![Panel de ajustes](capturas/ajustes.png)

## Instalación

### Desde Marketplace (recomendado)

1. Abre Spotify con Spicetify y entra en **Marketplace** (el icono del carrito).
2. Ve a **Temas**, busca **Aura Glass** y pulsa **Instalar**.

Si Marketplace te pide configurar `current_theme` como `marketplace`, ejecuta estos comandos y vuelve a abrir Spotify:

```bash
spicetify config current_theme marketplace
spicetify apply
```

### Instalación manual

1. Copia esta carpeta en el directorio de temas de Spicetify con el nombre `AuraGlass`:
   - Windows: `%APPDATA%\\spicetify\\Themes\\AuraGlass`
   - macOS / Linux: `~/.config/spicetify/Themes/AuraGlass`
2. Ejecuta:

```bash
spicetify config current_theme AuraGlass color_scheme Gece inject_css 1 replace_colors 1 inject_theme_js 1
spicetify apply
```

## Uso

| Para… | Haz… |
| --- | --- |
| Abrir los ajustes | Pulsa el icono de paleta, arriba a la izquierda |
| Abrir el modo escaparate | Pulsa `Alt + S` o el icono de vinilo, arriba a la izquierda |
| Salir del modo escaparate | Pulsa `Esc` o haz clic en ✕ |
| Saltar a un verso | Haz clic en la línea de la letra en el modo escaparate |
| Avanzar o retroceder | Usa las flechas sobre la barra de progreso (`Mayús` para 30 segundos) |
| Programar el apagado | Ajustes → Temporizador de apagado |

## Requisitos

- Versión de escritorio de Spotify compatible con Spicetify. La versión de Microsoft Store no admite Spicetify.
- Spicetify 2.x.

Probado con Spotify 1.3.8 y Spicetify 2.46.4 en Windows 11.

## Licencia

MIT
