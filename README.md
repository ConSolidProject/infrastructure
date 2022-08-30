# ConSolid software stack
This repository contains references to the different repositories used in the ConSolid project. 

* The directory "api" contains the two low-level APIs to interact with the ecosystem's data patterns, i.e the Dataset Aggregation Api (`npm i consolid_daapi`) and the Reference Aggregation Api (`npm i consolid_raapi`).
* The directory "vocabulary" contains the ConSolid vocabulary, registered at `https://w3id.org/consolid`.
* The directory "system" contains a prototype for the modified Solid Community Server, which mirrors its RDF resources to a SPARQL endpoint (Apache Fuseki).
* The directory "consolid_demo" contains some demo scripts to evaluate the following data patterns, using the IP-free BIM Duplex model:
  * create accounts
  * create project
  * create alignment
  * aggregate
  * register crack (damage assessment documentation)

The repository was created in context of [a submission to Semantic Web Journal]()