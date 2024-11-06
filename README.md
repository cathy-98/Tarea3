# README para el Proyecto de Ciberseguridad: Hospital Base San José

## Descripción del Proyecto

Este proyecto es un sitio web para el **Hospital Base San José**, diseñado para proporcionar información sobre los servicios médicos disponibles, facilitar el contacto con los pacientes y permitir la reserva de citas. La interfaz es responsiva y amigable, adaptándose a diferentes dispositivos.

## Tabla de Contenidos

1. [Características](#características)
2. [Tecnologías Utilizadas](#tecnologías-utilizadas)
3. [Estructura del Proyecto](#estructura-del-proyecto)
4. [Instrucciones de Instalación](#instrucciones-de-instalación)
5. [Uso](#uso)
6. [Contribuciones](#contribuciones)
7. [Licencia](#licencia)

## Características

- Navegación intuitiva con menú hamburguesa.
- Secciones informativas sobre el equipo médico y servicios del hospital.
- Formulario de contacto para consultas.
- Integración de Google Maps para facilitar la ubicación del hospital.

## Tecnologías Utilizadas

- **HTML5**: Estructura del contenido.
- **CSS3**: Estilo visual del sitio.
- **Sass**: Preprocesador CSS para estilos.
- **Bootstrap**: Framework para diseño responsivo.
- **JavaScript**: Interactividad y manejo de eventos.

## Estructura del Proyecto

Actualmente, todos los archivos están organizados en la carpeta principal del proyecto:

```
Tarea3/ ├── index.html # Página principal del hospital ├── contact.html # Página de contacto ├── team.html # Página del equipo médico │ ├── styles/ # Carpeta que contiene los estilos │ ├── abstracts/ # Contiene variables y mixins │ │ ├── _mixins.scss │ │ └── _variables.scss │ ├── base/ # Estilos base │ │ └── _base.scss │ ├── layout/ # Estructura del diseño │ │ ├── _footer.scss │ │ ├── _grid.scss │ │ ├── _header.scss │ │ └── _navigation.scss │ ├── pages/ # Estilos específicos de cada página │ │ ├── _contact.scss │ │ ├── _home.scss │ │ └── _team.scss │ └── main.scss # Archivo principal de estilos SCSS │ ├── img/ # Imágenes utilizadas en el sitio │ ├── doctor1.webp │ ├── doctor2.webp │ ├── doctor3.webp │ └── doctor4.webp │ └── js/ # Archivos JavaScript ├── jquery/jquery-3.6.0.js └── bootstrap/bootstrap.js
```

## Instrucciones de Instalación
1. Clona el repositorio:
   ```bash
   git clone https://github.com/cathy-98/Tarea3

2. Navega en el directorio del proyecto:
   cd Tarea3

3. Abre el archivo index.html en tu navegador para ver el sitio.

