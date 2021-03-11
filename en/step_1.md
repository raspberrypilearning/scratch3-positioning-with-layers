## Positioning sprites with layers

There are two ways to position your sprite into layers.

You can drag a sprite on the Stage to move it to the front layer.

![Drag sprites on the Stage to move it to the front](images/drag-sprite-change-layers.gif){:width="300px"}

You can also use a `go to [front v] layer`{:class="block3looks"} or `go to [back v] layer`{:class="block3looks"} block to position a sprite.

If you want a sprite to always stay at the `front`{:class="block3looks"} or `back`{:class="block3looks"} use a `forever`{:class="block3events"} loop to make the sprite move back to the correct layer if you accidentally move it.

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
