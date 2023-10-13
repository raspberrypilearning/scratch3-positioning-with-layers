Existem duas formas de posicionar seus atores em camadas.

Você pode arrastar um ator no palco para movê-lo para a camada da frente:

![Arrastar um ator no Palco para movê-lo para frente, em seguida, arrastar outro ator no Palco para movê-lo para frente.](images/drag-sprite-change-layers.gif){:width="300px"}

Você também pode usar um bloco `vá para a camada da frente`{:class="block3looks"} ou `vá para a camada de trás`{:class="block3looks"} para posicionar o ator.

Se você quiser que um ator sempre permaneça na `frente`{:class="block3looks"} ou `atrás`{:class="block3looks"}, use um laço `sempre`{:class="block3control"} para fazer o ator voltar para a camada correta se você o moveu acidentalmente:

```blocks3
when flag clicked
forever
go to [front v] layer // ou atrás
```
