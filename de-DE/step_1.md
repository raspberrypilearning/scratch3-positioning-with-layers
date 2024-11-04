Es gibt zwei Möglichkeiten, die Figuren in Ebenen anzuordnen.

Du kannst eine Figur auf der Bühne ziehen, um es in die vordere Ebene zu verschieben:

![Ziehe eine Figur auf der Bühne, um sie nach vorne zu verschieben. Ziehe dann eine andere Figur auf der Bühne, um diese nach vorne zu verschieben.](images/drag-sprite-change-layers.gif){:width="300px"}

Du kannst auch einen Block vom Typ `gehe zu vorderster Ebene`{:class="block3looks"} oder `gehe zu hinterster Ebene`{:class="block3looks"} verwenden, um eine Figur zu positionieren.

Wenn du eine Figur immer im `Vordergrund`{:class="block3looks"} oder `Hintergrund`{:class="block3looks"} halten möchtest, kannst du eine `wiederhole fortlaufend`{:class="block3control"} Schleife verwenden, um die Figur immer wieder in die gewünschte Ebene zu holen, solltest du sie versehentlich woanders hin bewegen:

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
