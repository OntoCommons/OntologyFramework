# PHYSICAL QUANTITY

### **General Concept Info:**

| **IRI:** | _Suggested entity new IRI._ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | Physical Quantities are properties associated with a physical entity (_qua_ physical) for which there is a standardized definition capable of supporting quantification, and which can either be observed under practically achievable experimental conditions or predicted by means of a theoretical model apt to generalize observations. It should be noted that Physical Quantities need not necessarily pertain to the domain of physics, understood as a discipline. <br> <br> Domain: Natural sciences - Metrology. |
| **Labels:** | skos:prefLabel: _Physical Quantity_ <br><br> _skos:altLabel: Physical Property; Quantity_ <br><br> _skos:hiddenLabel: Property; Physical Quality; Physical Characteristic; Quality_ |

### **Knowledge Domain Resources:**

|     |     |
| --- | --- |
| **Related Domain Resources:** | _-Wikipedia:_ "a physical quantity is a physical property of a material or system that can be quantified by measurement. A physical quantity can be expressed as a value, which is the algebraic multiplication of a numerical value and a unit".-_WikiData:_ "quantitative characterisation of an aspect of a physical entity, phenomenon, event, process, transformation, relation, system, or substance" (Q107715).-_VIM (3__rd_ _edition):_ "property of a phenomenon, body, or substance, to which a number can be assigned with respect to a reference".-_ISO 80000-1/12_ provides a general characterisation and an extensional definition of quantities, though it is explicitly stated that "systems of quantities and systems of units can be treated in many consistent, but different, ways. Which treatment to use is only a matter of convention" and that "the quantities and the relations among them are essentially infinite in number and are continually evolving as new fields of science and technology are developed. Thus, it is not possible to list all these quantities and relations in this International Standard; instead, a selection of the more commonly used quantities and the relations among them is presented".-_ISO 10303-45:_ "a type of property of a product where the meaning and value of the property depend on the method and conditions by which it was measured"; "material properties are representative of all engineering properties that are defined by a specified testing method [whereas] an engineering property characterises some aspect of the behaviour of a product"; "The following are the fundamental concepts and assumptions related to the representation of engineering properties: <br> - multiple representations of a property are possible including the use of numeric values, parametric or fundamental equations, graphical representations and non-numeric values (NOTE The distinction between a concept and the representation of a concept is described in ISO 10303-43); <br> - the value of a property may be assigned or measured; <br> - if the value is measured, the resulting value will depend on the method of measurement and on the conditions used in applying the method; <br> - if the value is assigned, the conditions under which that assignment is valid may be specified; <br> - in the case of either assignment or measurement, the conditions under which the value is valid are expressed as a set of quantitative and qualitative data which form the data environment".|
| **Comments:** | _This engineered OntoCommons bridge-concept aims to provide a MLO-friendly, pragmatic restriction of an extremely general family of notions which can be characterised in vastly different ways; notions which generally fall under the labels of 'property', 'attribute', 'quality', 'characteristic', 'quantity'. Given the aim, the characteristics of the target MLOs, and, more importantly, the requests coming from MLOs' stakeholders given OntoCommons' survey, it was decided to focus on a list of features encompassing property quantification, the existence of a standardised and shared definition/procedure ensuring objectivity, and the relevant aspects being grounded -directly or indirectly- in actual, and not just possible (to restrict the number of problematic cases by avoiding merely hypothetical ones), observability._ <br> _There was an effort to ensure that the proposed bridge-concept would be aligned with golden standards: specifically, it is in line with ISO 80000, which also provides a (nominally partial, yet extremely rich) extensional definition of the class; it is also aligned with ISO10303-45, though we ultimately decided to explicitly include quantities associated with physical objects which do not pertain to the domain of physics, understood as discipline, to ensure coverage of all the relevant MLOs, in line with our goals. Doing so also avoids some well-known issues related to demarcation problems. Notably, the resulting definition is compatible with the ones provided by well known and pervasively employed domain resources, such as Wikipedia, Wikidata, and another golden standard, the International Vocabulary of Metrology. This will ensure immediateness and intuitiveness for domain experts and ontologists, while at the same time improving the usability for non-experts. The risk of meaning/conceptual shift, and thus, obsoleteness, is also reduced. That said, the proposed definition cannot be reduced to said resources, insofar as it attempts to go beyond them explicitly pointing at possible pitfalls and nuances that need to be considered when attempting an alignment._ |

## **Alignments To Existing Ontologies:**

