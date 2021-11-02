ನಿಮ್ಮ ಸ್ಪ್ರೈಟ್ ಗಳನ್ನು ಪದರಗಳಾಗಿ ಇರಿಸಲು ಎರಡು ಮಾರ್ಗಗಳಿವೆ.

ಮುಂಭಾಗದ ಪದರಕ್ಕೆ ಸರಿಸಲು ನೀವು ಸ್ಪ್ರೈಟ್ ಅನ್ನು ಸ್ಟೇಜ್ ಮೇಲೆ ಎಳೆಯಬಹುದು:

![ಒಂದು ಸ್ಪ್ರೈಟ್ ಅನ್ನು ಮುಂಭಾಗಕ್ಕೆ ಸರಿಸಲು ಸ್ಟೇಜ್ ಮೇಲೆ ಎಳೆಯಿರಿ, ನಂತರ ಅದನ್ನು ಮುಂದೆ ಸರಿಸಲು ಸ್ಟೇಜ್ ಮೇಲೆ ಇನ್ನೊಂದು ಸ್ಪ್ರೈಟ್ ಅನ್ನು ಎಳೆಯಿರಿ.](images/drag-sprite-change-layers.gif){:width="300px"}

ಪರ್ಯಾಯವಾಗಿ, `go to front layer`{:class="block3looks"} ಅಥವಾ `go to back layer`{:class="block3looks"} ಬ್ಲಾಕ್ ಅನ್ನು ಬಳಸಬಹುದು.

ಸ್ಪ್ರೈಟ್ ಯಾವಾಗಲೂ `front`{:class="block3looks"} ಅಥವಾ `back`{:class="block3looks"} ನಲ್ಲಿ ಉಳಿಯಲು ಬಯಸಿದರೆ, `forever`{:class="block3control"} ಲೂಪ್ ಬಳಸಿ ನೀವು ಆಕಸ್ಮಿಕವಾಗಿ ಅದನ್ನು ಸರಿಸಿದರೆ ಸ್ಪ್ರೈಟ್ ಸರಿಯಾದ ಪದರಕ್ಕೆ ಹಿಂತಿರುಗುತ್ತದೆ:

```blocks3
when flag clicked
forever
go to [front v] layer // or back
```
