# 🧾 Sistema de Facturación para Ventas de Bolsas

Este proyecto es una aplicación web desarrollada en **HTML, CSS y JavaScript** puro, diseñada para gestionar la venta de bolsas en distintas presentaciones. Permite facturar productos, calcular precios por unidad o por millar, generar recibos imprimibles, y mantener un historial de facturas.

## 🚀 Funcionalidades

- ✅ Selección de tipo y subtipo de bolsas.
- ✅ Cálculo automático del precio según:
  - Modo de venta (unidad o millar).
  - Cantidad real por paquete (ej. 10 o 50 unidades por paquete).
- ✅ Tabla de productos añadidos con subtotales.
- ✅ Generación de recibo para impresión.
- ✅ Registro automático en un historial de facturas.
- ✅ Posibilidad de exportar el historial en formato Excel.

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3 (estilizado básico)
- JavaScript (sin frameworks, totalmente Vanilla JS)
- `localStorage` para almacenamiento de historial
- Exportación a Excel con [`xlsx`](https://github.com/SheetJS/sheetjs) 

## 📦 Estructura del proyecto

├── index.html
├── script.js
├── style.css 
└── README.md


## 📐 Lógica de precios

- Cada tipo y subtipo de bolsa tiene un precio por millar y por unidad.
- Las bolsas pueden tener distintas cantidades por paquete:
  - Ejemplo: bolsas de kilo → 10 unidades por paquete.
  - Ejemplo: bolsas 5x8 → 50 unidades por paquete.
- El sistema ajusta el precio unitario dependiendo del tipo de bolsa seleccionado.

## 🖨️ Recibo e impresión

Una vez agregados los productos, puedes generar un recibo visual listo para imprimir con todos los detalles de la compra.

## 📊 Historial

Cada factura queda registrada con:
- ID único
- Nombre del cliente
- Fecha y hora
- Total de la factura
- Estado (pagada o no pagada)
- Acciones para marcar como pagado, eliminar o exportar

## 📤 Exportación

El historial de facturas puede exportarse como archivo Excel para llevar registros contables.

## 📷 Capturas de pantalla (opcional)

Puedes añadir capturas de cómo se ve la app, por ejemplo:

- Selección de productos
- Recibo generado
- Tabla de historial

## 🧠 Ideas futuras

- Conexión con base de datos (Firebase, Supabase, etc.)
- Autenticación de usuarios
- Interfaz responsive con mejor diseño visual (usando Bootstrap o Tailwind)

## 🧑‍💻 Autor

**Oscar Gil**  
Desarrollador web y estudiante de Ingeniería de Sistemas y Computación.  
Contacto: [GitHub @Ogil11](https://github.com/Ogil11)

---

