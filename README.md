# DREaM: Drug-Drug Relation Extraction via Transfer Learning Method

Relation extraction between drugs plays a crucial role in identifying drug–drug interactions and predicting side effects. The advancement of machine learning methods in relation extraction, along with the development of large medical text databases, has enabled the low-cost extraction of such relations compared to other approaches that typically require expert knowledge.

However, to the best of our knowledge, there are limited datasets specifically designed for drug–drug relation extraction currently available. Therefore, employing transfer learning becomes necessary to apply machine learning methods in this domain.

In this study, we propose **DREaM**, a method that first employs a trained relation extraction model to discover relations between entities and then applies this model to a corpus of medical texts to construct an ontology of drug relationships. The extracted relations are subsequently validated using a large language model (LLM).

Quantitative results indicate that the LLM agreed with **71 %** of the relations extracted from a subset of **PubMed abstracts**. Furthermore, our qualitative analysis indicates that this approach can uncover ambiguities in the medical domain, highlighting the challenges inherent in relation extraction in this field.
