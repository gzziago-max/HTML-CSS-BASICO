# HTML-CSS-BASICO
1. Estructura del repositorio
Según las instrucciones del profesor, los ejercicios deben estar dentro de la carpeta UD2, cada uno en su propia carpeta.
UD2/
├── A1/
│   └── README.md
├── A2/
│   └── README.md
├── A3/
│   └── README.md
├── A4/
│   └── README.md
├── A5/
│   └── README.md
└── A6/
    └── README.md


2. Contenido de los ejercicios
A1. Verdadero o falso
1. Falso. HTML es un lenguaje de marcado, no de programación.
2. Verdadero. <br> no necesita cierre.
3. Falso. Las comillas no siempre son obligatorias, aunque se recomienda utilizarlas.
4. Falso. Los atributos se escriben en la etiqueta de apertura.
5. Verdadero. <title> aparece en la pestaña del navegador.
6. Verdadero. <strong> y <b> normalmente se ven igual, pero tienen distinto significado.
7. Falso. El contenido de <head> normalmente no se muestra en la página.
8. Falso. <hr> no necesita cierre.
9. Falso. Los comentarios HTML no aparecen en pantalla.
10. Falso. <span> no crea una línea nueva.
A2. Relacionar etiquetas
Etiqueta	Respuesta
<mark>	B
<del>	A
<sub>	E
<sup>	F
<small>	D
<em>	C
<ins>	G

A3. Corregir errores HTML
Primero revisamos las etiquetas y corregimos las que están mal cerradas. También añadimos la estructura necesaria.
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="utf-8">
    <meta name="author" content="Tu nombre">
    <title>Mi tienda de gadgets</title>
</head>
<body>
    <h1>Ofertas de otoño</h1>
    <p>Auriculares con <b>cancelación de ruido</b></p>
</body>
</html>


Explicación: Se ha cerrado correctamente el título, cambiado </h2> por </h1> y colocado </b> antes de </p>.
A4. Estilos rotos
Los errores estaban en la forma de escribir las propiedades CSS y en el cierre de una etiqueta.
<h1 style="color:red; font-size:40px;">
    Directo esta noche
</h1>

<p style="text-align:center;">
    Estreno de temporada
</p>

<p style="background-color:yellow;">
    Sorteo de una tarjeta gráfica
</p>


Explicación: Se añade el punto y coma que faltaba, se sustituye = por : en text-align y se cierra el último párrafo correctamente.
A5. Comentarios y anidación
<!-- Revisar el texto antes de publicar -->

<p>
    Tu contraseña debe tener
    <strong><em>al menos 12 caracteres</em></strong>.
</p>
