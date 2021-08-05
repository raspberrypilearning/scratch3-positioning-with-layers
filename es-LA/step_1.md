Hay dos formas de colocar tus objetos en capas.

Puedes arrastrar un objeto en el Escenario para moverlo a la capa del frente:

![Arrastrar un objeto en el Escenario para moverlo al frente, luego arrastrar otro objeto para moverlo al frente.](images/drag-sprite-change-layers.gif){:width="300px"}

También puedes usar un bloque `ir a la capa de adelante`{:class="block3looks"} o un bloque `ir a la capa de atrás`{:class="block3looks"} para posicionar un objeto.

Si quieres que un objeto se quede siempre en la capa `de adelante`{:class="block3looks"} o `de atrás`{:class="block3looks"}, usa un bucle `por siempre`{:class="block3control"} para hacer que el objeto regrese a la capa correcta si lo mueves accidentalmente:

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
