Ci sono sue modi per posizionare i tuoi sprite all'interno di un livello.

Puoi trascinare uno sprite sullo Stage per spostarlo in primo piano:

![Trascinando uno sprite sullo Stage per spostarlo in primo piano, poi trascinando un altro sprite sullo stage per spostarlo in primo piano.](images/drag-sprite-change-layers.gif){:width="300px"}

In alternativa, puoi utilizzare un blocco `vai in primo piano`{:class="block3looks"} o `vai in secondo piano`{:class="block3looks"} per posizionare uno sprite.

Se vuoi che uno sprite rimanga sempre su `in primo piano`{:class="block3looks"} o `in secondo piano`{:class="block3looks"}, usa un ciclo `per sempre`{:class="block3control"} per fare in modo che lo sprite torni al livello corretto se lo sposti accidentalmente:

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