|     |     |
| --- | --- |
| **Target Ontology:** | BFO: _<http://purl.obolibrary.org/obo/bfo.owl>_ |
| **Related Ontology Entities:** | _Quality: <http://purl.obolibrary.org/obo/BFO\_0000019>_ |
| **Mapping Elucidation:** | _Arguably, BFO's Specifically Dependent Continuants cover the vast majority of the entities commonly labelled as 'properties' etc. -in line with what has been said above- in the guise of a metaphysical commitment to tropes. The ones which are not covered might be seen as falling under Generically Dependent Continuant, yet said class does not seem to be appropriate as an alignment target. BFO's Role class is likewise not a good candidate, since they explicitly do not cover properties whose possession has consequences for the physical make-up of the bearer. As such, the only options left are Disposition and Quality. Given the focus on the observation process outlined in the proposed definition of Physical Quantity, it might be tempting to connect the latter to a specific kind of BFO:Disposition, yet that would mean vastly disregarding BFO's background philosophical assumptions, internal organization, and factual approach to the description of similar cases. Taking those into account the proper connection is arguably with BFO:Quality. The Quality class is not restricted to quantities, nor bound by actual-observation grounding or the possibility of supporting quantification; as such the proposed OntoCommons bridge-concept, Physical Quantity, can only be a subclass of the former._ |
| **Semantic Relation Level:** | rdfs:subClassOf |
| **Mapping Axioms:** | _TBD_ |


|     |     |
| --- | --- |
| **Target Ontology:** | DOLCE: _<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic>_ |
| **Related Ontology Entities:** | _PhysicalQuality:_ _<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#PhysicalQuality>_ |
| **Mapping Elucidation:** | _In the TLO DOLCE, the class Quality arguably covers the entirety of the entities commonly labelled as 'properties' etc. -in line with what has been said above-. Analogously to BFO, DOLCE approaches properties via a commitment to tropes, though the relevant theoretical framework is fairly more complex. As such, it seems appropriate to look for a connection in the subclasses of DOLCE:Quality. The most pertinent target is arguably the class Physical Quality, which covers one of the core traits characterising the proposed bridge-concept, Physical Quantity. Since there are no explicit references to actual-observation grounding for the sake of generality, and qualities implicitly include non quantifiable properties, qua qualities, the proposed OntoCommons bridge-concept, Physical Quantity, should be considered a specification of the relevant Dolce class, and, thus, a subclass of the latter. This last point is also supported by the explicit examples of usage provided in DOLCE's documentation._ |
| **Semantic Relation Level:** | rdfs:subClassOf |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | EMMO: _<http://emmo.info/emmo>_ |
| **Related Ontology Entities:** | _QuantitativeProperty_ _<http://emmo.info/emmo#EMMO\_dd4a7f3e\_ef56\_466c\_ac1a\_d2716b5f87ec>_ |
| **Mapping Elucidation:** | _In EMMO, properties are approached from a metaphysically deflationary (even in-framework, and not as a general attitude concerning the relationship between ontology and world), applied-sciences friendly point of view. Despite belonging to the Semiotic perspective, EMMO:Quantitative Property, is perfectly in line with the OntoCommons bridge-concept definition, as the various traits characterising the latter are explicitly covered, either in the relevant elucidation or on the elucidation of its superclasses. In fact, there are extensive references to the same golden standards/domain resources (e.g., ISO 80000 and the VIM). Given that, there are good reasons to believe that the class defined by the proposed bridge-concept, Physical Quantity, is equivalent to EMMO:Quantitative Property. The linguistic labels associated with the two concepts arguably offer further support to the proposed alignment._ |
| **Semantic Relation Level:** |rdfs:equivalentClass |
| **Mapping Axioms:** | _TBD_ |


