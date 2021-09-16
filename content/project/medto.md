+++
title = "MEDTO: Medical Data to Ontology Matching using Hybrid Graph Neural Networks"
date = 2021-05-15T00:00:00
math = false
highlight = true

# List fomat.
#   0 = Simple
#   1 = Detailed
list_format = 1

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""
+++

## Abstract
Medical ontologies are widely used to describe and organize medical terminologies and to support many critical applications on healthcare databases. These ontologies are often manually curated (e.g., UMLS, SNOMED CT, and MeSH) by medical experts. Medical databases, on the other hand, are often created by database administrators, using different terminology and structures. The discrepancies between medical ontologies and databases compromise interoperability between them. Data to ontology matching is the process of finding semantic correspondences between tables in databases to standard ontologies. Existing solutions such as ontology matching have mostly focused on engineering features from terminological, structural, and semantic model information extracted from the ontologies. However, this is often labor-intensive and the accuracy varies greatly across different ontologies. Worse yet, the ontology capturing a medical database is often not given in practice. In this paper, we propose MEDTO, a novel end-to-end framework that consists of three innovative techniques: (1) a lightweight yet effective method that bootstrap a semantically rich ontology from a given medical database, (2) a hyperbolic graph convolution layer that encodes hierarchical concepts in the hyperbolic space, and (3) a heterogeneous graph layer that encodes both local and global context information of a concept. Experiments on two real-world medical datasets matching against SNOMED CT show significant improvements compared to the state-of-the-art methods. MEDTO also consistently achieves competitive results on a benchmark from the Ontology Alignment Evaluation Initiative.

## Modeling

{{< figure library="true" src="project/medto_system.png" title="Fig 1: MEDTO workflow" lightbox="true">}}

{{< figure library="true" src="project/medto_ontognn.png" title="Fig 2: MEDTO matching module" lightbox="true">}}

## More Info

**Publication:** The 27th International ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD 2021)

**Date:** August, 2021

**Links:** [Paper (ACM Library)](https://dl.acm.org/doi/10.1145/3447548.3467138), [PDF](https://www.haojunheng.com/files/pubs/KDD21_MEDTO.pdf), [Slides](https://www.haojunheng.com/files/pubs/KDD21_MEDTO_Slides.pdf), [Poster](https://www.haojunheng.com/files/pubs/KDD21_MEDTO_Poster.pdf), [Video](https://drive.google.com/file/d/1XIJU0k17xGe0fQwuLBxHHZby3pTlQVgq/view?usp=sharing)