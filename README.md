## GET & POST
No método GET: As informações do usuário como por exemplo nome, e-mail, número de telefone vão todos escritos do lado de fora, para qualquer pessoa ver, pois com o GET essas informações vão aparecer na URL, ou seja, na barra do navegador logo após um símbolo. Ex: "site.com/this&that?nome=sara&telefone=1430".
Já no método POST: As mesmas informações vão ser escondidas no corpo da requisição HTTP e não irão aparecer na URL, o que também ajuda para que ela não fique longa, nem poluída.
---
## CODIFICAÇÃO DOS DADOS (URL Encoding)
Já que as URLs aceitam apenas um grupo restrito de caracteres padrão, os símbolos especiais ou espaços precisam ser transformados via Encoding URL para que o servidor consiga ler as informações sem erros. Por exemplo, na hora do envio o espaço é convertido para + ou %20, e o @ é codificado como %40.
---
## REFLEXÃO/TEMA ESCOLHIDO:
Um formulário que atende pedidos de uma cafeteria chamada "This & That", a estética foi inspirada em um álbum musical que possui o conceito de cafeteria, particularmente me agrado do design e decidi me inspirar, os sabores e preços também foram escolhidos por mim. 
{Implementei um pouco de CSS para conseguir seguir melhor a estética}.
---
## ESCOLHA DOS CONTROLES:
Usei as caixinhas do (checkbox) nas bebidas para o cliente conseguir marcar mais de uma opção no mesmo pedido. Já no adoçante usei o (radio), porque aí ele só pode escolher uma opção por vez, não tem como pedir com e sem açúcar ao mesmo tempo.
---
## O QUE FARIA COM MAIS TEMPO:
Queria com a ajuda de alguma linguagem de programação, fazer um sistema que pudesse calcular o valor total da compra e informar ao cliente no próprio formulário antes de finalizar o pedido.
---
