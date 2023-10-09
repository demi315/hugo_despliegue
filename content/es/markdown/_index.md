+++ 
title = 'Markdown Cheatsheet'
date = 2023-09-19T10:56:03+02:00
weight = 100
+++
### Distintas formas de resaltar el texto
 + *Cursiva*
 + **Negrita**
 + ***Una* mezcla un _poco_** _rara_
 + ~~Tachado~~

 ```md
 ### Distintas formas de resaltar el texto
  + *Cursiva*
  + **Negrita**
  + ***Una* mezcla un _poco_** _rara_
  + ~~Tachado~~
 ```

### Formas de hacer [links]
 1. Link a [Google](https://www.google.com)
 2. Link a [Google](https://www.google.com "Este enlace te llevará a Google"), pero cuando pasas por encima el ratón te muestra un texto  
 3. Links con referencias:
    * Referencia textual a [Reddit][reddit]
    * Referencia numérica a [Reddit][1]
    * El propio texto del likn es la referencia a [Twitter]
 4. Imágenes ![gato](/gato.jpg "gatito")

[reddit]: https://www.reddit.com
[1]: https://www.reddit.com
[Twitter]: https://www.twitter.com

 ```md
 ### Formas de hacer [links]
  1. Link a [Google](https://www.google.com)
  2. Link a [Google](https://www.google.com "Este enlace te llevará a Google"), pero cuando pasas por encima el ratón te muestra un texto  
  3. Links con referencias:
    * Referencia textual a [Reddit][reddit]
    * Referencia numérica a [Reddit][1]
    * El propio texto del likn es la referencia a [Twitter]
  4. Imágenes ![gato](/gato.jpg "gatito")

 [reddit]: https://www.reddit.com
 [1]: https://www.reddit.com
 [Twitter]: https://www.twitter.com
 ```

### Escribir código
```c++
    //en la primera línea, después de indicar que es un bloque de código escribe el lenguaje
    List<int> naturales;
    rellenarNaturales(naturales);
    for(int i : naturales)
        cout << i << endl;
```

```
    ```c++
    //en la primera línea, después de indicar que es un bloque de código escribe el lenguaje
    List<int> naturales;
    rellenarNaturales(naturales);
    for(int i : naturales)
        cout << i << endl;
    ```
```

### Notas de pie
¿Sabías que el 39% de los españoles afirma que su color favorito es el azul?[^1]

 ```md
 ### Notas de pie
 ¿Sabías que el 39% de los españoles afirma que su color favorito es el azul?[^1]
 [^1]: https://ailmadrid.com/blog/costumbres-espanolas-colores/ 
 ```

### Tablas
Izquierda | Centrado | Derecha
---|:---:|---:
cada|columna|está
centrada|de|una
forma|distinta|

 ```md
 ### Tablas
Izquierda | Centrado | Derecha
---|:---:|---:
cada|columna|está
centrada|de|una
forma|distinta|
 ```

### Citas en bloque
> Esto es una cita en bloque.
> Sigue siendo la misma línea aunque la haya escrito en otra  

Corto el bloque
> Esto es otro bloque

 ```md
 ### Citas en bloque
> Esto es una cita en bloque.
> Sigue siendo la misma línea aunque la haya escrito en otra  

Corto el bloque
> Esto es otro bloque

 ```


<!---### HTML
<ol>
    <li>Puedes añadir código html junto al código de markdown</li>
</ol>--->

### Saltos de línea y líneas horizontales
Para hacer un salto de línea en markdown debes dejar dos espacios al final de la línea.  
Y así sigue en el mismo párrafo.

Pero si haces un doble salto de línea creas un nuevo párrafo.

---
Tres guiones hacen una línea horizontal

***
De la misma forma que tres asteriscos

___
O tres barra-bajas

 ```md
 ### Saltos de línea y líneas horizontales
Para hacer un salto de línea en markdown debes dejar dos espacios al final de la línea.  
Y así sigue en el mismo párrafo.

Pero si haces un doble salto de línea creas un nuevo párrafo.

---
Tres guiones hacen una línea horizontal

***
De la misma forma que tres asteriscos

___
O tres barra-bajas
 ```

### Vídeos de YouTube
[![Esportmaniacos 1837](http://img.youtube.com/vi/OZ-6ThPL3lw/0.jpg)](http://www.youtube.com/watch?v=OZ-6ThPL3lw)

 ```md
 [![Esportmaniacos 1837](http://img.youtube.com/vi/OZ-6ThPL3lw/0.jpg)](http://www.youtube.com/watch?v=OZ-6ThPL3lw)
 ```

<a href="http://www.youtube.com/watch?feature=player_embedded&v=OZ-6ThPL3lw
" target="_blank"><img src="http://img.youtube.com/vi/OZ-6ThPL3lw/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


[^1]: https://ailmadrid.com/blog/costumbres-espanolas-colores/ 