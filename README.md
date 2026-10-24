# Repasos de chino

Sitios estáticos para practicar mandarín, cada uno con su propio proyecto en Vercel:

- `arcade/` → **Arcade**: Tonos con el dedo, Ninja de sonidos, Corredor de frases y Café en Pekín.
- `repaso/` → **Repaso**: todo lo de las lecciones 1 a 6, tema por tema, con examen final.
- `aventura/` → **El secreto del té del mono**: una aventura de señalar y tocar, al estilo de los juegos de piratas de los noventa. Tres pruebas, duelos de réplicas y un capitán fantasma, todo en chino de las lecciones 1 a 6.
- `horapico/` → **Hora pico**: un café de Pekín con lo de las lecciones 1 a 6: saludos según la hora, gracias, perdón y chau, grupos, turistas, cuentas, vueltos y filósofos chinos como clientes. Tiene hora pico, turno noche, logros y galletita de la fortuna.

Cada carpeta tiene un `index.html` autocontenido (estilos, datos y código adentro), más el manifest y los íconos para instalarlo en el celular. No hay build: Vercel sirve los archivos tal cual, y cada proyecto solo se vuelve a publicar cuando cambia su carpeta.

El progreso se guarda en el navegador de cada dispositivo (localStorage).

Cada sitio también funciona como artifact de Claude; ahí el progreso se guarda en la cuenta.
