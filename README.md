# SNEAKER VAULT - Tienda Online

Tienda de zapatillas premium con catálogo dinámico y carrito de compras integrado con WhatsApp. Diseñada para ser fácil de usar por personas de cualquier edad.

## 🚀 Desplegar en GitHub Pages

1. Sube este repositorio a GitHub
2. Ve a **Settings** > **Pages**
3. En **Source**, selecciona la rama `main` (o `master`)
4. Haz clic en **Save**
5. Tu sitio estará disponible en: `https://tu-usuario.github.io/Pagina-web-Nancy/`

## 📝 Características

- **Interfaz separada**: Vista para clientes y panel de administración independiente
- **Seguridad**: El panel de administración está protegido con contraseña
- **Catálogo dinámico**: Los productos se guardan en localStorage
- **Carrito de compras**: Agrega productos y selecciona talla
- **Pedidos por WhatsApp**: Los clientes envían sus pedidos directamente a tu WhatsApp
- **Diseño accesible**: Botones grandes, textos claros, fácil de usar para personas mayores
- **Diseño responsive**: Se adapta perfectamente a móviles, tablets y escritorio

## ⚙️ Configuración

### Cambiar número de WhatsApp

Para cambiar el número donde recibes los pedidos:

1. Abre `index.html`
2. Busca la línea 426: `const phone = "573100000000";`
3. Reemplaza con tu número de WhatsApp (incluyendo código de país)
4. Guarda y sube los cambios

### Configurar contraseña de administrador

La primera vez que ingreses al panel de administración, se te pedirá crear una contraseña. Esta contraseña se guarda en tu navegador.

## 🔐 Panel de Administración

### Cómo acceder:

1. Ve a `login.html` en tu sitio (o haz clic en el enlace "Admin" en la esquina inferior izquierda)
2. Ingresa tu contraseña
3. Serás redirigido al panel de administración

### Agregar productos:

1. En el panel de administración, completa los campos:
   - Nombre del producto
   - Precio (ej: 450.000)
   - URL de la imagen
2. Haz clic en "GUARDAR PRODUCTO"
3. El producto aparecerá automáticamente en la tienda

### Editar o eliminar productos:

- Haz clic en "EDITAR" para modificar un producto existente
- Haz clic en "ELIMINAR" para borrar un producto del catálogo

## 👥 Para los Clientes

Los clientes solo ven la tienda (`index.html`) donde pueden:
- Ver el catálogo de productos
- Agregar productos al carrito seleccionando la talla
- Finalizar el pedido por WhatsApp

**Importante**: Los clientes NO tienen acceso al panel de administración.

## 📦 Notas sobre el almacenamiento

Los productos se guardan en el localStorage del navegador. Esto significa:
- Los cambios persisten en el dispositivo donde se hicieron
- Si cambias de dispositivo, verás los productos base (Jordan 4 y Nike Dunk)
- Para cambios permanentes que todos vean, edita el array `products` en `index.html` (líneas 326-329)
