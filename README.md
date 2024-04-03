# Selectores avanzados

Nos han pedido aplicar algunos estilos a esta galería de gatitos.
La cosa es que **NO** podemos modificar el fichero index.html, y tendremos que usar selectores avanzados para conseguir nuestro propositos. Solamente puedes modificar el fichero styles.css, agregando nuevas reglas CSS

[DEMO del aspecto final aproximado](https://github.com/omiras/selectores-avanzados)

## Ejercicio 1

Crea DOS reglas CSS nuevas usando un selector de descendencia.

1. La imagen del gato blanco dentro del header debe tener un width de 100px.
2. Al resto de imagenes de la galería tenemos que aplicarles los siguientes estilos CSS

```
    width: 100%;
    max-width: 350px;
    height: 300px;
    object-fit: cover;
    border-radius: 10px;

```

BONUS: Existen al menos otro selector avanzado que puedes aplicar para conseguir seleccionar estos gatos. ¿Cuál es?

## Ejercicio 2
Aplica el siguiente filtro a los gatos de la galería pares.
```
filter: grayscale(100%);
```

## Ejercicio 3
Crea dos reglas más.

Aplica un borde de color #ff9b4 al primer gato de la galería, y un borde de color #00964b al último gato de la galería.

## BONUS

¿Cómo podríamos crear una regla que usando el [selector por atributo](https://www.w3schools.com/css/css_attribute_selectors.asp) nos ocultará el gato número 7? Puedes aplicar por ejemplo la propiedad CSS: `display: none`
