## レイヤーを使用してスプライトを配置する

スプライトをレイヤーに配置する方法は 2 つあります。

スプライトをステージ上でドラッグして、最前面のレイヤーに移動できます。

![ステージ上でスプライトをドラッグして「さいぜんめん」に移動し、別のスプライトをドラッグして最前面に移動します。](images/drag-sprite-change-layers.gif){:width="300px"}

`"さいぜんめん"へいどうする`{:class="block3looks"} または `"さいはいめん"へいどうする`{:class="block3looks"} ブロックを使用し移動することもできます。

スプライトを常に `さいぜんめん`{:class="block3looks"} または `さいはいめん`{:class="block3looks"} にしたい場合は、 `ずっと`{:class="block3control"} ループを使用してスプライトを間違って移動したら、スプライトを正しいレイヤーに戻します。

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
