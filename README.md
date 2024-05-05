# Tienda Virtual - Aplicación Flask
Esta es una aplicación Flask básica que implementa una tienda en línea simple. Los usuarios pueden navegar a través de una lista de productos y ver información detallada sobre cada uno.

## Características
* Muestra una lista de productos con categorías, marcas, nombres, precios y niveles de stock.
* Permite a los usuarios navegar a páginas de productos individuales que muestran descripciones detalladas.
* Incluye un botón "Inicio" para regresar a la lista de productos.

## Ejecutando la aplicación
1. **Prerequisitos:**
  *Python 3.x (https://www.python.org/downloads/)
  *pip (generalmente incluido con la instalación de Python)
   
2. **Instalar dependencias:**
Bash
pip install flask sqlite3

3. **Crear la base de datos:**
Ejecute el script crear_db.py para crear la base de datos web2.sqlite3 con la tabla productos e introducir datos de ejemplo.

4. **Ejecutar la aplicación:**
Navegue al directorio del proyecto en su terminal y ejecute:
Bash
python main.py

5. **Acceder a la aplicación:**
Abra su navegador web y visite http://localhost:5000/ (puerto predeterminado).

##Estructura del código
La aplicación consta de los siguientes archivos:

* main.py: El script principal de la aplicación Flask, responsable de inicializar la conexión a la base de datos, cargar datos de productos, definir rutas y ejecutar el servidor.
* crear_db.py: Un script para crear la base de datos web2.sqlite3 e insertar datos de productos de ejemplo.
* base.html: La plantilla base para todas las páginas, que proporciona un diseño con un título y un marcador de posición para el contenido principal.
* index.html: La plantilla para la página de lista de productos, que extiende la plantilla base y muestra una tabla de productos.
* producto.html: La plantilla para páginas de productos individuales, que extiende la plantilla base y muestra información detallada del producto.
* estilo.css: La hoja de estilos que contiene reglas CSS para diseñar los elementos visuales de la aplicación.

##Personalización
Puede personalizar la aplicación mediante:

* Modificando los datos del producto en crear_db.py.
* Actualizando las plantillas (archivos HTML) para cambiar el diseño y el contenido.
* Agregando rutas y funcionalidades adicionales en main.py.
* Personalizando los estilos en estilo.css.

##Licencia
Esta aplicación se proporciona sin una licencia específica. Puede usar y modificar el código a su discreción.
