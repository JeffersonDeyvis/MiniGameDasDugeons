<h1 align="center"> Este é o mini game das Dugeons </h1>
<hr>

<div style="text-align: justify"> 
O jogo consiste de um Mapa, um guerreiro e um tesouro.
Nossa tarefa é levar o estimado guerreiro, Melkor, representado por P no mapa M<sub>10x10</sub>,
da posição 10x10 para a posição 1x1 do mapa, que é onde se encontra o tesouro,
representado por T, no entanto ele enfrentará algumas dificuldades no caminho: 
</div>
<hr>

<p>
Este é um exemplo de como o mapa aparecerá para o usuário:
</p>


<p align="center">
 T  _  \#  ^  ^  \#  _  _  _  ^   <br>
 ^  ^  ^  ^  ^  \#  \#  @  ^  _   <br>
 \#  ^  \#  ^  _  ^  \#  _  @  \#   <br>
 _  ^  *  \#  ^  _  \#  \#  _  \#   <br>
 \#  *  ^  ^  ^  \#  _  *  @  _   <br>
 ^  ^  ^  \#  _  _  ^  \#  \#  ^   <br>
 _  \#  _  ^  \#  ^  _  \#  _  _   <br>
 \#  \#  @  \#  *  _  \#  _  \#  ^   <br>
 ^  \#  \#  \#  ^  _  @  ^  ^  \#   <br>
 _  @  ^  _  _  _  \#  ^  \#  P 
</p>
<hr>

<p>
A movimentação de Melkor é implementada da seguinte forma:<br>
<ol>
<li>w -> para cima;</li>
<li>s -> para baixo;</li>
<li>d -> para direita;</li>
<li>a -> para esquerda;
</ol>
</p>
<hr>

<p>
O mapa está repleto de armadilhas, cada armadilha causa dano na vida d Melkor:<br>
<ol>
<li>_ -> chão -------> vida perdida:  0;</li>
<li>^ -> espinhos ---> vida perdida: 15;</li>
<li># -> flechas ----> vida perdida: 25;</li>
<li>@ -> buraco  ----> vida perdida: 40;</li>
<li>* -> chamas  ----> vida perdida: 60;
</ol>
</p>
<hr>

<p>
<div style="text-align: justify"> 
Melkor inicia sua exploração na dugeon com 100 de vida e também anda equipado com 
3 poções que recuperam a vida perdida:
</div>
<ol>
<li>É pedido ao jogador que digite um caractere:</li>
<li>cada poção recupera 20 de vida;</li>
<li>a vida de Melkor terá um limite máximo = 100, ou seja, recuperar vida, não recupera sua saúde além do máximo;</li>
</ol>   
</p>
<hr>

<p>
Para executar o código basta baixar o arquivo dugeons.py em um computador com o python instalado, utilizando o seu editor de textos preferido, ou basta abrir o terminal no diretório onde o arquivo está instalado e digitar:<br>

```
python3 dugeons.py
```
<br>

Se Você não tiver o python instalado no seu pc e usa windows, ainda é possível jogar o mini-game das Dungeons, basta baixar o arquivo dugeons.exe que se encontra no diretório ExecutavelWindwos/dist. <br>
 
Eu utilizo o vs code, ele pode ser obtido em:

https://code.visualstudio.com/. <br>

Editores que recomendo:
<ol>
<li>VsCode</li>
<li>Spyder</li>
</ol>  
link para download do Spyder: 

https://www.anaconda.com/products/individual, https://www.spyder-ide.org/


</p>

