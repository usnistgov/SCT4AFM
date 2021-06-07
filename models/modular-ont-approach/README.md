# Modular Ontology Refinement

## Events and TRUs
The infographic below gives a general overview of the types of data and entities that may relate to a CTE (or simple Event). The values for nodes like “TimeData” and “QuantityofStuff (TRU)” would be KDEs. In this model, Traceable Resource Units (TRUs) represent the product that is being tracked, e.g., grain. The relationship between the nodes “QuantityofStuff (TRU)” and “Container (Car, Truck)” illustrates that the TRU is contained in the container. As you can see, this relationship constitutes only some of the KDEs that are important in this model.

![CTE2](https://user-images.githubusercontent.com/78493839/121057872-be2f0200-c78d-11eb-8ff4-f083f8e1bfcc.png)

## Transfer Event
A Transfer Event is an event (or CTE) in which all or a portion of the material (the subject of the event) in a container is moved from the source container to a destination container. For example, a Transfer Event could be the movement of grain from a field to a harvester’s grain tank. Note that a container doesn’t have to be a physical container; in the example above, both the field and harvester’s tank are considered containers in this model. Transfer Events are key because they allow the lifecycle of a product to be understood via a set of Transfer Events. 

For example, the infographic below outlines a Transfer Event. You see the relationship among the Event (CTE), TRU, and Container. The “ContainedInRelation” node allows us to track which containers were used, the manner they were used in, and what they held. 

![Transfer Event](https://user-images.githubusercontent.com/78493839/121057966-db63d080-c78d-11eb-97a0-11f47f52be5c.jpg)

## Interactions among notions
Finally, the following infographic lays out the relationship among the TRU, Container, and Event (or CTE) notions.

![TRU-Container](https://user-images.githubusercontent.com/78493839/121057990-df8fee00-c78d-11eb-99d6-5cdff8197e7e.jpg)
