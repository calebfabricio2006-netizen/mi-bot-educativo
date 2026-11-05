# AI Crypto Lab V1.0 — iPad

Este proyecto es un prototipo educativo de paper trading. Utiliza precios sintéticos generados en el navegador. No descarga cotizaciones reales, no se conecta a exchanges, no ejecuta órdenes y no puede generar ingresos.

## Archivos
- `index.html`: panel y simulador.
- `manifest.webmanifest`: configuración de la aplicación web instalable.
- `sw.js`: caché offline para cuando se aloje mediante HTTPS.

## Probarlo
1. Descomprime el ZIP en Archivos.
2. Abre `index.html` en Safari o en un navegador compatible para probar la demo.
3. Pulsa **Iniciar simulación**. Los precios ficticios avanzan mientras la página está abierta.

## Instalar como app en iPad
Para que Safari permita “Añadir a pantalla de inicio” como PWA, primero hay que publicar estos archivos en un hosting HTTPS. Después:
1. Abre la dirección HTTPS en Safari.
2. Pulsa Compartir.
3. Selecciona “Añadir a pantalla de inicio”.

## Limitaciones importantes
- Esta versión no funciona 24/7 si cierras la pestaña o el navegador.
- La estrategia es una regla didáctica de cruce de medias, no una IA predictiva.
- Los créditos son ficticios, no euros.
- No añadas claves API ni datos bancarios. Mantendremos esta primera versión desconectada de dinero real.
