Il existe deux façons de positionner tes sprites en calques.

Tu peux faire glisser un sprite sur la scène pour le déplacer vers la couche avant:

![Faire glisser un sprite sur la scène pour la déplacer vers l'avant, puis faire glisser un autre sprite sur la scène pour la déplacer vers l'avant.](images/drag-sprite-change-layers.gif){:width="300px"}

Alternativement, tu peux utiliser un `aller à l'avant plan`{:class="block3looks"} ou `aller à l'arrière plan`{:class="block3looks"} pour positionner un sprite.

Si tu veux qu'un sprite reste toujours à l'`avant`{:class="block3looks"} ou à l'`arrière`{:class="block3looks"}, utilise une boucle `répéter indéfiniment`{:class="block3control"} pour que le sprite revienne au bon plan si tu le déplaces accidentellement :

```blocks3
when green flag clicked
répéter indéfiniment
go to [avant v] layer // ou l'arrière
```
