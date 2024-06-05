Forked from codigoconjuan/_globales.scss

@use 'variables' as v;

html {
    font-size: 62.5%;
    box-sizing: border-box;
    scroll-padding-top: 0rem;
}
*, 
*:before,
*:after {
    box-sizing: inherit;
}
body {
    font-family: v.$fuente_principal;
    font-optical-sizing: auto;
    font-style: normal;
    color: v.$negro;
    font-size: 2rem;
}
p {
    color: v.$negro;
    line-height: 1.5;
}
.contenedor {
    width: 95%;
    max-width: 120rem;
    margin: 0 auto;
}
a {
    text-decoration: none;
}
h1, h2, h3 {
    margin: 0 0 5rem 0;
    font-weight: 900;
}
h1 {
    font-size: 4rem;
}
h2 {
    font-size: 4.6rem;
}
h3 {
    font-size: 6rem;
    text-align: center;
}
img {
    max-width: 100%;
    width: 100%;
    height: auto;
    display: block;
}
body > section {
    padding: 10rem 0
}
