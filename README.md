# Ajax
Repositorio destinado a exemplos de utilização do Ajax
> Acronomo de Asynchronous Javascript And XML.

Ajax é um conjunto de técnicas de desenvolvimento voltado para a web que permite que aplicações trabalhem de modo assíncrono, 
processando qualquer requisição ao servidor em segundo plano.

![](https://miro.medium.com/max/2000/1*v3b022s2UAyhVAFLUtzhJg.png)

## Exemplo De utilização de AJAX

Imagine a ferramenta de sugestões de pesquisa do Google. Ela ajuda a completar as palavras que você digita em tempo real enquanto a página permanece estática.

No início dos anos 90, quando a internet ainda não era tão avançada, a mesma funcionalidade iria exigir que a página fosse recarregada sempre que uma nova sugestão de pesquisa aparecesse na tela. O AJAX permite a troca de informações simultânea sem interferir com outras funções. leia mais nesse link:  (<https://www.hostinger.com.br/tutoriais/o-que-e-ajax/>)

## Como fazer Requisições AJAX

No JavaScript podemos usar o Ojeto ```XMLHttpRequst``` para fazer as requisições segue exemplo:

```let ajax= new XMLHttpRequest();
   ajax.open('GET',url);
   ajax.send();
```
instancia-se um objeto e depois chama-se os métodos referentes a abertura da comunicação e a finalização da mesma.

Gileno Cordeiro Duarte – gileno.cr.duarte@gmail.com
## Exemplos feitos a partir da instrução do Curso de desenvolvimento Web completo Ministrado na plataforma Udemy.
## Links para mais informações:
(<https://www.devmedia.com.br/ajax-tutorial/24797>)



