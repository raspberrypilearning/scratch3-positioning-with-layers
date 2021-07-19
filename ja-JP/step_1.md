スプライトをレイヤーに配置する方法は 2 つあります。

スプライトをステージ上でドラッグして、最前面のレイヤーに移動できます。

![Dragging a sprite on the Stage to move it to the front, then dragging another sprite on the Stage to move it to the front.](images/drag-sprite-change-layers.gif){:width="300px"}

Alternatively, you can use a `go to front layer`{:class="block3looks"} or `go to back layer`{:class="block3looks"} block to position a sprite.

スプライトを常に `さいぜんめん`{:class="block3looks"} または `さいはいめん`{:class="block3looks"} にしたい場合は、 `ずっと`{:class="block3control"} ループを使用してスプライトを間違って移動したら、スプライトを正しいレイヤーに戻します。

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
