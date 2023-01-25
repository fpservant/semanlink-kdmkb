# Semanlink-KD-MKB
Export of semanlink data for [kd-mkb](https://github.com/raphaelsty/kdmkb)

## Data
An export of the whole [semanlink](http://www.semanlink.net) data is provided in the ``files`` folder. It consists of two RDF files (in turtle format): one describing the tags (**sltags.ttl**), the other the documents (**sldocs.ttl**). The former contains the description of the graph of tags (using SKOS vocabulary), and the later provides the bookmarks, including, for each of them, the tags that they are tagged with.

(The dataset is provided at different dates)

## Script
A notebook, ``rdf2kdmkb``, allows to load the 2 files described above, and computes the input expected by kd-mkb.

That's all for the moment.

### Requirements

- Python >= 3.6
- pip install rdflib
