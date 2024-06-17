# Documentación del Proyecto

- [Notas CSS]

1. box-sizing-border-box

`https://www.paulirish.com/2012/box-sizing-border-box-ftw/`

/_ apply a natural box layout model to all elements, but allowing components to change _/
html {
box-sizing: border-box;
}
_, _:before, \*:after {
box-sizing: inherit;
}

2. css para rem

```css
html {
  font-size: 62.5%;
}

body {
  font-size: 16px; /* 1 rem = 10px */
}
```

4. Normalize

   `https://necolas.github.io/normalize.css/`

5. media queries tamaños

/_ Teléfonos en orientación vertical _/
@media (max-width: 320px) {
/_ Estilos aquí _/
}

/_ Teléfonos móviles _/
@media (max-width: 480px) {
/_ Estilos aquí _/
}

/_ Dispositivos móviles y tablets pequeñas _/
@media (max-width: 600px) {
/_ Estilos aquí _/
}

/_ Tablets en orientación vertical _/
@media (max-width: 768px) {
/_ Estilos aquí _/
}

/_ Tablets en orientación horizontal y dispositivos pequeños _/
@media (max-width: 992px) {
/_ Estilos aquí _/
}

/_ Dispositivos de escritorio y laptops pequeñas _/
@media (max-width: 1200px) {
/_ Estilos aquí _/
}

/_ Pantallas de escritorio grandes _/
@media (min-width: 1200px) {
/_ Estilos aquí _/
}
