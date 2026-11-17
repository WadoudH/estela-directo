# estela-directo

Página que abre quien recibe un enlace de ubicación en directo de la app Estela.

No contiene datos de nadie: es solo el visor. La ubicación llega cifrada (AES-GCM) y se descifra en el navegador con la clave que va en el enlace, después de `#`; esa parte nunca se envía a este servidor ni a ningún otro.

- Mapa: [Leaflet](https://leafletjs.com) 1.9.4 (incluido aquí, licencia BSD-2) con datos de © [OpenStreetMap](https://www.openstreetmap.org/copyright).
- Sin el enlace completo, la página no enseña nada.
