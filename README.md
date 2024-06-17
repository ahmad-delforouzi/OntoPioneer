This repository contains ontologies for an Open Innovation Platform focused on Steel-based Additive Manufacturing (AM) and SMC production. These ontologies are designed to be inferred from the MPCCI Ontologies developed by Fraunhofer SCAI.

## Purpose: 
Facilitate knowledge sharing and data integration within the Open Innovation Platform (OIP) for Steel AM and SMC.

## Source: 
Inferred from MPCCI Ontologies by Fraunhofer SCAI.

## Documentation: 
Refer to the following link for the MPCCI ontology documentation: 
[Link](https://www.researchgate.net/publication/345811171_Whitepaper_ONTOLOGIES_FOR_DIGITAL_TWINS_IN_SMART_MANUFACTURING)

## How to use ontology to find proper data: 
This Jupyter Notebook [MX3D.ipynb](https://github.com/ahmad-delforouzi/OntoPioneer/blob/main/MX3D.ipynb) demonstrates how to access and interact with the Steel Additive Manufacturing (AM) ontology using Python.

## Key functionalities:

Ontology Access: The notebook guides you through connecting to the Steel AM ontology.

SPARQL Queries: You'll learn how to formulate SPARQL queries to perform semantic searches on the ontology.

Data Retrieval: The notebook shows how to retrieve relevant data based on your SPARQL queries.

Data Visualization: Techniques for visualizing the retrieved data are also covered.

You can experiment with the attached notebook (MX3D.ipynb) in a live environment on Google Colab ([link here](https://colab.research.google.com/drive/1eqG2AVu0r5KJivyZxPeOxzbt65Zllxdp#scrollTo=IMemo6g-P63M)).

## Ontology Inferring Examples:

The following diagram illustrates the process of inferring a Thermomechanical Simulation Model from the MPCCI ontologies. This inferred model will be used for the MX3D use case within the PIONEER project.
![image](https://github.com/ahmad-delforouzi/OntoPio/assets/81425722/ea91138c-f749-46a6-a08a-1237324d0c4f)

***
 
The following diagram illustrates the process of inferring entities from the EMMO ontologies.
PhysicalProcess is extended directly to the Additive Manufacturing Process in the MX3D use case.
Continuum is extended with an interface to the products e.g., I-Section and Truss Nodes in the MX3D use case.
![image](https://github.com/ahmad-delforouzi/OntoPio/assets/81425722/c78ba2f0-2a68-4ee3-a46e-3e5ff91f08ce)

![image](https://github.com/ahmad-delforouzi/OntoPio/assets/81425722/c9857ac4-ef2b-4fe9-9418-10667926f80d)

