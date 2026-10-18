# WhiteRabbit

Películas, series y anime en streaming desde torrents, con una interfaz al estilo Netflix. El instalador incluye todo lo necesario, incluido el reproductor de video, así que **no hace falta instalar ningún otro programa**.

## Descargar

**[Descargar la versión más reciente](https://github.com/gersongrzesiek/popcorntime-releases/releases/latest)**

En la página de la versión, dentro de **Assets**, elige:

| Sistema | Archivo |
|---|---|
| Windows 10 / 11 (64 bits) | `WhiteRabbit_<versión>_x64-setup.exe` |
| Mac con chip Apple (M1 o posterior) | `WhiteRabbit_<versión>_aarch64.dmg` (por ahora, en la [versión 0.4.0](https://github.com/gersongrzesiek/popcorntime-releases/releases/tag/v0.4.0)) |

## Requisitos

- Windows 10 u 11 de 64 bits, conectado a internet.
- Al menos 1 GB libre (unos 200 MB para la app y hasta 600 MB de caché temporal de video).
- No hacen falta permisos de administrador: se instala solo para tu usuario.

## Instalar en Windows

1. **Descarga** el archivo que termina en `_x64-setup.exe`. También puedes pasarlo a otra PC por USB, correo o Google Drive.
2. **Ábrelo** con doble clic.
3. Si aparece **"Windows protegió tu PC"**, haz clic en **Más información** y luego en **Ejecutar de todas formas**. Aparece porque la app no tiene firma digital de pago, no porque tenga un virus.
4. **Sigue el asistente** (está en inglés):
   - *Welcome* → **Next**
   - *Choose Install Location* → deja la carpeta y pulsa **Next**
   - *Choose Start Menu Folder* → **Install**
   - *Installing* → espera. Si la PC no tiene Microsoft WebView2 (Windows 10 muy antiguos), el instalador lo descarga e instala solo.
   - *Completing* → deja marcadas **Create desktop shortcut** y **Run WhiteRabbit**, y pulsa **Finish**.

## Primer uso

1. Abre WhiteRabbit desde el escritorio o el menú Inicio.
2. Busca una película, serie o anime y pulsa **Reproducir**. El video empieza en pocos segundos mientras se descarga.
3. La primera vez puede salir el aviso del **Firewall de Windows**. Marca **Redes privadas** y pulsa **Permitir acceso**. Así los videos cargan más rápido y funciona el envío a la tele.

### Ver en la tele

En el reproductor, el botón de **transmitir** envía el video a un Chromecast o Google TV que esté en la misma red Wi-Fi que la PC. La PC tiene que quedarse encendida, porque es la que descarga el video.

## Actualizaciones

Son automáticas. Cuando hay una versión nueva, abajo a la derecha aparece **"Nueva versión disponible"**. Pulsa **Actualizar** y la app se instala y se reinicia sola, conservando tu lista y tu progreso.

## Problemas frecuentes

- **El video tarda o se queda cargando:** vuelve a la ficha y elige otra fuente, de preferencia una con más semillas.
- **Sale una ventana de verificación de Cloudflare:** pasa con algunas fuentes de 1337x. Espera unos segundos.
- **No aparece la tele al transmitir:** revisa que la tele y la PC estén en la misma red y que el firewall permita a WhiteRabbit en redes privadas.

## Desinstalar

Inicio → Configuración → Aplicaciones → Aplicaciones instaladas → **WhiteRabbit** → ⋯ → **Desinstalar**.

---

Instrucciones detalladas, también para Mac: [INSTALAR.txt](https://github.com/gersongrzesiek/popcorntime-releases/releases/latest/download/INSTALAR.txt).