|     |     |
| --- | --- |
| **Target Ontology:** | Allotrope: <http://purl.allotrope.org/voc/afo/merged-OLS/REC/2019/05/10> |
| **Related Ontology Entities:** | _Quality:_ <http://purl.obolibrary.org/obo/BFO\_0000019> |
| **Mapping Elucidation:** | _Allotrope is based on BFO, hence sharing its treatment of the entities commonly labelled as 'properties' etc. -in line with what has been said above-. Some subclasses of Allotrope:Quality are obvious candidates as subclasses of the proposed OntoCommons bridge-concept, Physical Quantity, though the discussion of the links should be done via a case by case analysis. Given that, the most informative alignment connection, having to chose only one for the sake of demonstration, is with Quality class itself, in line with alignment with BFO proposed above._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | BMWD: <https://gitlab.cc-asp.fraunhofer.de/EMI\_datamanagement/bwmd\_ontology/-/blob/master/docs/create\_new\_domain\_ontology\_using\_BWMD\_mid.md> |
| **Related Ontology Entities:** | _QuantityKind: <https://www.materials.fraunhofer.de/ontologies/BWMD\_ontology/mid#BWMD\_00011>_ |
| **Mapping Elucidation:** | BWMD, like Allotrope, is based on BFO, hence sharing its treatment of the entities commonly labelled as 'properties' . The subclass of Quality, QuantityKind, adds an explicit requirement which covers one of the traits characterising the proposed OntoCommons bridge-concept, Physical Quantity, namely, being quantifiable. The linguistic labels wear the above point on their sleeves. As such, BWMD:QuantityKind seems to be the most informative target for a meaningful connection/alignment. Some subclasses of BWMD:QuantityKind are obvious candidates as subclasses of the proposed OntoCommons bridge-concept, Physical Quantity, however, as above, the discussion of the links should be done via a case by case analysis. It should be noted that BWMD distinguishes between the class Quantity and the class QuantityKind, and it might prima facie seem that the former is a better candidate for alignment. However, at a closer inspection, that does not seem to be the case, though some subclasses of Quantity seems eminently physical, rather than concerning the mathematical representation/modelling of single possible observations. Direct cooperation with the developers of BWMD to clarify this point is advised._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | CCO: <https://github.com/CommonCoreOntology/CommonCoreOntologies> |
| **Related Ontology Entities:** | _Quality:_ <http://purl.obolibrary.org/obo/BFO\_0000019> |
| **Mapping Elucidation:** | _The situation is analogue as in the case of the Mid Level Ontology Allotrope; as such, the same considerations can be applied, mutatis mutandis, in this case._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | IOF-Core: <https://github.com/NCOR-US/IOF-BFO> |
| **Related Ontology Entities:** | _Quality:_ _<http://purl.obolibrary.org/obo/BFO\_0000019>_ |
| **Mapping Elucidation:** | _BWMD, like some of the MLOs considered above, is based on BFO, hence sharing its treatment of the entities commonly labelled as 'properties' . Differently from them, the ontology seems to be less focused on providing a categorization of different kinds of properties: the sole subclass of Quality is, in fact, IOF-Core:Relational Quality. As such, the choice of the alignment target is even more straightforward. The considerations concerning the nature of the alignment between the proposed OntoCommons bridge-concept, Physical Quantity, and IOF-Core:Quality are analogous as in the cases of Allotrope and CCO._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | Saref: <https://saref.etsi.org/core/v3.1.1> |
| **Related Ontology Entities:** | _Property: <https://saref.etsi.org/core/Property>_ |
| **Mapping Elucidation:** | _Saref:Property is defined in terms of qualities and features, and the subclasses seem appropriate for a connection. In fact, some a good number of the subclasses of Property are good candidates as subclasses of the proposed OntoCommons bridge-concept, Physical Quantity, though not all of them. In line with what has been said in other cases, Sare:Property remains the preferable target for a meaningful and informative connection and other alignments should be considered case by case. The alternatives to Saref:Property seem less compelling/appropriate._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |

## EXISTING CONCEPT: QUALITY (BFO)

### General Concept Info:

| **IRI:** | _<http://purl.obolibrary.org/obo/BFO\_0000019>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | _A quality is a specifically dependent continuant that, in contrast to roles and dispositions, does not require any further process in order to be realized._ <br> _Examples of Usage:_ The colour of a tomato, the ambient temperature of this portion of air, the length of the circumference of your waist, the shape of your nose, the shape of your nostril, the mass of this piece of gold. |
| **Labels:** | _Quality_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _Building Ontologies with BFO:_ "specifically dependent continuant is a continuant entity that depends on one or more specific independent continuants for its existence. Dependent continuants exhibit existential dependence in the sense that, in order for a dependent continuant to exist, some other entity in which it inheres (intuitively, an entity enjoying a larger degree of concreteness) must exist also"; "there are two types of specifically dependent continuant : quality and realizable entity . Qualities are contrasted with realizables in that the former, if they inhere in an entity at all, are fully exhibited or manifested or realized in that entity. The latter, in contrast, can inhere without being realized, and can be realized to different degrees (including different degrees of likelihood). What all qualities have in common is that they inhere in, and so depend on, other entities; in order for a quality to exist some other entity or entities — specifically, one or more independent continuants, must also exist". |

## EXISTING CONCEPT: PHYSICAL QUALITY (DOLCE)

### General Concept Info:

| **IRI:** | _<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#PhysicalQuality>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | _A Physical Quality is a quality that directly inheres to a physical endurant._ <br> _Examples of Usage:_ the weight of a pen, the color of an apple. |
| **Labels:** | _PhysicalQuality_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _Dolce D18:_ "DOLCE has four top categories: endurant (including object- and substance-like entities), perdurant (event- and state-like entities), quality (individual attributes), and abstracts (mainly conceptual "regions" for structuring attributes)"; "Qualities can be seen as the basic entities we can perceive or measure: shapes, colors, sizes, sounds, smells, as well as weights, lengths, electrical charges. . . 'Quality' is often used as a synonymous of 'property', but this is not the case in DOLCE: qualities are particulars, properties are universals. Qualities inhere to entities: every entity (including qualities themselves) comes with certain qualities, which exist as long as the entity exists. Within a certain ontology, we assume that these qualities belong to a finite set of quality types (like color, size, smell, etc., corresponding to the "leaves" of the quality taxonomy shown in Figure 2), and are characteristic for (inhere in) specific individuals". |

## EXISTING CONCEPT: QUANTITATIVE PROPERTY (EMMO)

### General Concept Info:

| **IRI:** | _<http://emmo.info/emmo#EMMO\_dd4a7f3e\_ef56\_466c\_ac1a\_d2716b5f87ec>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A 'Quantity' that can be quantified with respect to a standardized reference physical instance (e.g. the prototype meter bar, the kg prototype) or method (e.g. resilience) through a measurement process. <br> "A property of a phenomenon, body, or substance, where the property has a magnitude that can be expressed by means of a number and a reference"ISO 80000-1 <br> "A reference can be a measurement unit, a measurement procedure, a reference material, or a combination of such."International vocabulary of metrology (VIM) <br> Subclasses of 'QuantitativeProperty' classify objects according to the type semiosis that is used to connect the property to the object (e.g. by measurement, by convention, by modelling). |
| **Labels:** | _QuantitativeProperty_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _European Materials Modelling Ontology v. 1.0.0 alpha 2:_ "a quantitative property is always expresssed as a quantity (i.e. a number and a reference unit). For the EMMO, a nominalistic ontology, there is no property as abstract object"; "a property is a sign that stands for an object according to a specific code shared by some observers"; "for quantitative properties, one possible code that is shared between the scientific community (the observers) is the SI system of units". |

## EXISTING CONCEPT: QUALITY (Allotrope)

### General Concept Info:

| **IRI:** | _<http://purl.obolibrary.org/obo/BFO\_0000019>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A quality is a specifically dependent continuant that, in contrast to roles and dispositions, does not require any further process in order to be realized. [BFO] <br> <http://purl.allotrope.org/voc/bfo/REC/2018/04/bfo-2-0> <br> <http://purl.obolibrary.org/obo/bfo.owl> <br> _Examples of Usage__:_ the ambient temperature of this portion of air, the colour of a tomato, the length of the circumference of your waist, the mass of this piece of gold, the shape of your nose, the shape of your nostril. |
| **Labels:** | _Quality_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No Instances._ |

## EXISTING CONCEPT: QUANTITY KIND (BMWD)

### General Concept Info:

| **IRI:** | _<https://www.materials.fraunhofer.de/ontologies/BWMD\_ontology/mid#BWMD\_00011>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | _A quantity kind in analogy to the QUDT ontology described by http://www.qudt.org |
| **Labels:** | _QuantityKind_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No instances._ |

## EXISTING CONCEPT: QUALITY (CCO)

### General Concept Info:

| **IRI:** | <http://purl.obolibrary.org/obo/BFO\_0000019> |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A quality is a specifically dependent continuant that, in contrast to roles and dispositions, does not require any further process in order to be realized. (axiom label in BFO2 Reference: [055-001]) <br> <http://purl.obolibrary.org/obo/bfo.owl> <br> _Examples of Usage__:_ the ambient temperature of this portion of air, the colour of a tomato, the length of the circumference of your waist, the mass of this piece of gold, the shape of your nose, the shape of your nostril. |
| **Labels:** | _Quality_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No Instances._ |

## EXISTING CONCEPT: QUALITY (IOF-Core)

### General Concept Info:

| **IRI:** | _<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#PhysicalQuality>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A quality is a specifically dependent continuant that, in contrast to roles and dispositions, does not require any further process in order to be realized. <br> _Examples of Usage:_ the colour of a tomato, the ambient temperature of this portion of air, the length of the circumference of your waist, the shape of your nose, the shape of your nostril, the mass of this piece of gold. |
| **Labels:** | _Quality_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No Instances._ |

## EXISTING CONCEPT: PROPERTY (Saref)

### General Concept Info:

| **IRI:** | _<https://saref.etsi.org/core/Property>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A quality of a feature of interest that can be measured; an aspect of a feature of interest that is intrinsic to and cannot exist without the feature. |
| **Labels:** | _Property_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No instances._ |
