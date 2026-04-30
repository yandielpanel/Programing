# SMM Boost Studio

Sitio web funcional para una agencia de **Marketing SMM / Social Media Marketing**.

Incluye:

- Landing page profesional.
- Servicios SMM.
- Paquetes de precios editables.
- Formulario de cotización.
- Resumen automático.
- Botón para enviar pedido por WhatsApp.
- Modo claro / oscuro.
- Diseño responsive para móvil y PC.
- GitHub Actions para publicar en GitHub Pages.

## Probar localmente

Abre `index.html` directamente en tu navegador.

También puedes usar:

```bash
npm install
npm run dev
```

## Personalizar negocio

En `script.js`, cambia:

```js
const business = {
  name: "SMM Boost Studio",
  whatsappNumber: "10000000000",
  currency: "USD"
};
```

Pon tu WhatsApp en formato internacional, sin `+`, espacios ni símbolos.

Ejemplo:

```js
whatsappNumber: "17861234567"
```

## Editar paquetes

En `script.js`, busca:

```js
const packages = [...]
```

Ahí puedes cambiar nombres, precios y beneficios.

## Publicar en GitHub Pages

Este proyecto ya trae GitHub Actions listo.

Cuando lo subas a GitHub:

1. Entra al repo.
2. Ve a **Settings**.
3. Entra en **Pages**.
4. En **Build and deployment**, selecciona **GitHub Actions**.
5. Haz push a `main`.
6. GitHub publicará la web automáticamente.

## Próximas mejoras

- Backend para guardar pedidos.
- Panel admin.
- Panel de clientes.
- Pagos online.
- Login.
- Base de datos.
- Tickets.
- Integración real con WhatsApp Business API.
