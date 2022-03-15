आपके स्प्राइट्स को परतों में रखने के दो तरीके हैं।

आप एक स्प्राइट को मंच पर आगे की परत पर ले जाने के लिए खींच सकते हैं:

![एक प्रेत को मंच पर आगे की ओर ले जाने के लिए उसे खींचकर, फिर मंच पर एक अन्य स्प्राइट को आगे की ओर ले जाने के लिए उसे खींच कर।](images/drag-sprite-change-layers.gif){:width="300px"}

दूसरे तरीके से, आप `go to front layer`{:class="block3looks"} या `go to back layer`{:class="block3looks"} ब्लॉक का उपयोग कर सकते हैं।

अगर आप चाहते हैं कि एक प्रेत हमेशा `सामने (front)`{:class="block3looks"} या `पीछे (back)`{:class="block3looks"} पर बना रहे, तो बनाने के लिए `forever`{:class="block3control"} लूप का उपयोग करें यदि आप गलती से इसे ले जाते हैं तो स्प्राइट सही परत पर वापस चला जाता है:

```blocks3
when flag clicked
forever
go to [front v] layer // या पीछे
```
