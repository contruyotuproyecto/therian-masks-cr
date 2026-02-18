# 🎭 Therian Masks CR

Sitio web de tienda en línea para **Therian Masks CR**, negocio costarricense de máscaras Therian artesanales. Envíos a todo Costa Rica por Correos de CR.

🌐 **Sitio en vivo:** [contruyotuproyecto.github.io/therian-masks-cr](https://contruyotuproyecto.github.io/therian-masks-cr/)

---

## 📁 Estructura del proyecto

```
therian-masks-cr/
├── index.html              # Tienda principal
├── historia.html           # Artículo: ¿Qué es un Therian?
├── productos.json          # Catálogo de productos (editable)
├── logo.png                # Logo del negocio
├── therian_historia.jpg    # Imagen para la página de historia
└── imagenes/
    ├── lobo-lunar.jpg
    ├── zorro-otonal.jpg
    ├── dragon-mistico.jpg
    ├── gato-nocturno.jpg
    ├── ciervo-sagrado.jpg
    └── buho-sabio.jpg
```

---

## ✨ Funcionalidades

- 🛒 Carrito de compras con cantidades y eliminación
- 📱 Diseño responsive (móvil y escritorio)
- 🔍 Filtros por categoría de máscara
- ❤️ Lista de favoritos (wishlist)
- 💬 Envío de pedido directo por **WhatsApp**
- 🔔 Notificación pop-out al agregar productos
- 📖 Página blog sobre el origen de los Therians
- 🗂️ Modal de detalle por producto

---

## 🛍️ Cómo funciona el proceso de venta

1. El cliente agrega máscaras al carrito
2. Envía el pedido por **WhatsApp** con su nombre y ubicación
3. Tiene **2 horas** para confirmar el pago
4. Pago por **SINPE Móvil al 6007-2890** (Paulo Jiménez) o depósito bancario
5. Se coordina el envío por **Correos de Costa Rica**

---

## 📦 Cómo agregar o editar productos

Editá el archivo `productos.json`. Cada producto tiene esta estructura:

```json
{
  "nombre": "Nombre del producto",
  "descripcion": "Descripción corta.",
  "precio": 25000,
  "stock": 10,
  "foto": "imagenes/nombre-archivo.jpg",
  "categoria": "Lobo",
  "destacado": true
}
```

| Campo | Descripción |
|-------|-------------|
| `nombre` | Nombre visible en la tienda |
| `descripcion` | Texto corto de la card |
| `precio` | En colones costarricenses (sin símbolos) |
| `stock` | Unidades disponibles. `0` = aparece como Agotado |
| `foto` | Ruta relativa a la imagen (dentro de `imagenes/`) |
| `categoria` | Lobo, Zorro, Dragón, Gato, Ciervo, Búho |
| `destacado` | `true` muestra badge "⭐ Destacado", `false` no |

---

## 🖼️ Cómo agregar imágenes nuevas

1. Guardá la imagen en la carpeta `imagenes/`
2. Usá nombres en **minúscula y sin espacios** (ej: `mascara-nueva.jpg`)
3. Agregá el producto en `productos.json` con `"foto": "imagenes/mascara-nueva.jpg"`
4. Subí los cambios a GitHub — el sitio se actualiza automáticamente

---

## 🚀 Tecnologías

- HTML5 + CSS3 vanilla
- JavaScript vanilla (sin frameworks)
- Google Fonts: Cinzel + Nunito
- Hospedado en **GitHub Pages** (gratis)

---

## 📞 Contacto

**SINPE Móvil:**
**Nombre:** Paulo Jiménez  
**Envíos:** Correos de Costa Rica 🇨🇷
