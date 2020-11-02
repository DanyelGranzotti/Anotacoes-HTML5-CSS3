<h1>Float</h1>
<p>
A propriedade float do CSS determina que um elemento deve ser retirado do seu fluxo normal e colocado ao longo do lado direito ou esquerdo do seu containêr, onde textos  e elementos em linha irão se posicionar ao seu redor.
</p>
<h3>Exemplo:</h3>
<p>

    float: left;
    float: right;
    float: none;
    float: inline-start;
    float: inline-end;

    /* Global values */
    float: inherit;
    float: initial;
    float: unset;
</p>

<h3>Valores:</h3>
<p>

<h4>left</h4>
    <p>É uma palavra-chave que indica que o elemento deve flutuar à esquerda do bloco.</p>

<h4>right</h4>
    <p>É uma palavra-chave que indica que o elemento deve flutuar à direita do bloco.</p>

<h4>none</h4>
    <p>É uma palavra-chave que indica que o elemtno não deve flutuar.</p>

<h4>inline-start</h4>
    <p>É uma palavra-chave que indica que o elemento deve flutuar no lado inicial do seu bloco, ou seja, o lado esquerdo em scripts ltr e no direito em scripts rtl.</p>

<h4>inline-end</h4>
    <p>É uma palavra-chave que indica que o elemento deve flutuar no lado final do seu bloco, ou seja, o lado direito em scripts ltr e no esquerdo em scripts rtl. </p>
</p>

<h2>Clear</h2>
<p>
O jeito mais simples de limpar os floats é adicionar a propriedade clear para o próximo cabeçalho que queremos assegurar que esteja alinhado à esquerda. 
</p>

    h2.secondHeading { clear: both; }

<p>
Porém, este método apenas funciona se não existirem outros elementos com o mesmo block formatting context  aos quais nós queiramos que o cabeçalho continue aparecendo ao lado horizontalmente. Se o nosso H2 possui irmãos os quais são barras laterais flutuadas à esquerda e à direita, usar clear irá forçá-lo a aparecer abaixo das duas barras laterais, o que provavelmente não é o que queríamos.</p>

<p>
Se limpar floats em um elemento não é uma opção, uma outra abordagem é limitar o contexto de formatação do bloco do containêr flutuante. Referindo-se ao exemplo acima novamente, aparentemente todos os três quadrados vermelhos possuem um elemento paragrafo P . Nós podemos atribuir a propiedade overflow neste paragrafo para hidden ou auto  para obrigá-lo a expandir para contê-los, porém não permitirá que os mesmos parágrafos pulem fora do limite inferior.</p>

    p.withRedBoxes { overflow: hidden; height: auto; }