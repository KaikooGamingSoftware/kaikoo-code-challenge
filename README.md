# kaikoo-code-challenge

## Build Setup

```bash
# Instalar dependencias
$ npm install

# Arrancar proyecto en local en localhost:3000
$ npm run dev
```

## Code Challenge
En este Challenge (no será largo, lo prometemos), usarás **Nuxt.js** para maquetar el diseño de una página a partir de un diseño en Figma. El challenge será replicar una de las páginas de nuestra plataforma: https://lol.kaikoo.pro/champions (sin side-bar ni nav-bar, solo el contenido).

### Primer paso
Realiza una petición GET al entrar a la página para recibir un JSON con los datos actualizados de todos los campeones de League of Legends. El endpoint es:
```bash
$ GET https://back.kaikoo.pro:8888/api/champions
```

### Segundo paso
Itera sobre la respuesta y pintar una Card para cada campeón con los datos de su JSON que aparecen en el figma:
https://www.figma.com/file/A7B9BcUtvY8WvjQ1bYZu59/Champions?node-id=60%3A2112&t=HAWakOMb81HhMzfD-0

Añade también el efecto de hover que aparece en el figma

![image](https://user-images.githubusercontent.com/78962636/210406701-0f55e966-5ae0-4d28-8442-c84db07ab07b.png)

### Tercer paso
Añade una barra de filtrado para los campeones. Se puede filtrar por nombre, por posición y por dificultad. Los filtros tienen que aplicarse en tiempo real y pueden ser borrados en cualquier momento

### Cuarto paso (OPCIONAL)
Añade una funcionalidad para guardar campeones en favoritos. No te preocupes por el diseño, añade un botón en algún sitio dentro de la card para añadir/eliminar campeones de Favoritos. Añade también un filtro que muestre solo los campeones guardados en favoritos.


## Instrucciones
  · **NO QUEREMOS ROBARTE MUCHO TIEMPO.** No hace falta hacer over-engineering, haz simplemente lo que te pedimos de la mejor forma que sepas, del mismo modo que lo harías en tu día a día en nuestra empresa.

  · No te preocupes de diseño responsive ni de dispositivos móviles

  · No hace falta hacer tests

## Instrucciones para compartir tu solución
Clona nuestro repositorio y súbelo a tu github como repositorio privado. Invita a nuestro CTO [Jose Pina](https://github.com/josepinaKaikoo) y a nuestro Frontend [Alejandro Maldonado](https://github.com/amaldonadokaikoo). De esta manera, podremos revisar tu código y tenerlo a mano para el siguiente paso: una entrevista personal 👻

