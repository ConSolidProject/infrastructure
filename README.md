# ConSolid software stack
This repository contains references to the different repositories used in the ConSolid project. 

* The directory "api" contains the two low-level APIs to interact with the ecosystem's data patterns, i.e the Dataset Aggregation Api (`npm i consolid-daapi`) and the Reference Aggregation Api (`npm i consolid-raapi`).
* The directory "vocabulary" contains the ConSolid vocabulary, registered at `https://w3id.org/consolid`.
* The directory "system" contains a prototype for the modified Solid Community Server, which mirrors its RDF resources to a SPARQL endpoint (Apache Fuseki). It also contains a prototype for an access control wrapper around this SPARQL endpoint. 
* The directory "consolid_demo" contains some demo scripts to evaluate the following data patterns, using the IP-free BIM Duplex model. Follow the instructions in the corresponding README to set up a local prototype of the ConSolid ecosystem. The demo contains instructions for running the setup with or without the SPARQL access control wrapper, with the former being more experimental.

The repository was created in context of [a submission to Semantic Web Journal](https://www.semantic-web-journal.net/content/consolid-federated-ecosystem-heterogeneous-multi-stakeholder-projects)