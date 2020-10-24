<h1>Âncoras</h1>
</p>Link de âncora (ou "desvio de página") é uma URL especial que direciona você para um lugar específico da página. Para isso, basta passar um atributo “id” com um nome para o elemento que se quer localizar, e passar esse nome no href com “#”.</p>
<br/>
<h3>Exemplo:</h3>

    <!doctype html>
    <html>
    <head>
    <meta charset="utf-8">
    <title></title>
    </head>
    <body>
    <h1>Lorem luctus consectetur</h1> <br>
    <a href="#title1">Lorem ipsum</a>
    <a href="#title2">Ut fermentum luctus </a>
    <a href="#title3">In in lorem erat. </a>
    <a href="#title4">Nullam tellus </a>

    <h2 id="title1">Lorem ipsum</h2>
    <p>
        Dolor sit amet, consectetur adipiscing elit. Aliquam mattis.
    </p>

    <h2 id="title2">Ut fermentum luctus</h2>
    <p>
        Enim non hendrerit. Aliquam justo nulla, ultricies sed pretium non, tempor at erat.
    </p>

    <h2 id="title3">In in lorem erat.</h2>
    <p>
        Vivamus ac pellentesque metus, eget hendrerit sem. Aenean in sollicitudin lacus, consequat porttitor ante.
    </p>

    <h2 id="title4">Nullam tellus</h2>
    <p>
        Magna, pulvinar vitae convallis eu, vestibulum sit amet nisl. 
    </p>
    </body>
    </html>
<hr/>
<h3>Resultado:</h3>
    <!doctype html>
    <html>
    <head>
    <meta charset="utf-8">
    <title></title>
    </head>
    <body>
    <h1>Lorem luctus consectetur</h1> <br>
    <a href="#title1">Lorem ipsum</a>
    <a href="#title2">Ut fermentum luctus </a>
    <a href="#title3">In in lorem erat. </a>
    <a href="#title4">Nullam tellus </a>

   <h2 id="title1">Lorem ipsum</h2>
    <p>
        Dolor sit amet, consectetur adipiscing elit. Aliquam mattis.
    </p>

   <h2 id="title2">Ut fermentum luctus</h2>
    <p>
        Enim non hendrerit. Aliquam justo nulla, ultricies sed pretium non, tempor at erat.
    </p>

   <h2 id="title3">In in lorem erat.</h2>
    <p>
        Vivamus ac pellentesque metus, eget hendrerit sem. Aenean in sollicitudin lacus, consequat porttitor ante.
    </p>

   <h2 id="title4">Nullam tellus</h2>
    <p>
        Magna, pulvinar vitae convallis eu, vestibulum sit amet nisl. 
    </p>
    </body>
    </html>