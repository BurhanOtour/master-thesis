# Introduction

The demand for Semantic Web technologies in recent years motivated the construction of a variety of triple stores.
Triple stores are a special kind of data management systems designed to store RDF triple data; a standard defined by 
World Wide Web Consortium (W3C) to represent the data web. 
Triple stores' performance is a crucial requirement to build scalable and reliable semantic web applications around major industrial fields, including medicine, commerce, and defense. For that, the scientific community dedicates a considerable amount of research to investigating approaches to designing high-quality RDF store solutions. Tentris is a novel triple store developed by the data science research group (DICE) at Paderborn university. It represents an RDF graph as a sparse boolean tensor and maps SPARQL operations to tensor operations. Tentris realizes the tensor concept using a trie-based data structure called hypertrie that provides efficient translation of tensor operations. In my thesis, I further contribute to the Tentris project by investigating, implementing, and evaluating an approach to reduce hypertrie memory utilization when storing large RDF data sets.
