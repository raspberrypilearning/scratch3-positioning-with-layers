Det finns två sätt att placera dina sprajter i lager.

Du kan dra en sprajt på scenen för att flytta den till det främre lagret:

![Dra en sprajt på scenen för att flytta fram den, dra sedan en annan sprajt på scenen för att flytta fram den.](images/drag-sprite-change-layers.gif){:width="300px"}

Annars kan du använda ett `"gå till översta lagret"`{:class="block3looks"}-block eller `"gå till det bakre lagret"`{:class="block3looks"}-block för att placera en sprajt.

Om du vill att en sprajt alltid ska vara `framme`{:class="block3looks"} eller `bak`{:class="block3looks"}, använd en `"för alltid"`{:class="block3control"}-loop för att få sprajten att flytta tillbaka till rätt lager om du av misstag flyttar den:

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
