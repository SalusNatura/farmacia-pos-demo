# Farmacia POS — demo

Demostración pública de Farmacia POS: la aplicación completa (caja, gestión, químico farmacéutico,
privacidad, informes) con datos de ejemplo, más la tienda en internet de la farmacia.

- **Aplicación:** https://salusnatura.github.io/farmacia-pos-demo/
- **Tienda en internet:** https://salusnatura.github.io/farmacia-pos-demo/#tienda
- **Otros roles:** añade `?rol=vendedor` o `?rol=quimico` a la dirección.
- **Descuentos en caja:** como cajero (`?rol=vendedor`), bajar un precio pide la clave de Gerencia. En la demo es `demo2026`.
- **Meta diaria de ventas:** la caja muestra un semáforo con lo vendido hoy frente a la meta ($900.000 de lunes a viernes; $600.000 sábados, domingos y festivos). Gerencia lo ajusta en Configuración → Meta de ventas.

Notas:
- Todos los productos, precios, ventas y la farmacia son **de ejemplo**.
- **No se cobra nada.** El pago de la tienda se simula.
- Los datos viven en el navegador: al recargar vuelven a los datos de ejemplo.
- Lo que llama al servidor (Mercado Pago, SII, publicar la tienda) no funciona aquí.

## Derechos

Todos los derechos reservados. © 2026 VALTRIX SPA. El código, el diseño y los textos de esta
demostración no pueden copiarse, reutilizarse, modificarse ni distribuirse sin autorización escrita
de su titular.
