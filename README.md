# EcoPuntos IIEE · MVP 2

Prototipo web estático con acceso único para administrador y estudiantes, registro de cuentas, asignación y canje de puntos, gráfica de acopio por material y reinicio de saldos.

## Probarlo

Sirve esta carpeta con cualquier servidor HTTP local y abre `index.html`. Para usarlo en iPad, publica **todos** los archivos de esta carpeta en un alojamiento estático con HTTPS y abre la URL en Safari. El manifiesto, los iconos y el service worker permiten añadir la página a la pantalla de inicio y cargarla sin conexión después de la primera visita.

## Límite del prototipo

Las cuentas, contraseñas, saldos y movimientos se guardan en `localStorage` del navegador. No se sincronizan entre dispositivos ni navegadores, y cualquiera con acceso al navegador o al código de la página puede ver las credenciales. Por ello, este prototipo solo debe usarse con datos de prueba. Para operar con alumnos reales se necesita un servidor con autenticación, base de datos y controles de acceso.

La cuenta inicial usa un nombre genérico para no publicar datos personales de un estudiante.
Los botones de la pantalla de acceso completan las credenciales de demostración.
