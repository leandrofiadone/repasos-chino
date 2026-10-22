# Repasos de chino

Dos sitios estáticos para practicar mandarín, cada uno con su propio proyecto en Vercel:

- `arcade/` → **Chinardo Arcade**: Tonos con el dedo, Ninja de sonidos, Corredor de frases y Café en Pekín.
- `repaso/` → **Repaso**: todo lo de las lecciones 1 a 3, tema por tema, con examen final.

Cada carpeta tiene un `index.html` autocontenido (estilos, datos y código adentro), más el manifest y los íconos para instalarlo en el celular. No hay build: Vercel sirve los archivos tal cual, y cada proyecto solo se vuelve a publicar cuando cambia su carpeta.

El progreso se guarda en el navegador de cada dispositivo (localStorage).
