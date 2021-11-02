Są dwa sposoby umieszczania/pozycjonowania duszków na warstwach.

Możesz przeciągnąć duszka na scenę, aby przenieść go na wierzch:

![Przeciągnięcie duszka na scenę, aby przenieść go na wierzch, a następnie przeciągnięcie innego duszka na scenę, aby teraz tego przenieść go na wierzch.](images/drag-sprite-change-layers.gif){:width="300px"}

Alternatywnie możesz użyć `przesuń na wierzch`{:class="block3looks"} lub `przesuń na spód`{:class="block3looks"}, aby umiejscowić duszka.

Jeśli chcesz, aby duszek zawsze pozostawał na warstwie `wierzch`{:class="block3looks"} lub `spód`{:class="block3looks"}, użyj `zawsze`{:class="block3control"}, aby duszek cofał się do właściwej warstwy, jeśli przypadkowo go przesuniesz:

```blocks3
when flag clicked
forever
go to [front v] layer // lub z powrotem
```

