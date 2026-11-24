# Holy Pocket

App web de control de gastos pensada para el celular. Registra ingresos y gastos, mira en qué se va tu dinero con un cilindro líquido y planea tu mes con presupuestos y gastos fijos.

## Funciones

- Ingresos, gastos y gastos fijos que se repiten cada mes
- Navegación por meses y edición de movimientos
- Cilindro líquido por categorías y Radar de ritmo del mes
- Costo de cada gasto en horas de tu trabajo
- Presupuesto por día, semana, quincena, mes o año, y límite por categoría
- Pesos colombianos y dólares (USD)
- Idiomas: español, inglés, francés, portugués y coreano
- Modo claro, oscuro o del dispositivo, y barra inferior con efecto liquid glass
- Bloqueo con PIN y respaldo copiando y pegando tus datos
- Perfil con foto desde cámara o galería

Todos los datos se guardan solo en tu dispositivo (`localStorage`). No hay servidor ni cuentas.

## Cómo usarla

No necesita instalación: abre `index.html` en el navegador.

### Publicarla gratis con GitHub Pages

1. Sube este proyecto a un repositorio de GitHub.
2. Ve a **Settings > Pages**.
3. En **Source** elige la rama `main` y la carpeta `/ (root)`.
4. Guarda. En unos minutos tendrás un enlace público.

## Donaciones

El botón de PayPal ya apunta a `https://paypal.me/morunh0ly`. Para cambiarlo o agregar más, busca en `index.html` la constante `DONATE` y pega tus enlaces (Ko-fi, PayPal.me, GitHub Sponsors, etc.):

```js
const DONATE=[{n:"Ko-fi",u:""},{n:"PayPal",u:"https://paypal.me/morunh0ly"},{n:"GitHub Sponsors",u:""}];
```

Solo se muestran los que tengan enlace. Los enlaces aparecen en **Perfil > Apoyar el proyecto**.
Si usas GitHub Sponsors, completa también `.github/FUNDING.yml` para que aparezca el botón "Sponsor" en el repositorio.

## Estado y próximos pasos

Es un prototipo web. Pendiente: inicio de sesión (Google y teléfono), respaldo en la nube y versión nativa para Google Play y App Store.

## Licencia

MIT. Consulta el archivo `LICENSE`.
