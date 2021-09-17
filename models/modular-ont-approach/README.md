# Modular Ontology Refinement
Kansas State University (TSU) and NIST have created an OWL model for supply chain traceability of grain. Development of the modules was a collaborative effort and was carried out using the principles laid out in, e.g., [Krisnadhi and Hitzler, 2016, Shimizu et al., 2020]. The modeling team included domain experts, data experts, software developers, and ontology engineers. The (partial) ontology constituted by these modules has, in particular, been developed as a modular ontology [Hitzler et al., 2017, Hitzler and Shimizu, 2018] based on ontology design patterns [Hitzler et al., 2016, Shimizu et al., 2019b].  
## Key aspects of the ontology
### Events and TRUs
The infographic below gives a general overview of the types of data and entities that may relate to a CTE (or simple Event). The values for nodes like “TimeData” and “QuantityofStuff (TRU)” would be KDEs. In this model, Traceable Resource Units (TRUs) represent the product that is being tracked, e.g., grain. The relationship between the nodes “QuantityofStuff (TRU)” and “Container (Car, Truck)” illustrates that the TRU is contained in the container. As you can see, this relationship constitutes only some of the KDEs that are important in this model.

![CTE2](https://user-images.githubusercontent.com/78493839/121057872-be2f0200-c78d-11eb-8ff4-f083f8e1bfcc.png)

### Transfer Event
A Transfer Event is an event (or CTE) in which all or a portion of the material (the subject of the event) in a container is moved from the source container to a destination container. For example, a Transfer Event could be the movement of grain from a field to a harvester’s grain tank. Note that a container doesn’t have to be a physical container; in the example above, both the field and harvester’s tank are considered containers in this model. Transfer Events are key because they allow the lifecycle of a product to be understood via a set of Transfer Events. 

For example, the infographic below outlines a Transfer Event. You see the relationship among the Event (CTE), TRU, and Container. The “ContainedInRelation” node allows us to track which containers were used, the manner they were used in, and what they held. 

![Transfer Event](https://user-images.githubusercontent.com/78493839/121057966-db63d080-c78d-11eb-97a0-11f47f52be5c.jpg)

### Interactions among notions
Finally, the following infographic lays out the relationship among the TRU, Container, and Event (or CTE) notions.

![TRU-Container](https://user-images.githubusercontent.com/78493839/121057990-df8fee00-c78d-11eb-99d6-5cdff8197e7e.jpg)
## Loading the ontology
The ontology can be loaded into any ontology editor that can read OWL rdf/xml files.  The open source [Protégé](https://protege.stanford.edu) editor from Stanford University is one example. The ontology is self-contained and requires no other OWL modules in order to view or use it.
## Licensing
Contents of this directory were developed by Kansas State University and the National Institute of Standards and Technology. Refer to the LICENSE.txt file in this directory for terms of use of this content.
## Citations
* [Hitzler et al., 2016] Hitzler, P., Gangemi, A., Janowicz, K., Krisnadhi, A., and Presutti, V., editors (2016). [Ontology Engineering with Ontology Design Patterns - Foundations and Applications],volume 25 of Studies on the Semantic Web. IOS Press.  
* [Hitzler et al., 2017] Hitzler, P., Gangemi, A., Janowicz, K., Krisnadhi, A. A., and Presutti, V. (2017). Towards a simple but useful ontology design pattern representation language. In Blomqvist, E., Corcho,  ., Horridge, M., Carral, D., and Hoekstra, R., editors, Proceedings of the 8thWorkshop on Ontology Design and Patterns (WOP 2017) co-located with the 16th International Semantic Web Conference (ISWC 2017), Vienna, Austria, October 21, 2017., volume 2043 of CEUR Workshop Proceedings. CEUR-WS.org.  
* [Hitzler and Shimizu, 2018] Hitzler, P. and Shimizu, C. (2018). Modular ontologies as a bridge between human conceptualization and data. In Chapman, P., Endres, D., and Pernelle, N., editors, Graph-Based Representation and Reasoning – 23rd International Conference on Conceptual Structures, ICCS 2018, Edinburgh, UK, June 20-22, 2018, Proceedings, volume 10872 of Lecture Notes in Computer Science, pages 3–6. Springer.  
* [Krisnadhi and Hitzler, 2016] Krisnadhi, A. and Hitzler, P. (2016). Modeling with ontology design patterns: Chess games as a worked example. In Hitzler, P., Gangemi, A., Janowicz, K., Krisnadhi, A., and Presutti, V., editors, Ontology Engineering with Ontology Design Patterns – Foundations and Applications, volume 25 of Studies on the Semantic Web, pages 3–21. IOS Press.  
* [Shimizu et al., 2019b] Shimizu, C., Hirt, Q., and Hitzler, P. (2019b). MODL: A modular ontology design library. In Janowicz, K., Krisnadhi, A. A., Villal n, M. P., Hammar, K., and Shimizu, C., editors, Proceedings of the 10th Workshop on Ontology Design and Patterns (WOP 2019) co-located with 18th International Semantic Web Conference (ISWC 2019), Auckland, New Zealand, October 27, 2019, volume 2459 of CEUR Workshop Proceedings, pages 47–58. CEUR-WS.org.  
* [Shimizu et al., 2020] Shimizu, C., Hitzler, P., Hirt, Q., Rehberger, D., Estrecha, S. G., Foley, C., Sheill, A. M., Hawthorne, W., Mixter, J., Watrall, E., Carty, R., and Tarr, D. (2020). The enslaved ontology: Peoples of the historic slave trade. Journal of Web Semantics, 63:100567.  
## Contacts
[Evan A. Wallace](https://www.nist.gov/people/evan-k-wallace) (NIST) - POC  
## Folder Status
This GitHub repository folder is currently under construction and does not yet contain all of the content generated by the project.  Contents found within are also still undergoing revision.
