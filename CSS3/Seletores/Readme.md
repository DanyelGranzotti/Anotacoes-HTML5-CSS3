<h1>Seletores</h1>
<p>
Os seletores CSS são usados para "encontrar" (ou selecionar) os elementos HTML que você deseja estilizar.
Podemos dividir os seletores de CSS em cinco categorias:
<ul>
<li>Selecionadores simples (selecione elementos com base no nome, id, classe)</li>
<li>Combinadores seletores (selecionar elementos com base em uma relação específica entre eles)</li>
<li>Selecionadores de classe Pseudo (selecionar elementos com base em um determinado estado)</li>
<li>Pseudo-elementos seletores (selecionar e estilizar uma parte de um elemento)</li>
<li>Selecionadores de atributos (selecionar elementos com base em um atributo ou valor de atributo)</li>
</ul>
</p>

<br/>
<hr/>
<br/>

<h2>The CSS id Selector</h2>
<p>
O seletor de id usa o atributo id de um elemento HTML para selecionar um elemento específico.
O id de um elemento é único dentro de uma página, então o seletor de id é usado para selecionar um elemento único!
Para selecionar um elemento com um id específico, escreva um caractere hash (#), seguido pelo id do elemento.
</p>
<h3>Exemplo:<h3>

    #para1 {
    text-align: center;
    color: red;
    }
<hr/>

<h2>The CSS class Selector</h2>
<p>
O seletor de classes seleciona elementos HTML com um atributo de class específico.
Para selecionar elementos com uma classe específica, escreva um caractere de ponto (.), seguido do nome da classe.
</p>
<h3>Exemplo:<h3>

    .center {
    text-align: center;
    color: red;
    }

<p>
Você também pode especificar que somente elementos HTML específicos devem ser afetados por uma classe.
</p>
<h3>Exemplo:<h3>

    p.center {
    text-align: center;
    color: red;
    }

<hr/>
<h2>The CSS Universal Selector</h2>
<p>
O seletor universal (*) seleciona todos os elementos HTML na página.
</p>
<h3>Exemplo:</h3>

    * {
    text-align: center;
    color: blue;
    }

