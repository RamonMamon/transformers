# Sentence-Transformers

This model can be imported directly via the SentenceTransformers package as shown below:

```python
from sentence_transformers import SentenceTransformer
model = SentenceTransformer('Kiri/kiri-model')
sentences = ['Here is a sample sentence','Another sample sentence']
embeddings = model.encode(sentences)

print("Sentence embeddings:")
print(embeddings)
```



