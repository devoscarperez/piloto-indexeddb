PILOTO INDEXEDDB / PWA
1. Descomprimir ZIP.
2. Servir carpeta por HTTPS (recomendado) o localhost. Ejemplo en computador: python -m http.server 8000 y abrir http://localhost:8000.
3. En Android, acceder mediante URL HTTPS (por ejemplo, hosting estático). No abrir index.html directamente como archivo para prueba offline.
4. Cargar 2.000 productos, buscar código 7800000000001, registrar ticket, revisar tickets.
5. Probar rollback y confirmar que no aumentan los conteos.
6. Esperar que se instale Service Worker, cerrar, activar modo avión y reabrir.
7. No borrar datos del navegador. No hay sincronización real con Google en este piloto.
