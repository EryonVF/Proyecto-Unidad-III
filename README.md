# Proyecto-Unidad-III

Funcionalidades y características.

## Funcionalidades

- **Inicio de Sesión:** Esta aplicación cuenta con un sistema de inicio de sesión que permite a los usuarios autenticarse como "admin" o "cliente" y la contraseña sera la misma que el usuario. Dependiendo de su rol, se redirige al usuario a la página correspondiente (admin.html o shop.html). El rol del usuario se almacena en localStorage.

- **Encabezado con Menú:** Pues le agregue un encabezado basico, con el logotipo de la tienda en la parte de abajo, enlaces a las páginas de catálogo de productos, tienda y acerca de. Además, hay un botón de "Cerrar Sesión" que ejecuta la función logout() para eliminar el rol del usuario de localStorage y redirigirlo a la página de inicio de sesión.

- **Roles de Usuario:** Los roles de usuario se utilizan para determinar qué enlaces y funcionalidades se muestran en las páginas. Por ejemplo, el catálogo de productos solo se muestra si el usuario es un administrador.

- **Catálogo de Productos (CRUD):** En la página de administrador (admin.html), los usuarios administradores pueden agregar, editar, eliminar y listar productos. Se utiliza una tabla para mostrar los productos, incluyendo la imagen. Se implementan botones para cada acción (Agregar, Editar, Eliminar). JavaScript se utiliza para gestionar las operaciones CRUD y actualizar la lista de productos en tiempo real.

- **Tienda con Calculadora:** La página de tienda (shop.html) permite a los usuarios agregar productos al carrito de compra, ajustar la cantidad y mostrar un resumen de la compra. También se incluye la opción de habilitar o deshabilitar una calculadora en la misma página. JavaScript se utiliza para realizar cálculos y actualizar el resumen de compra.

- **Homogeneidad de Páginas:** Se define una estructura de página común que incluye encabezado, contenido y pie de página. CSS y Bootstrap se utilizan para aplicar estilos consistentes a todas las páginas y asegurarse de que sean responsivas para diferentes tamaños de dispositivos.

