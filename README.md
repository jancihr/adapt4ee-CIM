adapt4ee-CIM
============

**adapt4ee-CIM** (**Common Information Model**) is the OWL2 ontology and XML data format designed for modeling of the building environments. Model consists from the following main parts:
-	building model based on gbXML standard
-	business process model
-	events observed in the building (low-level measured evens such as energy consumption or higher-level events such as device usage, space occupancy, etc.)
-	key performance indicators (e.g. total energy consumption, usage time)
-	external environment of the building (e.g. location, average weather conditions)

The owl directory contains the OWL2 ontology (adapt4eeCIM.n3 file) and exemple data in RDF format. The xsd directory contains the XML Schema specification files and example data in XML format.

The ontology was developed within the [adapt4ee](http://www.adapt4ee.eu/) European project.

The model is supplemented by [adapt4ee-CIMIM](https://github.com/jancihr/adapt4ee-CIMIM) services, which provide the reference implementation of the storage, inference and query functions for RDF and XML data.
