grid
====

Uma maneira mais eficaz de criar html

Para poder usar esse código é simples, você cria uma classe por exemplo
<div class="w-d960"> seu conteudo </div> e o php faz o resto, ele gera para vc essa class num arquivo css

Eu aconselho você usar um rand tbm assim oh na hora do test para não gerar cache

<link rel="stylesheet" href="site/css/grid.php?<?php rand até 100 ?>">
