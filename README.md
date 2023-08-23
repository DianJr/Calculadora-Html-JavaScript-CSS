# Calculadora-Html-e-JavaScript
Bem dei uma estudada em alguns comandos e com alguns auxilios criei essa calculadora simples
O Passo a Passo foi: 

1- Comecei declarando o doctype html: Isso declara o tipo de documento.

2- html lang='pt-br': Abre a tag html e coloquei o idioma da página como português do Brasil.

3- tag head: Começa o cabeçalho, onde as informações meta e o título da página são especificados. O conteúdo dentro desta tag não é exibido na página, mas fornece informações sobre a página para o navegador.

4- tag title: Defini o título da página exibido na aba do navegador sendo a palavra Calculadora, e depois fechei a head

5- <body>: Abre o corpo da página, onde o conteúdo visível é colocado.

6- Depois Criei um h1 para a palavra calculadora pra ficar como cabeçalho da pagina

7- Depois comecei a fazer os inputs para a calculadora 

8- Comecei criando um button on click 'somar' que, quando clicado, chama a função somar() definida no JavaScript.

Outros botões de operação (Subtrair, Multiplicar, Dividir) seguem a mesma lógica.

9- fiz um comando de span que é um espaço reservado onde o resultado será exibido. Inicialmente, está vazio.

10- Criei a tag script para incorporar código JavaScript no documento.

11- var n1 = document.querySelector('#n1');: Isso define a variável n1 para armazenar uma referência ao elemento HTML com o id n1, ou seja, o primeiro campo de entrada.Fiz mais duas varias uma para n2 e outra para o resultado.

12- Depois comecei a fazer o processo das 4 operações que seguiam esse logica:                                              
  function somar() {
            resultado.innerHTML = parseFloat(n1.value) + parseFloat(n2.value)
Todas as outras três seguiam a mesma lógica so mudavam os sinais de operação de cada uma e os nomes no lugar de somar por exemplo viraria subtrair caso fosse subtração a operação

13- parseFloat(): Converte os valores dos campos de entrada em números de ponto flutuante (decimais) para realizar as operações corretamente.

14- resultado.innerHTML: Atualiza o conteúdo do elemento span com o resultado da operação.

15- </script>: Fecha a tag <script>.

</body>: Fecha a seção do corpo da página.

</html>: Fecha a tag <html>.
