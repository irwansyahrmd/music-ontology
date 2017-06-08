# Music Ontology

![owlviz](https://user-images.githubusercontent.com/5053232/26954668-8471973e-4cdb-11e7-83e8-fd245345c7a4.png)
![img](https://user-images.githubusercontent.com/5053232/26954672-87917b96-4cdb-11e7-88f2-be9c32c027ef.png)

# SPARKL Query
Examples : 
 1. PREFIX owl: <http://www.w3.org/2002/07/owl#>
    PREFIX mo: <http://www.semanticweb.org/irwansyah/ontologies/2015/4/MusicOntology#>
    SELECT ?superclass
    WHERE { mo:Artist rdfs:subClassOf ?superclass . }
 2. PREFIX owl: <http://www.w3.org/2002/07/owl#>
    PREFIX mo: <http://www.semanticweb.org/irwansyah/ontologies/2015/4/MusicOntology#>
    SELECT ?subclass
    WHERE { ?subclass rdfs:subClassOf mo:Person . }
 3. PREFIX owl: <http://www.w3.org/2002/07/owl#>
    SELECT ?subject ?object
    WHERE { ?subject rdfs:subClassOf ?object }
