# Alura MIDI

## Projeto de um instrumento musical de interface digitial (MIDI), que reproduz sons de instrumentos musicais, por enquanto de uma bateria, ao usuário clicar ou pressionar com teclado em seus botões.

![Animation2](https://user-images.githubusercontent.com/97718074/173210520-ccdb9f9a-a046-4c44-92b9-8e0a5591700b.gif)

## Sobre o projeto
O MIDI tem um teclado digitial com 9 botões, cada botão reproduzirá o som de dado instrumento musical. O HTML carregará os arquivos de mídia com o som dos instrumentos através do elemento <audio>, e com o MIDI vamos controlar a reprodução destes arquivos de mídia através do clique em seus elementos <button>. Serão 9 sons diferentes.

## Técnicas utulizadas
  
 - `HTML`: O HTML tem um papel fundamental para a aplicação funcionar corretamente com a inserção dos elementos `<audio>` que irão prover para o JavaScript os controles de reprodução da mídia carregada.
 - `CSS`: O CSS tem papel fundamental para indicar a interação do usuário com a interface gráfica, portanto indica quando os botões são pressionados por mouse ou teclado.
 - `JavaScript`: O JavaScript proporcionará programarmos a dinâmica de controle de reprodução de um som, que a princípio está sendo realizada pelo elemento `<audio>`, e passarmos este controle para os elementos `<button>`.
 
  
