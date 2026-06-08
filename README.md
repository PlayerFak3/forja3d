# 🔧 Forja 3D

> Calculadora de costos para impresión 3D, pensada para el mercado argentino.

Aplicación de escritorio gratuita para Windows que te ayuda a calcular el costo
real de tus piezas impresas, armar presupuestos profesionales en PDF y llevar
el registro de tus trabajos.

[![Descargar última versión](https://img.shields.io/github/v/release/PlayerFak3/forja3d?label=Descargar&style=for-the-badge&color=14b8a6)](https://github.com/PlayerFak3/forja3d/releases/latest/download/Forja3D.exe)
[![Invitame un café](https://img.shields.io/badge/☕-Invitame%20un%20café-orange?style=for-the-badge)](https://cafecito.app/forja3d)

---

## ✨ ¿Qué hace?

- **Calcula el costo real** de cada pieza: material, electricidad, desgaste de máquina, insumos, margen de error.
- **Arma presupuestos en PDF** profesionales con tu marca, logo y términos personalizados.
- **Lleva el registro** de todos tus trabajos con estados (Presupuestado, En proceso, Aprobado, Entregado).
- **Avisa los vencimientos** próximos a la fecha de entrega.
- **Soporta MercadoLibre**: calcula el precio incluyendo la comisión del 16%.
- **Plantillas reusables**: guardá modelos de trabajos frecuentes para no cargar todo de cero cada vez.
- **Se actualiza sola**: cuando saco una versión nueva, la app se actualiza automáticamente.

Descarga

Bajá el `.exe` más reciente desde aquí:

**[Descargar Forja3D.exe](https://github.com/PlayerFak3/forja3d/releases/latest/download/Forja3D.exe)**

> Es un único archivo ejecutable, no requiere instalación. Hacé doble click y listo.

### Windows Defender puede mostrar advertencia

Como es una app nueva sin certificado de firma de código (que cuesta cientos de dólares al año), algunos antivirus muestran advertencia la primera vez. Si pasa, hacé click en "Más información" → "Ejecutar de todas formas". Es seguro, el código fuente está abierto en este repo para que cualquiera lo revise.

Primer uso

1. Abrí la app y seguí el tour de bienvenida.
2. Configurá los datos de tu impresora (precio del filamento, kWh, consumo, etc.).
3. Cargá los datos de tu negocio (nombre, contacto, logo, términos).
4. ¡Cotizá! Cargás piezas, ves el costo en vivo y generás el PDF.

Funcionalidades destacadas

Cálculo de costos
- Múltiples piezas por trabajo, cada una con horas, gramos, cantidad e insumos.
- Margen de ganancia ajustable y comparador de precios (x3 / x4 / x5).
- Soporte multimoneda (ARS, USD, EUR).
- Redondeo de precio final opcional.

Presupuestos PDF
- Numeración automática (N° 0001, 0002, ...).
- 3 estilos visuales: Clásico, Moderno o Minimalista.
- Términos y condiciones personalizables.
- Cualquier cantidad de piezas (paginación automática).

Gestión de trabajos
- Estados con colores: Presupuestado, En proceso, Aprobado, Entregado, Cancelado.
- Búsqueda por nombre.
- Filtro por estado.
- Plantillas reusables.
- Importar / exportar JSON para backup.
- Historial completo de presupuestos generados.

Para desarrolladores

Si querés correr la app desde el código:

```bash
git clone https://github.com/PlayerFak3/forja3d.git
cd forja3d
pip install customtkinter pillow reportlab
python app.py
```

Para empaquetar tu propio `.exe`:

```bash
python -m PyInstaller --clean forja3d.spec
```

Apoyar el proyecto

Forja 3D es **gratis** y se mantiene con el aporte voluntario de quienes la encuentran útil. Si te sirve para tu trabajo y querés apoyarme, podés invitarme un cafecito:

**[cafecito.app/forja3d](https://cafecito.app/forja3d)**

Cualquier aporte es bienvenido y me ayuda a seguir mejorando la app.

Reportar problemas

Si encontrás un bug, abrí un issue en este mismo repo con:
- Versión que estás usando (aparece abajo a la izquierda en la app).
- Qué hacías cuando pasó.
- El archivo `forja3d.log` (lo abrís desde el botón "?" → "Abrir carpeta de logs").

Licencia

Forja 3D es software libre. Podés usarlo, modificarlo y compartirlo. Más detalles en el archivo LICENSE.

Autor

Desarrollado por **E.S.** para la comunidad maker argentina.
