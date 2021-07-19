Existem duas formas de posicionar seus atores sobre as camadas.

Você pode arrastar um ator no palco para movê-lo para a camada da frente:

![Dragging a sprite on the Stage to move it to the front, then dragging another sprite on the Stage to move it to the front.](images/drag-sprite-change-layers.gif){:width="300px"}

Alternatively, you can use a `go to front layer`{:class="block3looks"} or `go to back layer`{:class="block3looks"} block to position a sprite.

Se você quiser que um ator sempre permaneça na `frente`{:class="block3looks"} ou `nos fundos`{:class="block3looks"}, use um laço `sempre`{:class="block3control"} para fazer o ator voltar para a camada correta se você o mover de forma acidentalmente ou sem querer:

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
