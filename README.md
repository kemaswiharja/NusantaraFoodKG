# NusantaraFoodKG — Nusantara Food Ontology

This repository holds the resources for our paper **"Safe Nusantara: A Semi-Automatic Framework for Engineering and Populating a Nusantara Food Ontology"**, published in *IJoICT* (Telkom University).

📄 **Paper:** https://socjs.telkomuniversity.ac.id/ojs/index.php/ijoict/article/download/1042/452

The Nusantara Food Ontology (NFO) models Indonesian (Nusantara) foods and their groupings. Examples include cereals, tubers, legumes and vegetables, along with their processed forms.

## Files

| File | Description |
|---|---|
| `NFOFor2026Book.owl` | **Current version** (57 classes, 27 individuals). It is the companion ontology for the Indonesian-language book *Representasi Pengetahuan*. |
| `NFOAugust22.owl` | Earlier version from August 2022, as used in the paper (schema only). |

Both files are OWL (RDF/XML). You can open them in [Protégé](https://protege.stanford.edu/) or load them with any RDF library, for example:

```python
from rdflib import Graph
g = Graph().parse("NFOFor2026Book.owl")
print(len(g), "triples")
```

## Citation

If you use this ontology, please cite the paper above.

## License

GPL-3.0. See `LICENSE`.
