# Folder for Semantic Traceability Models

This project investigated two different approaches for defining ontologies (i.e. semantic models) for Critical Tracking Events (CTEs) and Key Data Elements (KDEs) (see below), which are the key notions related to traceability for food. The two approaches were:

1. *Upper Ontology Extension* ([upper-ont-approach](https://github.com/usnistgov/SCT4AFM/tree/master/models/upper-ont-approach)): We extend the Basic Formal Ontology (BFO), an upper ontology, using the principles of the Industrial Ontology Foundry. The resulting model focuses on specific scenarios/use cases involving grain supply chains that domain experts have highlighted; it incrementally develops and then uses a traceability model to address domain user needs.
2. *Modular Ontology Refinement* ([modular-ont-approach](https://github.com/usnistgov/SCT4AFM/tree/master/models/modular-ont-approach)): This approach uses modular modeling to develop a rich ontology for full end-to-end traceability of grain supply chains. Stay tuned for a model based on this approach.

The Upper Ontology Extension approach was developed by teams from the [Engineering Informatics Research Group (INFONEER)](https://infoneer.wp.txstate.edu/) at Texas State University and the [NIST Supply Chain Traceability (SCT4AFM) project](https://www.nist.gov/programs-projects/supply-chain-traceability-agri-food-manufacturing). 

The Modular Ontology Refinement approach was led by a team from the [Data Semantics Laboratory (DaSe Lab)](https://daselab.cs.ksu.edu/) at Kansas State University. The associated model was developed by the DaSe Lab in collaboration with the [NIST SCT4FM project](https://www.nist.gov/programs-projects/supply-chain-traceability-agri-food-manufacturing) members, the principal investigator from the Texas State University team, and domain experts involved in traceability projects at the [AgGateway standards consortium](https://www.aggateway.org/) supporting digital connectivity in global agriculture.

The models developed from both cases were seeded with CTE and KDE notions developed in prior research from the NIST SCT4AFM project. In each case, ontologies were created in the [Web Ontology Language (OWL)](https://www.w3.org/TR/2012/REC-owl2-overview-20121211/), a World Wide Web Consortium (W3C) standard logic language. Subfolders have been created in this repository for artifacts from each of these approaches.

## *Critical Tracking Events* and *Key Data Elements*

Our ontologies formally represent Critical Tracking Events (CTEs) and their associated Key Data Elements (KDEs). A CTE is an important occasion in a product’s life cycle, such as a receiving, transferring, transforming, packing, shipping, and transporting event. CTEs are associated with KDEs, which describe the type of data that should be collected at each CTE. These factors are important for improving traceability because KDEs can be compiled to illustrate a product’s history, allowing that product to be better tracked across its life cycle and the supply chains that it is part of.

## Folder Status
This site is still in the process of being built, so some subparts of this folder and its expected contents are likely not present yet.  The models themselves are research outputs and are likely to continue to evolve.
