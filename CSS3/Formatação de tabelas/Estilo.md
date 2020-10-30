<h1>Estilo</h1>
<h2>Table Padding</h2>
<p>
Para controlar o espaço entre a borda e o conteúdo em uma tabela, use a propriedade de < padding> em < td> e < th> elementos
</p>
<h3>Exemplo:</h3>

    th, td {
    padding: 15px;
    text-align: left;
    }
<hr/>


<h2>Horizontal Dividers</h2>
<p>
Adicionar a propriedade < border-bottom> a < th> e < td> para adicionar divisores horizontais
</p>
<h3>Exemplo:</h3>

    th, td {
    border-bottom: 1px solid #ddd;
    }
<hr/>


<h2>Hoverable Table</h2>
<p>
Use o seletor ":hover" em < tr> para destacar as linhas da tabela em cima do mouse
</p>
<h3>Exemplo:</h3>

    tr:hover {background-color: #f5f5f5;} 
<hr/>


<h2>Striped Tables</h2>
<p>
Para mesas com listras de zebra, use o seletor nth-child() e acrescente uma background-color a todas as linhas da tabela pares (ou ímpares):
</p>
<h3>Exemplo:</h3>

    tr:nth-child(even) {background-color: #f2f2f2;} 
<hr/>


<h2>Table Color</h2>
<p>
Trocar cor de fundo da tabela
</p>
<h3>Exemplo:</h3>

    th {
    background-color: #4CAF50;
    color: white;
    }