<hr/>
<h2>CSS Selector Reference</h2>
<table>
<tbody>
<tr>
<td>
<p><strong>Seletor</strong></p>
</td>
<td>
<p><strong>Exemplo</strong></p>
</td>
<td>
<p><strong>Descrição do Exemplo</strong></p>
</td>
</tr>
<tr>
<td>
<p>sel, sel</p>
</td>
<td>
<p>div, #minhaLista</p>
</td>
<td>
<p>Seleciona todas as divs e o elemento com id=“minhaLista”. A vírgula serve para listarmos os elementos que queremos selecionar.</p>
</td>
</tr>
<tr>
<td>
<p>sel sel</p>
</td>
<td>
<p>div p</p>
</td>
<td>
<p>Seleciona todos os elementos &lt;p&gt; que estejam dentro do elemento &lt;div&gt;. Não importa se &lt;p&gt; é filho de outro elemento que não seja &lt;div&gt;.</p>
</td>
</tr>
<tr>
<td>
<p>sel &gt; sel</p>
</td>
<td>
<p>div &gt; p</p>
</td>
<td>
<p>Seleciona todos os elementos &lt;p&gt; que o pai seja &lt;div&gt;. Nesse caso é obrigatório o &lt;p&gt; ser filho direto da &lt;div&gt;.</p>
</td>
</tr>
<tr>
<td>
<p>sel + sel</p>
</td>
<td>
<p>div + p</p>
</td>
<td>
<p>Seleciona todos os elementos &lt;p&gt; que são precedidos por uma tag &lt;div&gt;, como:</p>
<p>&lt;div&gt;&lt;/div&gt;</p>
<p>&lt;p&gt;&lt;/p&gt;</p>
<p>Se houver algo separando as duas tags, essa seleção não funcionará.</p>
</td>
</tr>
<tr>
<td>
<p>sel ~ sel</p>
</td>
<td>
<p>div ~ p</p>
</td>
<td>
<p>Seleciona todos os elementos &lt;p&gt; que são precedidos por uma tag &lt;div&gt;, como:</p>
<p>&lt;div&gt;&lt;/div&gt;</p>
<p>&lt;input type=”text” /&gt;</p>
<p>&lt;p&gt;&lt;/p&gt;</p>
<p>Essa seleção funciona mesmo se houver algo separando as tags.</p>
</td>
</tr>
<tr>
<td>
<p>[atributo]</p>
</td>
<td>
<p>[readonly]</p>
</td>
<td>
<p>Seleciona todos os elementos que contém o atributo readonly, como:</p>
<p>&lt;input type=”text” readonly /&gt;</p>
</td>
</tr>
<tr>
<td>
<p>[atributo=valor]</p>
</td>
<td>
<p>[type=text]</p>
</td>
<td>
<p>Seleciona todos os elementos que contém o atributo igual ao valor especificado, como:</p>
<p>&lt;input type=”text” /&gt;</p>
</td>
</tr>
<tr>
<td>
<p>:active</p>
</td>
<td>
<p>a:active</p>
</td>
<td>
<p>Seleciona a tag &lt;a&gt; que esteja ativa.</p>
</td>
</tr>
<tr>
<td>
<p>:checked</p>
</td>
<td>
<p>input:checked</p>
</td>
<td>
<p>Seleciona todos os elementos &lt;input&gt; que estejam checados.</p>
</td>
</tr>
<tr>
<td>
<p>:disabled</p>
</td>
<td>
<p>input:disabled</p>
</td>
<td>
<p>Seleciona todo &lt;input&gt; que esteja desabilitado.</p>
</td>
</tr>
<tr>
<td>
<p>:empty</p>
</td>
<td>
<p>p:empty</p>
</td>
<td>
<p>Seleciona todo &lt;p&gt; que não tem filhos ou texto.</p>
</td>
</tr>
<tr>
<td>
<p>:enabled</p>
</td>
<td>
<p>input:enabled</p>
</td>
<td>
<p>Seleciona todo &lt;input&gt; que esteja habilitado.</p>
</td>
</tr>
<tr>
<td>
<p>:first-child</p>
</td>
<td>
<p>p:first-child</p>
</td>
<td>
<p>Seleciona a tag &lt;p&gt; caso ela seja o primeiro filho da tag pai.</p>
</td>
</tr>
<tr>
<td>
<p>:first-of-type</p>
</td>
<td>
<p>p:first-of-type</p>
</td>
<td>
<p>Seleciona todo &lt;p&gt; que seja o primeiro &lt;p&gt; de seu pai.</p>
</td>
</tr>
<tr>
<td>
<p>:focus</p>
</td>
<td>
<p>input:focus</p>
</td>
<td>
<p>Seleciona o elemento &lt;input&gt; que está com foco.</p>
</td>
</tr>
<tr>
<td>
<p>:hover</p>
</td>
<td>
<p>a:hover</p>
</td>
<td>
<p>Seleciona o elemento &lt;a&gt; em que o cursor do mouse está em cima.</p>
</td>
</tr>
<tr>
<td>
<p>:last-child</p>
</td>
<td>
<p>p:last-child</p>
</td>
<td>
<p>Seleciona a tag &lt;p&gt; que seja a última filha de seu pai.</p>
</td>
</tr>
<tr>
<td>
<p>:last-of-type</p>
</td>
<td>
<p>p:last-of-type</p>
</td>
<td>
<p>Seleciona todo &lt;p&gt; que seja o último &lt;p&gt; de seu pai.</p>
</td>
</tr>
<tr>
<td>
<p>:link</p>
</td>
<td>
<p>a:link</p>
</td>
<td>
<p>Seleciona todo link que não foi visitado ainda.</p>
</td>
</tr>
<tr>
<td>
<p>:not(sel)</p>
</td>
<td>
<p>:not(p)</p>
</td>
<td>
<p>Seleciona todos os elementos que não sejam &lt;p&gt;</p>
</td>
</tr>
<tr>
<td>
<p>:nth-child(n)</p>
</td>
<td>
<p>p:nth-child(2)</p>
</td>
<td>
<p>Seleciona todo &lt;p&gt; que seja o segundo filho de seu pai. Altere “n” por qualquer número.</p>
</td>
</tr>
<tr>
<td>
<p>:nth-last-child(n)</p>
</td>
<td>
<p>p:nth-last-child(2)</p>
</td>
<td>
<p>Seleciona todo &lt;p&gt; que seja o penúltimo filho de seu pai. Altere “n” por qualquer número.</p>
</td>
</tr>
<tr>
<td>
<p>:nth-last-of-type(n)</p>
</td>
<td>
<p>p:nth-last-of-type(2)</p>
</td>
<td>
<p>Seleciona todo &lt;p&gt; que seja o penúltimo &lt;p&gt; de seu pai. Altere “n” por qualquer número.</p>
</td>
</tr>
<tr>
<td>
<p>:nth-of-type(n)</p>
</td>
<td>
<p>p:nth-of-type(2)</p>
</td>
<td>
<p>Seleciona todo &lt;p&gt; que seja o segundo &lt;p&gt; de seu pai. Altere “n” por qualquer número.</p>
</td>
</tr>
<tr>
<td>
<p>:only-of-type</p>
</td>
<td>
<p>p:only-of-type</p>
</td>
<td>
<p>Seleciona todo &lt;p&gt; se ele for o único &lt;p&gt; de seu pai.</p>
</td>
</tr>
<tr>
<td>
<p>:only-child</p>
</td>
<td>
<p>p:only-child</p>
</td>
<td>
<p>Seleciona todo &lt;p&gt; que seja o único filho de seu pai.</p>
</td>
</tr>
<tr>
<td>
<p>:visited</p>
</td>
<td>
<p>a:visited</p>
</td>
<td>
<p>Seleciona todos os links que já foram visitados.</p>
</td>
</tr>
</tbody>
</table>
	