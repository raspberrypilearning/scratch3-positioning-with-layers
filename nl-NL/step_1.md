Er zijn twee manieren om je sprite in lagen te plaatsen.

Je kunt een sprite in het werkgebied slepen om deze naar de voorste laag te plaatsen:

![Een sprite in het werkgebied slepen om deze naar voren te plaatsen, en vervolgens een andere sprite slepen om deze naar voren te plaatsen.](images/drag-sprite-change-layers.gif){:width="300px"}

Je kunt ook een `ga naar laag voorgrond`{:class="block3looks"} of `ga naar laag achtergrond`{:class="block3looks"} blok gebruiken om een sprite te positioneren.

Als je wilt dat een sprite altijd op de `voorste laag`{:class="block3looks"} of `achterste laag`{:class="block3looks"} blijft, gebruik dan een `herhaal`{:class="block3control"} lus om de sprite terug naar de juiste laag te plaatsen voor als je hem per ongeluk verplaatst:

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
