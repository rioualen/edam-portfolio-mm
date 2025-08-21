---
title: "The EDAM ontology"
permalink: /docs/01-scope/
classes: wide
sidebar:
  nav: "documentation_sidebar"
---

## What is EDAM?

### Structured vocabulary

An ontology is essentially a structured vocabulary formalising so-called “concepts” or “classes”. The EDAM ontology focuses on concepts related to life science data analysis & management, and is divided in 4 main sub-ontologies: Topic, Operation, Data, Format.

* **Topics** refer to fields of interest or technologies, from general domains to narrower concepts;
* **Operations** describe functions that process input data and produce output data;
* **Data** concepts are types of information that can be passed as inputs and/or produced as outputs by computational programs;
* **Formats** represent computational file specifications, often associated with specific data types.


<div style="text-align: center">
<img src="{{ '/assets/images/EDAM_hierarchy.png' | relative_url }}" alt="Simple EDAM overal hierarchy" style="width: 600px; height: auto;">
</div>

### Hierarchical and semantic relations

Ontologies allow to define hierarchical & semantic relations between classes. Structured as a taxonomy, an ontology defines a hierarchy where each class is a specialisation from its parent class. Moreover, it allows to define semantic relations, which give a meaning to pieces of information or data. 

EDAM defines 4 main semantic relations between concepts from different sub-ontologies: *has_topic*, *has_input*, *has_output*, *is_format_of*. By definition, a hierarchical relation between a class and its parent classe is semantically equivalent to *is_a*.

<div style="text-align: center">
<img src="{{ '/assets/images/EDAM_relations.png' | relative_url }}" alt="Semantic relations between EDAM sub-ontologies" style="width: 500px; height: auto;">
</div>

### Properties

Each class defined in an ontology can be assigned properties, also called attributes. In EDAM, the minimum required properties for a concept are a label, a concise definition and a unique, persistent ID. The latter ensures that any concept can be used across resources and guarantee its long-term interoperability. 

<div style="text-align: center">
<img src="{{ '/assets/images/EDAM_IDs.png' | relative_url }}" alt="Example of concepts, their relations and PIDs" style="width: 500px; height: auto;">
</div>
