---
title: "Scope of EDAM"
permalink: /docs/01-scope/
classes: wide
sidebar:
  nav: "documentation_sidebar"
---

## The EDAM ontology

Ontology = controlled vocabulary formalising concepts structured as a taxonomy of classes, where each subclass (or ‘child’) is a specialisation from its parent class, thus  defining hierarchical relations

EDAM focuses on concepts related to (life) science data analysis & management, and is structured as 4 main sub-ontologies: Topic, Operation, Data, Format

* **Topic:** a domain or field of interest, of study, application, work, data, technology…
* **Operation:** a function that processes a set of inputs and results in a set of outputs
* **Data:** information that can be passed as input and/or produced as output by computational
* **Format:** a defined way or layout of representing and structuring data in a computer file

<div style="display: flex; align-items: center; gap: 1em; margin-bottom: 1em;">
  <img src="{{ '/assets/images/EDAM_hierarchy.png' | relative_url }}" alt="Simple EDAM overal hierarchy" style="width: 300px; height: auto;">
  <h2 style="margin: 0;"></h2>
</div>

Ontologies also allow to define semantic relations between classes

Concepts in EDAM allow to define 4 main types of semantic relations

<div style="display: flex; align-items: center; gap: 1em; margin-bottom: 1em;">
  <img src="{{ '/assets/images/EDAM_relations.png' | relative_url }}" alt="Semantic relations between EDAM sub-ontologies" style="width: 300px; height: auto;">
  <h2 style="margin: 0;"></h2>
</div>

Each class or concept has a set of properties, or attributes, including unique & persistent IDs

<div style="display: flex; align-items: center; gap: 1em; margin-bottom: 1em;">
  <img src="{{ '/assets/images/EDAM_IDs.png' | relative_url }}" alt="Example of concepts, their relations and PIDs" style="width: 300px; height: auto;">
  <h2 style="margin: 0;"></h2>
</div>

