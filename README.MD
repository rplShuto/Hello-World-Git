# Formatos de Cabeceras

- # Cabecera H1
- ## Cabecera H2
- ### Cabecera H3
- #### Cabecera H4
- ##### Cabecera H5
- ###### Cabecera H6

# Formatos de Underline
- Underline 1
------------

- Underline 2
===========

# Formatos de Enfasís
- formato *italica* de la primera forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** primera forma.
- formato __bold o strong__ segunda forma.
- formato ~~tachado.~~


Un ejemplo de combibaciíon de estas opciones son: *formato italico* 
 y también **formato bold** y a la vez ~~formato tachado~~


 # Listas

 - Listas Ordenadas:
    1. Item
    2. Item
    3. Item

- Listas Desordenadas:
    - Item
    - Item
    - Item

# Formatos Links
- <a href="http://www.google.com">Esto es un link HTML</a>
- [Esto es un link en markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://media.jfrog.com/wp-content/uploads/2019/02/20131119/GitLab-250.png)

# Code Snippets
Codigo JSON
```JSON
[
    {
        "title": "apples",
        "count": [12000, 20000],
        "description": {"text": "....","sensitive":false}
    },
    {
        "title": "oranges",
        "count": [17500, null],
        "description": {"text": "....","sensitive":false}
    }
]
```

Codigo en Javascript
```JAVASCRIPT
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```

# Tablas
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi  | Burgos | 12345678 |
| Tomas | Tompson | 87654321 |