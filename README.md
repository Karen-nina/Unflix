# Unflix 🎬

Unflix es una aplicación web de catálogo audiovisual inspirada en las interfaces de plataformas de streaming. Permite explorar películas y series, buscar títulos por nombre o género, consultar información del contenido y navegar entre recomendaciones mediante carruseles interactivos. Incluye pantallas de registro, inicio de sesión y perfil como parte de una demostración frontend.

```text
Estado: prototipo frontend / proyecto académico
```

![Logo de Unflix](img/logo.png)

## Índice
* [Funcionalidades principales](#funcionalidades-principales)
* [Objetivo](#objetivo)
* [Screenshots](#screenshots)
* [Lenguajes y tecnologías](#-lenguajes-y-tecnologías)
* [Cómo ejecutar](#cómo-ejecutar)
* [Autora](#autora)

## Funcionalidades principales
- **Catálogo de películas y series:** acceso a títulos con portadas, distribuidos en secciones como «Continuar viendo», «Recomendaciones» y «Lo más nuevo».
- **Búsqueda por nombre:** filtrado de títulos en el navegador a medida que se escribe.
- **Filtros por categoría:** clasificación por géneros como acción, comedia, drama, anime, romance, terror y documentales; posibilidad de combinar género y texto.
- **Navegación por tipo de contenido:** vistas para todas las producciones, películas o series.
- **Páginas de detalle:** información sobre títulos, género, actores, sinopsis, videos incrustados y enlaces externos.
- **Selección de temporadas y capítulos:** controles dinámicos en páginas de series para consultar episodios según la temporada.
- **Carruseles y recomendaciones similares:** exploración visual con transiciones y desplazamiento de contenidos.
- **Formularios de usuario:** interfaces de inicio de sesión, registro, recuperación de contraseña y perfil, con validaciones en JavaScript.
- **Preferencias de perfil y métodos de pago simulados:** formularios para practicar su ingreso y validación sin procesamiento real de pagos.
- **Diseño adaptable:** menú desplegable y estilos para diferentes tamaños de pantalla.

> **Alcance:** es un prototipo de frontend. El acceso se simula mediante datos guardados en `localStorage`; no existe autenticación segura con servidor, base de datos de usuarios, recuperación real de contraseñas ni cobros integrados. Los videos disponibles utilizan recursos o enlaces externos, no una infraestructura propia de streaming.

## Objetivo
Desarrollar una experiencia web interactiva inspirada en una plataforma de streaming utilizando **HTML, CSS y JavaScript**, con énfasis en maquetación, navegación, validación de formularios y manipulación dinámica del DOM.

El proyecto permite poner en práctica búsquedas y filtros sobre colecciones de datos locales, diseño responsive, almacenamiento del navegador, navegación entre páginas y componentes de interfaz desarrollados con **jQuery y Slick Carousel**.

## Screenshots
El repositorio incluye imágenes y portadas del catálogo, así como el logo original de Unflix. Para ilustrar las funcionalidades de la aplicación, se recomienda incorporar capturas reales de las siguientes pantallas:

- Inicio de sesión (`index.html`).
- Catálogo principal (`home.html`).
- Búsqueda y filtrado de títulos (`home.html`).
- Detalle de película o serie (por ejemplo, `dr_house.html`).
- Perfil de usuario (`perfil.html`).

> Pendiente: agregar capturas reales de la interfaz en funcionamiento.

## 🛠 Lenguajes y tecnologías
- **HTML5:** estructura y contenido de las distintas páginas.
- **CSS3:** estilos, componentes visuales y diseño adaptable.
- **JavaScript (Vanilla JS):** lógica de navegación, formularios, búsquedas, filtros e interacción.
- **jQuery:** manejo de eventos, animaciones y elementos de la interfaz.
- **Slick Carousel:** carruseles interactivos para el catálogo y contenidos relacionados.
- **Web Storage API (`localStorage`):** almacenamiento local de datos de demostración y estado de navegación.
- **YouTube Embed:** inserción de videos externos mediante `iframe`.
- **Git y GitHub:** control de versiones y alojamiento del código fuente.

## Cómo ejecutar

### Requisitos
- Navegador web moderno con JavaScript habilitado.
- Git, si se desea clonar el proyecto.

No requiere instalación de dependencias mediante npm, base de datos ni un servidor backend.

### 1. Clonar el repositorio
```bash
git clone https://github.com/Karen-nina/Unflix.git
cd Unflix
```

### 2. Abrir la aplicación
Abrir el archivo `index.html` en un navegador.

También se puede utilizar un servidor local, por ejemplo mediante la extensión **Live Server** de Visual Studio Code, para acceder al proyecto desde una dirección como:

```text
http://127.0.0.1:5500/index.html
```

La dirección y el puerto pueden variar según la configuración del servidor local.

### 3. Explorar la interfaz
1. En el formulario inicial, completar nombre de usuario y contraseña para ingresar al catálogo de demostración.
2. Navegar por películas y series, explorar los carruseles y utilizar los filtros de nombre y categoría.
3. Abrir las fichas de contenido para consultar sinopsis, actores, videos y, en determinadas series, temporadas y episodios.
4. Acceder al perfil para explorar las opciones de edición simuladas.

**Importante:** no ingresar contraseñas reales ni información verdadera de tarjetas bancarias. Los formularios fueron desarrollados para demostrar validaciones en el navegador y ciertas preferencias pueden guardarse en `localStorage` sin las protecciones de una aplicación de producción.

## Autora
- **Karen Nina Coela** — [GitHub](https://github.com/Karen-nina)

---

Proyecto de demostración frontend. Documentación basada en los archivos y funcionalidades presentes en el repositorio.
