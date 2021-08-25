スプライトをレイヤーに配置する方法は 2 つあります。

スプライトをステージ上でドラッグして、最前面のレイヤーに移動できます:

![ステージ上のスプライトをドラッグして最前面に移動し、そしてまた別のスプライトをドラッグして最前面に移動します。](images/drag-sprite-change-layers.gif){:width="300px"}

別の方法として、 `最前面へ移動する`{:class="block3looks"}または `最背面へ移動する`{:class="block3looks"}ブロックを使用し、スプライトを配置することができます。

スプライトを常に `さいぜんめん`{:class="block3looks"} または `さいはいめん`{:class="block3looks"} にしたい場合は、 `ずっと`{:class="block3control"} ループを使用してスプライトを間違って移動したら、スプライトを正しいレイヤーに戻します。

```blocks3
when flag clicked
forever
go to [front v] layer // または戻る
```
