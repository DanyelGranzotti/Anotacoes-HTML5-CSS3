<h1>Table Borders</h1>
<p>
Para especificar as bordas da tabela no CSS, use a propriedade "border:".
</p>
<h3>Exemplo:</h3>

    table, th, td {
    border: 1px solid black;
    }
<hr/>


<h2>Full-Width Table</h2>
<p>
Se você precisar de uma tabela que deve abranger toda a tela (largura total), adicione largura: 100% ao elemento < table>
</p>
<h3>Exemplo:</h3>

    table {
    width: 100%;
    }
<hr/>


<h2>Collapse Table Borders</h2>
<p>
A propriedade de "border-collapse" define se as bordas da tabela devem ser colapsadas em uma única borda
</p>
<h3>Exemplo:</h3>

    table {
    border-collapse: collapse;
    }


<p>
Se você quiser apenas uma borda ao redor da tabela, especifique apenas a propriedade da borda para < table>
</p>
<h3>Exemplo:</h3>

    table {
    border: 1px solid black;
    }
<hr/>


<h2>Border Spacing</h2>
<p>
Indica a distância entre as bordas das células da tabela.
</p>
<h3>Exemplo:</h3>

    table {
    border-collapse: separate;
    border-spacing: 10px 50px;
    }
<hr/>


<h2>Caption Side</h2>
<p>
A tag <caption> indica onde a legenda da tabela será posicionada.
</p>
<h3>Exemplo:</h3>
<h4>HTML:</h4>

    <table>
    <caption>Alunos</caption>
    <thead>
<h4>CSS:</h4>

    table, td, tr, th {
    border: 1px solid black;
    border-collapse: collapse;
    }

    caption {
    caption-side: bottom;
    }
<hr/>


<h2>Empty Cells</h2>
<p>
Define quando uma célula vazia deve ser oculta. Disponível apenas quando as bordas são separadas.
</p>
<h3>Exemplo:</h3>

    table, td, tr, th{
    border: 1px solid black;
    empty-cells: hide;
    }