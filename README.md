# SNEAKER VAULT - Tienda Online

Tienda de zapatillas premium con catálogo dinámico y carrito de compras integrado con WhatsApp.

## 🚀 Desplegar en GitHub Pages

1. Sube este repositorio a GitHub
2. Ve a **Settings** > **Pages**
3. En **Source**, selecciona la rama `main` (o `master`)
4. Haz clic en **Save**
5. Tu sitio estará disponible en: `https://tu-usuario.github.io/Pagina-Web-Nancy/`

## 📝 Características

- **Catálogo dinámico**: Los productos se guardan en localStorage
- **Carrito de compras**: Agrega productos y selecciona talla
- **Pedidos por WhatsApp**: Los clientes envían sus pedidos directamente a tu WhatsApp
- **Panel de administración**: Presiona la tecla `A` para mostrar/ocultar el panel admin
- **Diseño responsive**: Se adapta a móviles y escritorio

## ⚙️ Configuración

Para cambiar el número de WhatsApp donde recibes los pedidos:

1. Abre `index.html`
2. Busca la línea 279: `const phone = "573100000000";`
3. Reemplaza con tu número de WhatsApp (incluyendo código de país)
4. Guarda y sube los cambios

## 📦 Agregar productos

1. Abre el sitio web
2. Presiona la tecla `A` para mostrar el panel de administración
3. Completa los campos: Nombre, Precio, URL de imagen
4. Haz clic en "GUARDAR EN CATÁLOGO"

**Nota**: Los productos se guardan en el localStorage del navegador. Para cambios permanentes, edita directamente el array `products` en el archivo `index.html` (líneas 182-185).
