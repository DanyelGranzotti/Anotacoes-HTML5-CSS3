<h1>Tipos de posicionamento</h1>
<p>Quando queremos alterar a posição, mudamos os valores das propriedades top, left, bottom e right. O modo como definimos a propriedade “position” irá mudar o modo do elemento responder ao posicionamento.</p>

<h2>Posicionamento Estático</h2>
<p>O padrão de todos os elementos é o “static” (estático). Nesse modo os elementos são apresentados de acordo com o fluxo do código HTML, sem nada especial. Por essa razão, as propriedades top, right, bottom e left não surtirão efeito nenhum.</p>

<h2>Posicionamento Fixo</h2>
<p>O valor fixed usado em position deixa o bloco posicionado de maneira fixa em relação a uma referência. O contexto de posicionamento é sempre a área de renderização, exemplo, canto superior esquerdo da tela do navegador. O bloco com esse valor não se movimenta quando há rolagem na página. O IE6 não suporta essa declaração.</p>

<h2>Posicionamento Relativo</h2>
<p>Quando definimos a propriedade position como “relative”, o elemento será “empurrado” em relação à sua posição normal.
Se colocarmos “right: 30px”, o elemento será empurrado por 30px a partir do seu canto direito, ou seja, irá para a esquerda.</p>

<h2>Posicionamento Absoluto</h2>
<p>Para declararmos um bloco com posicionamento absoluto usamos a propriedade position:absolute. Um bloco com posicionamento absoluto retira o elemento da posição original, fazendo com que o lugar deixado seja ocupado pelo elemento que se segue.</p>

