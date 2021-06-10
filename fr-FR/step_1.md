## Positionner les sprites avec des couches

There are two ways to position your sprites into layers.

You can drag a sprite on the Stage to move it to the front layer:

![Dragging a sprite on the Stage to move it to the front, then dragging another sprite to move it to the front.](images/drag-sprite-change-layers.gif){:width="300px"}

Tu peux également utiliser un `aller à l'avant-plan`{:class="block3looks"} ou `aller à l'arrière-plan`{:class="block3looks"} pour positionner un sprite.

If you want a sprite to always stay at the `front`{:class="block3looks"} or `back`{:class="block3looks"}, use a `forever`{:class="block3control"} loop to make the sprite move back to the correct layer if you accidentally move it:

```blocks3
quand le drapeau est cliqué
répéter indéfiniment
aller à l' [avant v] // ou l'arrière
```
