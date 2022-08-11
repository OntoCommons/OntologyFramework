
# NEW CONCEPT _name_<sup>[1](#1)</sup>

_(use the preferred label, or IRI name, provided in the first table as title)_

### General Concept Info:

| **IRI:** | _Suggested entity new IRI._ |
| --- | --- |
| **OWL Type:** | _Class|ObjectProperty|Individual._ |
| **Concept Elucidation:** | _Natural language definition of the concept (elucidation). Here the concept that we want to introduce is expressed as precisely as possible, making references to knowledge domain resources, including instance and usage examples when relevant._ |
| **Labels:** | _Labels used to address the concept, ordered as: i) preferred (one) (the label to primarily used to shortly refer to the concept) ii) alternative (multiple) (labels that are commonly used to address the concept in practice, even if they are used with narrower of wider sense) iii) deprecated (multiple) (labels that are misleading with respect to the concept, because of misuse, ambiguity or too wide meaning)._ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _Existing domain resources (e.g. standards, books, articles, dictionaries) that defines or are related to the concept (provide reference to the resource and quote the relevant informational content). More than one resource can be reported. These resources are aimed to support the choice of the above concept choice and elucidation._ |
| **Comments:** | _Explain the motivations behind the concept definition with reference to the domain resources, underlying similarities and differences._ |

### Alignments To Existing Ontologies:

|     |     |
| --- | --- |
| **Target Ontology:** | _Existing IRI of the ontology that will express the concept according to its logical framework (concept alignment)._ |
| **Related Ontology Entities:** | _List of terms and IRIs of the Target Ontology entities that are relevant for the concept (documentation is supposed to be accessible through the target ontology)._ |
| **Mapping Elucidation:** | _Natural language description of the mapping choice and motivations._ |
| **Semantic Relation Level:** | _The level of semantic relationship between the Concept and the Target Ontology entities: (one of) i) Equivalence (strong mapping) (e.g. owl:equivalentClass, owl:equivalentProperty), ii) Strong Hierarchical (e.g. rdfs:subClassOf, rdfs:subPropertyOf), iii) Weak Hierarchical (e.g. skos:narrower, skos:broader), iii) Similarity (e.g. skos:related)._ |
| **Mapping Axioms:** | _Proposed mapping axiom (or axioms) between the Concept entity and the Target Ontology entities in a OWL2 compliant syntax (e.g. Turtle, Manchester, RDF/XML, Functional-Style, OWL/XML)._ |

## EXISTENT CONCEPT _name_ <sup>[2](#2)</sup>

_(use the preferred label, or IRI name, provided in the first table as title)_

### General Concept Info:

| **IRI:** | _Entity IRI_ |
| --- | --- |
| **OWL Type:** | _Class|ObjectProperty|Individual_ |
| **Concept Elucidation:** | _Refer to ontology annotations or other existing OFFICIAL documentation that defines the concept in natural language._ |
| **Labels:** | _Labels (e.g. rdfs:label) used to address the concept, ordered as i) preferred (one), ii) alternative, iii) deprecated._ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _Existing domain resources (e.g. standards, books, articles, dictionaries) that define or are related to the elucidated concept, specifying if they are explicitly mentioned in the ontology documentation._ _Provide reference to the resource and quote the relevant informational content._ _More than one resource can be reported._ |
| **Comments:** | _Explain the similarities and differences between the concept definition and the domain resources, underlying similarities and differences._ |

## Alignments To Existing Ontologies:

| **Target Ontology:** | _Ontology IRI_ |
| --- | --- |
| **Related Ontology Entities:** | _Term and IRI of the Target Ontology entity_. |
| **Mapping Elucidation:** | _Natural language description of the mapping choice and motivations. 
| **Semantic Relation Level:** | _The level of semantic relationship between the Concept and the Target Ontology entities: (one of) i) Equivalence (strong mapping) (e.g. owl:equivalentClass, owl:equivalentProperty), ii) Strong Hierarchical (e.g. rdfs:subClassOf, rdfs:subPropertyOf) ii) Weak Hierarchical (e.g. skos:narrower, skos:broader) Similarity (e.g. skos:related)_ |
| **Mapping Axioms:** | _Proposed mapping axiom (or axioms) between the Concept entity and the Target Ontology entities in a OWL2 compliant syntax (e.g. Turtle, Manchester, RDF/XML, Functional-Style, OWL/XML)._ |

<a name="1">1</a>: _This template can be used to build META concepts (e.g. based on the list of MLO concepts provided by Arko) documenting their semantic relation and formal alignment (using OWL-DL) with TLOs._

<a name="2">2</a> _This template can be used to align existing MLOs to the TLOs/META documenting their semantic relation and formal alignment (using OWL-DL)._
