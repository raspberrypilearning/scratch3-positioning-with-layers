## Positionner les sprites avec des couches

Il existe deux façons de positionner ton sprite en couches.

Tu peux faire glisser un sprite sur la scène pour le déplacer vers la couche avant.

! [[Faire glisser un sprite sur la scène pour le déplacer vers l'avant, puis faire glisser un autre sprite pour le déplacer vers l'avant.](images/drag-sprite-change-layers.gif){:width="300px"}

Tu peux également utiliser un `aller à l'avant-plan`{:class="block3looks"} ou `aller à l'arrière-plan`{:class="block3looks"} pour positionner un sprite.

Si tu veux qu'un sprite reste toujours à l'`avant`{:class="block3looks"} ou l'`arrière`{:class="block3looks"}, utilise une boucle `répéter indéfiniment`{:class="block3control"} pour que le sprite revienne à la bonne couche si tu le déplaces accidentellement.

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
