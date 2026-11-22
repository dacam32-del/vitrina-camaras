# 📷 Vitrina de Cámaras Fotográficas

Vitrina virtual de la colección de cámaras fotográficas de David Eduardo: compactas digitales, cámaras de rollo de 35 mm y otras que se vayan sumando.

Cada ficha incluye fotos, marca, modelo, tipo, año, época, especificaciones (lente, sensor o formato, zoom, pantalla o visor, alimentación), una reseña de la tecnología y de lo que significó en su época, el estado y una tasación en pesos chilenos (CLP). Los precios se presentan separados en **vendido**, **anunciado** y **estimado**, con un rango mínimo–máximo y un **sugerido de venta en Chile**.

**Funciones de la vitrina:**
- Filtros por marca, tipo (digital, rollo de 35 mm, etc.), época o década, estado y rango de precio.
- Orden por defecto: de más cara a más barata.
- Calculadora / carrito flotante para ir sumando piezas (cantidades, total en CLP, se guarda en el navegador).
- Música de fondo: "Lobby Time" de Kevin MacLeod (incompetech.com), licencia CC BY 4.0.

**Totales:** 3 fichas · 3 unidades · CAM-001 Kodak EasyShare C433 $10.000 – $20.000 (sugerido $14.000) · CAM-002 Highs HC35 $12.000 – $25.000 (sugerido $18.000; rango fijado por el dueño según el estado) · CAM-003 Canon PowerShot SX230 HS $50.000 – $90.000 (sugerido $65.000) · Valor total Chile: **$72.000 – $135.000**.

## 🛒 Tienda web
**[https://dacam32-del.github.io/vitrina-camaras/](https://dacam32-del.github.io/vitrina-camaras/)**

## Agregar una pieza
1. Copiar las fotos tal cual (sin recorte ni compresión) a `img/` como `CAM-00N.jpg`, `CAM-00N-2.jpg`, …
2. Agregar un objeto al arreglo `D` en `index.html`, copiando la estructura de `CAM-001` (`pmin` / `pmax` / `p_sugerido` en CLP numéricos para filtros y carrito).
3. Actualizar los totales del encabezado y de este README.
