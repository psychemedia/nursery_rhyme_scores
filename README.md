# nursery_rhyme_scores
Scores for nursery rhymes

A simple abc.js editor can be found [here](https://www.abcjs.net/abcjs-editor.html).

For viewing in Python notebooks using `music21`:

```python
from music21 import converter
abcScore = converter.parse('filename.abc')
abcScore.metadata.title = abcScore.metadata.title
display(abcScore.show())
abcScore.show('midi')
```
