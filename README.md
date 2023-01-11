# 📝 Resumo Projeto 2 DEVStart - Dados dos Atletas
Trata-se de um projeto de aplicação capaz de receber as informações de um atleta, bem como calcular parãmetros e exibi-los ao usuário, <strong>feito somente em JS</strong>.

<h2>✍️Introdução</h2>
<p>

Os organizadores da competição realizada durante o projeto anterior gostaram muito da sua solução proposta e do seu perfil de desenvolvimento. Com isso, eles resolveram fazer uma nova encomenda utilizando a linguagem JavaScript, onde você deverá criar um software capaz de receber informações dos atletas e exibir a categoria, IMC, média calculada e demais informações capturadas.

</p>

<h2>📋Especificações</h2>
<p>
Você deverá criar uma classe <strong>Atleta</strong> para concentrar os atributos e métodos dos atletas.<br>

A classe deverá receber os seguintes atributos:<br>

<ul>
  <li><strong>nome</strong></li>
  <li><strong>idade</strong></li>
  <li><strong>peso</strong></li>
  <li><strong>altura</strong></li>
  <li><strong>notas</strong></li>
</ul>
<br>
A classe deverá possuir os seguintes métodos:

<br>
<br>
<ul>
  <li><strong>calculaCategoria()</strong>, para calcular a categoria do atleta;</li>
  <li><strong>calculaIMC()</strong>, para calcular o IMC do atleta;</li>
  <li><strong>calculaMediaValida()</strong>, para calcular a média válida do atleta;</li>
  <li><strong>obtemNomeAtleta()</strong>, que retorna o nome do atleta;</li>
  <li><strong>obtemIdadeAtleta()</strong>, que retorna a idade do atleta;</li>
  <li><strong>obtemPesoAtleta()</strong>, que retorna o peso do atleta;</li>
  <li><strong>obtemNotasAtleta()</strong>, que retorna as notas do atleta;</li>
  <li><strong>obtemCategoria()</strong>, que retorna a categoria do atleta;</li>
  <li><strong>obtemIMC()</strong>, que retorna o IMC do atleta;</li>
  <li><strong>obtemMediaValida()</strong>, que retorna a média válida do atleta;</li>
</ul>
<br>
<h3>Utilize as seguintes regras:</h3>
<br>
<ol>
  <h3><strong><li>Para calcular a categoria</li></strong></h3>
    <ul>
       <li>Infantil: 9 a 11 anos</li>
       <li>Juvenil: 12 e 13 anos</li>
       <li>Intermediário: 14 e 15 anos</li>
       <li>Adulto: 16 a 30 anos</li>
       <li>Sem categoria: demais idades</li>
    </ul>
  <h3><strong><li>Para calcular o IMC</li></strong></h3>
     <ul>
       <li>Fórmula: IMC = peso / (altura x altura)</li>
    </ul>
  <h3><strong><li>Para calcular a média válida</li></strong></h3>
    <ul>
       <li>Método: A média é calculada com base nas três notas do meio, desconsiderando a maior e menor nota.</li>
    </ul>
</ol>


</p>

<h2>Exemplo de entrada</h2>
<br>


![exemplo_saida](https://user-images.githubusercontent.com/105760259/211915281-44428133-9c1b-44ba-b2f6-739ec3a23ff4.png)

<br>
<h2>Exemplo de saída</h2>
<br>



![exemplo_saida](https://user-images.githubusercontent.com/105760259/211915630-581b250f-d393-4f40-ad15-ecb1c80fb82b.png)








