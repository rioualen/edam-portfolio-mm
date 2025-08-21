---
title: "Navigate EDAM"
nav_order: 1
permalink: /docs/02-finding/
classes: wide
sidebar:
  nav: "documentation_sidebar"
---

## Finding a concept

When documenting resources, one can use controlled terminologies defined by one or several ontologies, making their metadata more FAIR. EDAM allows annotating resources related to the field of life science and data analysis. In order to use it, the first step is to identify the needed term(s) and look for them in the ontology. 

### The EDAM browser

The [EDAM browser](https://edamontology.github.io/edam-browser/) was developed in order to navigate the ontology in an intuitive way, display essential information on each concept , and provide links to some of the associated resources. 

Make sure to select the latest version of EDAM:

<div style="text-align: center">
<img src="{{ '/assets/images/EDAM_browser_1.png' | relative_url }}" alt="Overview of the EDAM browser" style="width: 600px; height: auto;">
</div>

Click on the tree nodes to display their children and basic class information on the right. This information includes the concept’s URI, as well as links to their associated entries in BioPortal and the Ontology Lookup Service (OLS). Those entries provide the full list of properties for the selected concepts.  

<div style="text-align: center">
<img src="{{ '/assets/images/EDAM_browser_2.png' | relative_url }}" alt="Detail of a concept in the EDAM browser" style="width: 600px; height: auto;">
</div>

### Missing concept

If a given concept does not seem to be available in EDAM, consider the following:

- Is there a related concept or a synonym? If so, the corresponding entry can be edited to include a new synonym or edit its definition where relevant. 
- Is it available in other ontologies? BioPortal and OLS allow navigating numerous ontologies and search for specific terms. 
- Is it in the scope of EDAM? If it is out of scope or too specific, you may want to consider other domain ontologies such as EFO, MeSH, SO… 
- If it belongs in EDAM, what would be its parent class? A new concept should be a specialisation of its parent. 

Depending on these elements, you may want to edit an existing concept or suggest the addition of a new one. Guidelines are provided in the following sections.
