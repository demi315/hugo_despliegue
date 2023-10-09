+++ 
title = 'Markdown Cheatsheet'
date = 2023-09-19T10:56:03+02:00
weight = 100
+++
### Different ways to highlight text
 + *Italics*
 + **Bold**
 + ***A* little bit _weird_** _mix_
 + ~~Line above it~~

 ```md
 ### Different ways to highlight text
 + *Italics*
 + **Bold**
 + ***A* little bit _weird_** _mix_
 + ~~Line above it~~
 ```

### Ways to create [links]
 1. Link to [Google](https://www.google.com)
 2. Link to [Google](https://www.google.com "This link will take you to Google"), but when you hover your mouse avobe the link a text will show up  
 3. Links with references:
    * Text reference to [Reddit][reddit]
    * Numerical reference to [Reddit][1]
    * The text itself its the reference to the link [Twitter]
 4. pictures ![gato](/gato.jpg "kitty")

[reddit]: https://www.reddit.com
[1]: https://www.reddit.com
[Twitter]: https://www.twitter.com

 ```md
 ### Ways to create [links]
 1. Link to [Google](https://www.google.com)
 2. Link to [Google](https://www.google.com "This link will take you to Google"), but when you hover your mouse avobe the link a text will show up  
 3. Links with references:
    * Text reference to [Reddit][reddit]
    * Numerical reference to [Reddit][1]
    * The text itself its the reference to the link [Twitter]
 4. pictures ![gato](/gato.jpg "kitty")

[reddit]: https://www.reddit.com
[1]: https://www.reddit.com
[Twitter]: https://www.twitter.com
 ```

### Writting code
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

### Footnotes
Did you know that 39% of Spaniards says that blue is their favourite colour?[^1]

 ```md
 ### Footnotes
Did you know that 39% of Spaniards says that blue is their favourite colour?[^1]
 [^1]: https://ailmadrid.com/blog/costumbres-espanolas-colores/ 
 ```

### Charts
Left | Centred | Right
---|:---:|---:
each|column|is
centred|in|a
different|way|

 ```md
 ### Charts
Left | Centred | Right
---|:---:|---:
each|column|is
centred|in|a
different|way|
 ```

### Blockquotes
> This is a blockquote.
> Still the same line, even though i wrote it in another one 

I "cut" the block
> This is another block

 ```md
 ### Blockquotes
> This is a blockquote.
> Still the same line, even though i wrote it in another one 

I "cut" the block
> This is another block
 ```


<!---### HTML
<ol>
    <li>Puedes añadir código html junto al código de markdown</li>
</ol>--->

### Line brakes and horizontal lines
In order to make a line break in markdown you may put two spaces at the end of the line.  
And it is still the same paragraph.

But if you hit enter twice it's another paragraph.

---
Three hyphen make a horizontal line

***
Same as three asterisks

___
Or three low bars 

 ```md
 ### Line brakes and horizontal lines
In order to make a line break in markdown you may put two spaces at the end of the line.  
And it is still the same paragraph.

But if you hit enter twice it's another paragraph.

---
Three hyphen make a horizontal line

***
Same as three asterisks

___
Or three low bars 
 ```

### Youtube videos
[![Esportmaniacos 1837](http://img.youtube.com/vi/OZ-6ThPL3lw/0.jpg)](http://www.youtube.com/watch?v=OZ-6ThPL3lw)

 ```md
 [![Esportmaniacos 1837](http://img.youtube.com/vi/OZ-6ThPL3lw/0.jpg)](http://www.youtube.com/watch?v=OZ-6ThPL3lw)
 ```

<a href="http://www.youtube.com/watch?feature=player_embedded&v=OZ-6ThPL3lw
" target="_blank"><img src="http://img.youtube.com/vi/OZ-6ThPL3lw/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


[^1]: https://ailmadrid.com/blog/costumbres-espanolas-colores/ 