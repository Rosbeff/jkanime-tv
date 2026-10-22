<div align="center">

![JKAnime — Android TV y Móvil](assets/jkanime-banner.svg)

# JKAnime · Android TV y Móvil

**Tu anime, a tu ritmo. En la tele y en el bolsillo.**

Una app independiente conectada a JKAnime, con una interfaz pensada para el mando de la TV y otra adaptada al móvil.

![Versión 1.0](https://img.shields.io/badge/versión-1.0-FFAD39?style=flat-square&labelColor=17191F)
![Android 6.0 o posterior](https://img.shields.io/badge/Android-6.0%2B-78C257?style=flat-square&labelColor=17191F)
![TV y móvil](https://img.shields.io/badge/ediciones-TV%20%2B%20Móvil-FFFFFF?style=flat-square&labelColor=17191F)

### [📺 Descargar para TV](https://github.com/Rosbeff/jkanime-tv/releases/latest/download/JKAnimeTV.apk) · [📱 Descargar para móvil](https://github.com/Rosbeff/jkanime-tv/releases/latest/download/JKAnimeMobile.apk)

[Qué ofrece](#qué-ofrece) · [Instalación](#instalación) · [Tu cuenta](#tu-cuenta) · [Ayuda](#ayuda)

</div>

---

## Qué ofrece

| Descubre tu próxima serie | Continúa donde lo dejaste |
| :--- | :--- |
| **Últimos episodios** con las novedades de JKAnime y actualización automática al usar Inicio. | **Seguir viendo** con historial, posición de reproducción y opción de quitar series desde los tres puntos. |
| **Catálogo, búsqueda y ranking** en sus propias secciones. | **Favoritos** para guardar las series que quieres seguir. |
| **Top de 50 animes** con carátulas, votos y sinopsis al seleccionar una serie en TV. | **Capítulos vistos**: marca uno o un bloque completo hasta el episodio que elijas. |
| **Episodios por grupos** y búsqueda por número para llegar directamente al capítulo. | **Cuenta opcional** para sincronizar la biblioteca entre tus dispositivos. |

### Dos formas de disfrutarla

| 📺 Android TV | 📱 Android móvil |
| :--- | :--- |
| Navegación con cruceta y foco visible. | Interfaz vertical y navegación táctil. |
| Filas de series sobre una interfaz oscura. | Filas deslizables, Mi lista y accesos a Explorar. |
| **OK** para pausar o continuar el vídeo. | Controles al tocar el vídeo y barra de posición. |
| **← / →** para retroceder o avanzar diez segundos. | Pantalla completa horizontal y vuelta a la vista vertical. |
| Actualización del APK desde el menú. | Actualización del APK desde el menú. |

Los controles de reproducción dependen del servidor elegido. La disponibilidad de capítulos, imágenes y vídeos depende de JKAnime y de sus servidores.

## Instalación

### 1. Elige tu edición

| Dispositivo | Archivo que debes instalar |
| :--- | :--- |
| Televisor o dispositivo con **Android TV** | [**JKAnimeTV.apk**](https://github.com/Rosbeff/jkanime-tv/releases/latest/download/JKAnimeTV.apk) |
| Teléfono Android | [**JKAnimeMobile.apk**](https://github.com/Rosbeff/jkanime-tv/releases/latest/download/JKAnimeMobile.apk) |

**Solo necesitas un APK por dispositivo.** Los archivos `update.json` y `update-mobile.json` sirven a la app para buscar actualizaciones; no se instalan.

### 2. Instala y abre

1. Descarga el APK correspondiente. En la TV puedes transferirlo desde el móvil o mediante una memoria USB.
2. Cuando Android lo solicite, permite que la aplicación con la que abres el archivo instale ese APK.
3. Completa la instalación y abre JKAnime.
4. Para buscar próximas versiones, entra en **Menú → Actualizaciones**.

Requiere **Android 6.0 o posterior** y conexión a Internet. La edición de TV necesita Android TV; un televisor con otro sistema, como Tizen o webOS, no instala estos APK.

Al actualizar, instala sobre la versión anterior para conservar tu biblioteca y ajustes. Ambas ediciones muestran la versión **1.0**; su contador interno permite actualizar desde publicaciones anteriores.

## Tu cuenta

### Una biblioteca para ti

Puedes usar la app sin cuenta. Si quieres compartir tu progreso entre móvil y TV:

1. Pulsa el **icono de perfil junto a la lupa** y selecciona **Iniciar sesión**.
2. Selecciona **Crear cuenta** y elige tu usuario y contraseña.
3. Guarda el **código privado de recuperación** que se muestra al registrarte.
4. Inicia sesión con esa misma cuenta en el otro dispositivo.

Se sincronizan **favoritos, historial, capítulos vistos y posición de reproducción**. Cada persona debe usar su propia cuenta.

La biblioteca que tenías sin cuenta se añade únicamente si marcas la opción correspondiente. Los ajustes de pantalla y del reproductor se mantienen en cada dispositivo.

### GitHub y GitLab

En el móvil puedes vincular GitHub o GitLab desde **Mi cuenta** y utilizarlos después para volver a entrar. **Primero crea tu cuenta de la app y vincula el proveedor.** En la TV utiliza tu usuario y contraseña de JKAnime.

La vinculación solicita datos de perfil y correo para identificarte; **no solicita acceso a repositorios**. Tras entrar con un proveedor vinculado, la app permite recuperar la contraseña para volver a acceder también desde la TV.

### Recuperación y privacidad

- El código privado se utiliza una sola vez y permite cambiar tu contraseña. Guarda uno nuevo después de recuperarla.
- El registro con usuario no requiere correo electrónico; no hay recuperación por email.
- Las bibliotecas se separan por cuenta. La sincronización utiliza Supabase y el administrador del servicio puede gestionar su base de datos.
- Los tokens de sesión se guardan cifrados mediante Android Keystore. La contraseña no se guarda en el dispositivo.
- Si compartes el dispositivo, cierra sesión al terminar.

> Las funciones de cuenta son nuevas en esta versión. Se han comprobado la separación de usuarios y la recuperación mediante la API; la validación completa del registro y del retorno de los proveedores en los dispositivos sigue pendiente.

## Ayuda

<details>
<summary><strong>¿Tengo que descargar todos los archivos de la publicación?</strong></summary>

No. Instala únicamente el APK de tu dispositivo. Los dos APK son aplicaciones distintas: TV y móvil pueden coexistir.

</details>

<details>
<summary><strong>¿Es necesario tener un navegador en la TV?</strong></summary>

No necesitas abrir JKAnime en un navegador aparte para buscar series y ver episodios. La app presenta su propia navegación para TV. La vinculación de GitHub o GitLab se realiza desde el móvil con su navegador.

</details>

<details>
<summary><strong>¿Por qué no carga un episodio?</strong></summary>

Comprueba tu conexión y prueba otro servidor desde el reproductor. Una incidencia en JKAnime o en el alojamiento del vídeo puede impedir la reproducción.

</details>

<details>
<summary><strong>¿Dónde comunico un problema?</strong></summary>

Abre una [incidencia](https://github.com/Rosbeff/jkanime-tv/issues) indicando la edición, la versión, el dispositivo y los pasos para reproducir el fallo. Si adjuntas una imagen, oculta datos personales. No compartas contraseñas, códigos de recuperación ni tokens.

</details>

---

<div align="center">

**[Descargas y novedades](https://github.com/Rosbeff/jkanime-tv/releases) · [Comunicar un problema](https://github.com/Rosbeff/jkanime-tv/issues)**

Cliente independiente, sin afiliación oficial con JKAnime, GitHub o GitLab.  
Este repositorio distribuye las aplicaciones y sus actualizaciones; no aloja episodios.

</div>
