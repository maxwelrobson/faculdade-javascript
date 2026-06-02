Faça você mesmo!
Vamos retomar um código já apresentado no conteúdo:

Faça as seguintes alterações no código:

 

Mova o código que está entre as linhas 12 e 51, inclusive, para dentro da seção <head>.
Salve a alteração.
Carregue novamente sua página.
 

Assinale a alternativa correta que demonstra o resultado da execução do código, após modificado, no navegador web.

Parabéns! A alternativa B está correta.
Ao final da execução do script, quando a página web é carregada, o alerta é exibido, mas a div “exibe_resultado” não recebe o valor de resultado da multiplicação. Isso acontece porque, quando está no início da página, o código é lido pelo navegador antes que o restante seja renderizado. Portanto, a tag div, por exemplo, ainda não foi carregada e não está presente na árvore DOM.