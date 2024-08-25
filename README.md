# Space Nasa Arequipa

# Proyecto: Estructura de Archivos

## Descripción
Este proyecto está estructurado en varios directorios y archivos para organizar los diferentes aspectos de la aplicación, como estilos, imágenes, fuentes y componentes. Está configurado con Vite, TypeScript y React. A continuación, se detalla la estructura de carpetas y archivos que debe seguirse:

## Estructura del Proyecto

<!-- src/  
├── assets/  
│   ├── css/  
│   │   └── Loading.css  
│   ├── images/  
│   │   └── react.svg  
│   └── fonts/  
├── components/  
│   └── Loading.tsx  
├── App.tsx  
└── main.tsx   -->

## Descripción de las Carpetas y Archivos

- **src/**: Carpeta raíz que contiene todos los archivos fuente del proyecto.
  - **assets/**: Directorio para almacenar recursos estáticos como estilos, imágenes y fuentes.
    - **css/**: Carpeta para archivos de estilos CSS.
      - **Loading.css**: Archivo de estilos CSS para el componente Loading.
    - **images/**: Carpeta que almacena imágenes usadas en la aplicación.
      - **react.svg**: Archivo SVG de la imagen de React.
    - **fonts/**: Carpeta para fuentes personalizadas utilizadas en la aplicación.
  - **components/**: Directorio que contiene los componentes de React.
    - **Loading.tsx**: Componente React escrito en TypeScript para mostrar una animación de carga.
  - **App.tsx**: Archivo principal de la aplicación donde se ensamblan los componentes.
  - **main.tsx**: Archivo de entrada que inicializa la aplicación y monta el componente principal en el DOM.

## Recomendaciones
- Asegúrate de seguir esta estructura para mantener el proyecto organizado y fácil de mantener.
- Coloca los archivos de recursos (como imágenes y fuentes) en sus respectivas carpetas dentro de **assets/**.
- Los componentes de React deben almacenarse en la carpeta **components/** y pueden tener sus propios archivos de estilo en **assets/css/** si es necesario.
- **App.tsx** debe ser utilizado para gestionar la estructura principal de la aplicación, mientras que **main.tsx** se encarga de montar la aplicación en el DOM.

## Instalación y Configuración
1. Clona el repositorio en tu máquina local.
2. Navega al directorio del proyecto:
```
   cd nombre-del-proyecto

```
3. Instala las dependencias necesarias utilizando npm o yarn:
```
   npm install
   o
   yarn install
```
4. Inicia la aplicación en modo de desarrollo:
```
   npm run dev
   o
   yarn dev
```
5. La aplicación estará disponible en http://localhost:5173


## Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.


¡Gracias por contribuir!
