Diseño de una Interfaz Web Accesible para Gestión de Dispositivos IoT

Ejecución y despliegue del Dashboard IoT

El Dashboard IoT es una aplicación web diseñada para permitir la visualización e interpretación de datos obtenidos desde dispositivos conectados a Internet de las Cosas (IoT). La plataforma permite representar información de sensores mediante una interfaz gráfica, facilitando el monitoreo de variables en tiempo real y la supervisión del estado del sistema.

Para ejecutar correctamente el dashboard es necesario contar con los archivos principales del proyecto, los cuales contienen la estructura visual, los estilos de diseño y la lógica de funcionamiento de la interfaz web.

📌 Procedimiento de ejecución

Obtención del proyecto

El primer paso consiste en descargar el proyecto desde su ubicación de almacenamiento o realizar una clonación del repositorio donde se encuentra alojado. Esto permite disponer de todos los recursos necesarios para el funcionamiento del dashboard.

Carga del proyecto en el entorno de desarrollo

Se debe abrir la carpeta principal del proyecto mediante Visual Studio Code, un editor de código que permite administrar archivos HTML, CSS y otros recursos utilizados para el desarrollo web.

Verificación de la estructura del proyecto

Antes de iniciar la ejecución, es importante comprobar que los archivos se encuentren organizados correctamente:

📁 Dashboard-IoT
│
├── index.html
└── styles.css
index.html: contiene la estructura principal de la página web, incluyendo los elementos visuales del dashboard, paneles de información, gráficos y componentes de monitoreo.
styles.css: almacena las reglas de diseño encargadas de definir colores, distribución, tamaños, fuentes y apariencia general de la interfaz.

Inicialización de la aplicación web

Una vez verificados los archivos, se procede a abrir el archivo index.html, el cual funciona como punto de entrada del sistema y permite cargar la interfaz desarrollada.

Ejecución mediante Live Server

Para visualizar correctamente el dashboard se utiliza la extensión Live Server de Visual Studio Code. Esta herramienta crea un servidor local que permite ejecutar la aplicación en un navegador web, actualizando automáticamente los cambios realizados durante el desarrollo.

Visualización del Dashboard IoT

Finalmente, el navegador mostrará la interfaz gráfica del sistema, donde el usuario podrá observar los elementos implementados para el monitoreo IoT, como indicadores, tarjetas de información, gráficos y datos provenientes de los dispositivos conectados.
