# Version del curso
Version actual: 1.2.2


# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- letra *italica* de la primera forma
- letra _italica_ de la segunda forma
- formato **bold o strong** de la primera forma.
- formato __bold o strong__ de la primera forma.
- formato ~~tachado~~, formato normal.
- aqui podemos usar *formato italico*, pero también **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
<a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)

- [Esto es un link al index](index.html)

# Imagenes
![Logo Github](https://image.flaticon.com/icons/png/512/25/25231.png)

# Code Snippets
Codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
Codigo en JavaScript
```Javascript
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
| Maxi   | Burgos | 3423463 |
| Tomas | Tompson | 232342 |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita.

# Lineas Divisorias
Esto es un texto que sera dividido por guiones medios.

---
Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajos

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista







