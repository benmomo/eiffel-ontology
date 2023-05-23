EIFFEL Ontology (EIFF-O)
===

Ontology developed inside the [EIFFEL project](https://www.eiffel4climate.eu/). EIFFEL has been financed by the EU Horizon 2020 research and innovation programme under Grant Agreement No 101003518

The ontology covers the Climate Change domain, considering:

- *ECV domain*: information related to [Essential Climate Variables](https://gcos.wmo.int/en/essential-climate-variables) and the taxonomy defined by the Global Climate Observing System (GCOS).

- *SDG domain*: information related to the [Sustainable Development Goals](http://metadata.un.org/sdg/ontology?lang=es) and related [ontolgies](https://github.com/UNStats/LOD4Stats/wiki/SDG-Knowledge-Organization-System) . 

- *EO taxonomy*: taxonomy specified by [EASRC](https://earsc-portal.eu/display/EOwiki/EO+Taxonomy) considering both the user (market) and provider (thematic) perspectives of the Earch Observation (EO) domain 

- *schema.org domain*: in order to reach a wide audience and allow for [Google Dataset](https://developers.google.com/search/docs/advanced/structured-data/dataset) indexing, some classes from [shema.org](https://schema.org/) have been used and extended.

The EIFFEL ontology (EIFFO) defines individual ontologies for the previous domains where the taxonomy were specified but not implemented and a wrapper ontology to link them together. 

The ontology also includes a permanent URI: [https://purl.org/eiffo](https://purl.org/eiffo)



Usage and Documentation
===


The **ontology** folder includes all the ontologies as TTL files. For the EO and ECV ontologies, there is a simple ontology file (no individuals) and a knowledge base file (with individuals). There might be updated as the EIFFEL project evolves.


Besides the ontologies, there is a **set of tools** including a visual viewer, a REST API and a SPARQL interface. They have been implemented as Docker containers and are publicly available in DockerHub. The **docker** folder includes a docker-compose file that shows a basic usage of the whole set. You might test it in your own computer.
*Note: The given docker-compose file is basic and should be improved for production environments (e.g., mounting volumes to change configuration, persist logs and databases)

More information can be found in [readthedocs](https://eiffel-ontology-doc.readthedocs.io/en/latest/) 


License
===

The EIFFO ontology and the set of tools are distributed through [Apache2](https://www.apache.org/licenses/LICENSE-2.0) license.

The EO ontology and the ECV ontology are distributed as [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license.



Contacts
===

Benjamin Molina <benmomo@upvnet.upv.es>
