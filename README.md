<h2>PROBLEM STATEMENT: Competição</h2>
---
<p>Quantidade de diamantes é uma boa forma de medir riqueza no Minecraft pois é um dos recursos minerais mais difícil de ser encontrado e minerado no mapa.</p>
<p>Arthur, Luiz e Pedro decidiram fazer uma competição no Minecraft, para decidir quem iria escolher qual brega que irá tocar durantes suas longas noites de programação no CIn e pediram ajuda de Tantan para disponibilizar suas vilas como moradia para cada um. Foi combinado que a competição iria ser realizada dentro do jogo, na qual cada participante iria criar um mundo do zero e teria que encontrar o máximo de diamantes no tempo definido.</p>
<p>Para deixar a competição mais divertida, eles combinaram que cada um iria definir uma restrição para o programa que computaria qual o maior valor de diamantes encontrado pelos participantes.</p>
1. Luiz definiu que o programa não poderia utilizar nenhuma estrutura condicional em seu código, como IF e outras;
<br/>
2. Pedro proibiu a utilização de quaisquer funções de bibliotecas externas para calcular o máximo da quantidade de diamantes do vencedor;
<br/>
3. Arthur falou que, para encontrar o valor final da quantidade máxima de diamantes, seria obrigatório utilizar a seguinte função para encontrar o máximo entre 2 valores: x = (a + b + (|a - b|)) / 2.
<br/><br/>
<p>Visando deixar a solução mais simples, Arthur e Pedro chegaram a um acordo e decidiram que seria permitido utilizar funções externas para calcular o valor absoluto de um número (abs(), em Python).</p>
<p>Sua tarefa é escrever o programa que vai auxiliar os três a descobrir o vencedor da competição, em acordo com todas as restrições.</p>
<h3>Input</h3>
---
<br/>
- A (número natural)
<br/>
- L (número natural)
<br/>
- P (número natural)
<br/>
- H (número natural) -> (1 <= H)
<br/><br/>
<p>As três primeiras linhas representam a quantidade média de diamantes obtidos por hora de Arthur, Luiz e Pedro, respectivamente.</p>
<p>A quarta linha de entrada é composta por um valor que representa a duração da competição, em horas.</p>
<p>Obs: Você deve considerar que a entrada é amigável, ou seja, sempre estará dentro do formato descrito.</p>
<h3>Output</h3>
---
<br/>
- M (número natural)
<br/><br/>
<p>A linha única da saída é composta por um valor que representa o valor máximo de diamantes obtido por um participante, na competição.</p>