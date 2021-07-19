Hay dos formas de colocar tus objetos en capas.

Puedes arrastrar un objeto en el Escenario para moverlo a la capa del frente:

![Dragging a sprite on the Stage to move it to the front, then dragging another sprite on the Stage to move it to the front.](images/drag-sprite-change-layers.gif){:width="300px"}

Alternatively, you can use a `go to front layer`{:class="block3looks"} or `go to back layer`{:class="block3looks"} block to position a sprite.

Si quieres que un objeto se quede siempre en la capa `del frente`{:class="block3looks"} o `de atrás`{:class="block3looks"}, usa un bucle `por siempre`{:class="block3control"} para hacer que el objeto regrese a la capa correcta si lo mueves accidentalmente:

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
