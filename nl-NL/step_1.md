There are two ways to position your sprites into layers.

You can drag a sprite on the Stage to move it to the front layer:

![Dragging a sprite on the Stage to move it to the front, then dragging another sprite on the Stage to move it to the front.](images/drag-sprite-change-layers.gif){:width="300px"}

Alternatively, you can use a `go to front layer`{:class="block3looks"} or `go to back layer`{:class="block3looks"} block to position a sprite.

Als je wilt dat een sprite altijd op de `voorste laag`{:class="block3looks"} of `achterste laag`{:class="block3looks"} blijft, gebruik dan een `herhaal`{:class="block3control"} lus om de sprite terug naar de juiste laag te plaatsen voor als je hem per ongeluk verplaatst:

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
