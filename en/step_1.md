There are two ways to position your sprites into layers.

You can drag a sprite on the Stage to move it to the front layer:

![Dragging a sprite on the Stage to move it to the front, then dragging another sprite on the Stage to move it to the front.](images/drag-sprite-change-layers.gif){:width="300px"}

Alternatively, you can use a `go to front layer`{:class="block3looks"} or `go to back layer`{:class="block3looks"} block to position a sprite.

If you want a sprite to always stay at the `front`{:class="block3looks"} or `back`{:class="block3looks"}, use a `forever`{:class="block3control"} loop to make the sprite move back to the correct layer if you accidentally move it:

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
