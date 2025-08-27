Aplicación de Búsqueda de Libros y Favoritos
Este proyecto es una aplicación móvil híbrida desarrollada con Ionic y Vue 3. Su objetivo principal es demostrar la integración de una API pública para buscar libros, la navegación entre múltiples vistas, y el almacenamiento de datos local para gestionar una lista de favoritos.

Funcionalidades ✨
Búsqueda de Libros: Permite a los usuarios buscar libros utilizando la Google Books API.

Lista de Resultados: Muestra una lista de libros relevantes con su título, autor y una miniatura de la portada.

Detalles del Libro: Navega a una vista de detalles que muestra información completa del libro, como la descripción y la fecha de publicación.

Gestión de Favoritos: Permite a los usuarios guardar libros en una lista de "Favoritos" que se almacena localmente en el dispositivo.

Pantalla de Favoritos: Una vista dedicada para ver todos los libros guardados como favoritos.

Manejo de Errores: Incluye un manejo básico de errores y estados de carga para mejorar la experiencia de usuario.

Autenticación: Proporciona un flujo de cierre de sesión básico.

Tecnologías Utilizadas 🛠️
Framework: Ionic Framework (versión más reciente)

Biblioteca de UI: Vue.js 3

Peticiones HTTP: Axios

Almacenamiento Local: Capacitor Preferences

Autenticación: Firebase Auth (para el flujo de login y logout)

Instalación y Configuración 🚀
Sigue estos pasos para instalar y ejecutar el proyecto en tu máquina local.

1. Requisitos previos
Asegúrate de tener instalado Node.js y el CLI de Ionic de forma global.

npm install -g @ionic/cli

2. Clona o descarga el proyecto
Si ya tienes los archivos, simplemente navega a la carpeta del proyecto en tu terminal.

# Si es un nuevo proyecto
ionic start my-book-app tabs --type vue --capacitor
cd my-book-app

3. Instala las dependencias
Desde la raíz del proyecto, ejecuta el siguiente comando para instalar todas las bibliotecas necesarias.

npm install
npm install axios
npm install @capacitor/preferences

4. Configuración de Firebase
Asegúrate de que tu proyecto tenga configurada la instancia de Firebase como se describe en el services/firebase.ts. Si no la tienes, necesitarás crear una en la consola de Firebase.

5. Ejecutar la aplicación
Puedes ejecutar la aplicación en el navegador o en un emulador/dispositivo.

# Ejecutar en el navegador
ionic serve

# Ejecutar en un emulador Android/iOS
ionic capacitor run android
ionic capacitor run ios

Estructura del Proyecto 📁
src/views/: Contiene los componentes de las vistas principales de la aplicación (BookSearchPage.vue, BookDetailsPage.vue, FavoritesPage.vue).

src/services/: Contiene los servicios que interactúan con APIs externas y el almacenamiento local (books.service.ts, favorites.service.ts, firebase.ts).

src/router/: Configuración del enrutamiento de la aplicación.

Contribuciones 🤝
Siéntete libre de clonar este proyecto, usarlo como base para tus propios desarrollos o mejorarlo.

Capturas
<img width="599" height="936" alt="image" src="https://github.com/user-attachments/assets/26143b8c-34ec-4e64-802d-a9cf07bf69d5" />
<img width="496" height="925" alt="image" src="https://github.com/user-attachments/assets/3dacfe84-5055-4d29-99eb-8db70bdd9198" />
<img width="471" height="511" alt="image" src="https://github.com/user-attachments/assets/95cc6730-1198-49d3-a601-81847bcd3ab5" />


