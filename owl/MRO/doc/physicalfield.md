# **PHYSICAL FIELD**

### **General Concept Info:**

| **IRI:** | _Suggested entity new IRI._ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A Physical Field is a physical entity which involves a region of spacetime and a physical quantity, potentially representable by means of mathematical objects, yet not reducible to the latter. A Physical Field can be understood as a region in which each point has a physical quantity associated with it. Depending on background assumptions, Physical Fields can be characterised as mediators of interactions, aggregate effects of interactions, or as that which makes up the posited interacting objects, which are then reinterpreted, e.g., as excitations of the field. It should be noted that the region involved in the characterisation of a given field might either contain massive entities or not; yet they need to contain (at least potential) energy, which distinguishes Physical Fields from classical true vacuum. Physical Fields should not confused with mathematical fields (which are mathematical objects, and, specifically, algebraic structures which can be formally defined via a model theoretical approach), nor with representations/models of Physical Fields which employ mathematical fields. <br><br> Domain: Natural Sciences - Physics (typically) |
| **Labels:** | __skos:prefLabel: Physical Field__ <br><br> __skos:altLabel: Field__ <br><br> __skos:hiddenLabel: Quantum Field; Quantity Distribution__ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _-Wikipedia:_ "in physics, a field is a physical quantity, represented by a number or another tensor, that has a value for each point in space and time"._-Encyclopedia Britannica:_ "a region in which each point has a physical quantity associated with it. The quantity could be a number, as in the case of a scalar field such as the Higgs field, or it could be a vector, as in the case of fields such as the gravitational field, which are associated with a force".-_WikiData:_ "common physics term for a physical quantity, represented by a number or tensor, that has a value for each point in space-time" (Q185674). |
| **Comments:** | _This engineered OntoCommons bridge-concept aims to provide a general and unambiguous definition of field, pragmatically useful for MLOs. Given the intrinsic domain-heterogeneity of Mid Level Ontologies, it was decided that the proposed bridge-concept should encompass both classical and quantum fields; on the other hand, it has come to our attention that representational, mathematical, and physical characterisations of fields are easily confused, leading to category-mistakes which, on the one hand, might compromise an ontology's stand-alone rigorousness and clarity, and, on the other hand, are bound to be problematic when alignments are concerned, endangering interoperability. The proposed bridge-concept is characterised by relatively simple traits, and the most notable question which might arise in categorization are tackled explicitly. Nonetheless, the definition is in line with the ones provided by well-known and commonly employed domain resources, such as Wikipedia, Wikidata, and authoritative encyclopedias, such as the Encyclopedia Britannica. The final proposal has also been evaluated and emended by a team of domain experts, to ensure domain-appropriateness/correctness._ |

## Alignments To Existing Ontologies:

|     |     |
| --- | --- |
| **Target Ontology:** | BFO: _<http://purl.obolibrary.org/obo/bfo.owl>_ |
| **Related Ontology Entities:** | _ImmaterialEntity: <http://purl.obolibrary.org/obo/BFO\_0000141>_ |
| **Mapping Elucidation:** | _Physical Fields can arguably be conceptualized in different and ontologically incompatible ways, depending on which aspects are privileged/highlighted. If the focus is on the involved region, BFO:Independent Continuant seems the right place to look for a connection; however -as it has been said- it is not out and out incorrect to think of fields as distributions of physical quantities over a topological space. In fact, it is not unfair to suppose that BFO would represent a scenario involving a (physical) field by employing a Spatial Region and some Specifically Dependent Continuants. However, this is a semantic alignment which won't be considered here. It might nonetheless be possible to preserve the general idea by proposing an alignment with BFO:Immaterial Entity and, specifically, with the union of BFO:Site and BFO:Continuant Fiat Boundary. In fact, the view according to which fields are more or less derivative is perfectly consistent with the informal characterisation of the two BFO classes, whose instances are not detachable and demarcated in relation to other entities. Further evidence favouring this claim can be found by means of holistic comparison with the classes Material Entity and Spatial Region. Moreover, BFO's Immaterial Entities, differently from BFO's Material Entities needn't have material parts, in line with the characterisation of the OntoCommons bridge-concept Physical Field provided above. Thus, the proposed connection seems prima facie appropriate, and arguably informative: Physical Fields are a subclass of the disjoint union of BFO:Site and BFO:Continuant Fiat Boundary for which further constraints relative to the inherent BFO:Specific Dependent Continuant hold._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |


|     |     |
| --- | --- |
| **Target Ontology:** | DOLCE: _<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic>_ |
| **Related Ontology Entities:** | _Feature: <http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#Feature>_ |
| **Mapping Elucidation:** | _DOLCE's classes Physical Endurant and Non-Physical Endurant are disjoint: that seemingly poses an immediate problem given the definition of the provided OntoCommons bridge-concept Physical Field. However, the distinction revolves around the possess of spatial qualities, which fields, as they have been defined, have as a characterising trait. Now, since only DOLCE's Phyical Objects must be constituted by Amounts of Matter, there seem to be no viable candidate but DOLCE:Feature for a meaningful connection. Thankfully, it the same result is achieved by following a route analogous to the one underlying the alignment proposed for BFO: in fact, DOLCE's Features are defined as parasitic entities which are dependent on other physical entities and exhibit topological unity. Interestingly, the examples of usage seem to support this connection, insofar as entities which are not part of their "host", such as the front of a house, are allowed. Physical Fields can be thus understood as a subclass of DOLCE:Feature, having a certain Physical Quality (trope) belonging to a certain type for each of their points._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |


|     |     |
| --- | --- |
| **Target Ontology:** | EMMO: _<http://emmo.info/emmo>_ |
| **Related Ontology Entities:** | _Field: <http://emmo.info/emmo#EMMO\_70dac51e\_bddd\_48c2\_8a98\_7d8395e91fc2>_ |
| **Mapping Elucidation:** | _EMMO:Field seems to be the perfect candidate for a meaningful and informative alignment with the OntoCommons bridge-concept Physical Field, with no real contenders. EMMO:Field belongs -in line with expectations- to the physicalistic perspective; the concept is explicitly characterised alongside Matter and Vacuum referring to state-of-the-art quantum mechanics. Given that, the only question left to ask pertains to the kind of connection holding between the bridge-concept and EMMO's Field. In line with what has been said above in the comment to the elucidation, EMMO:Field might prima facie appear to be a subclass of Physical Field; a straightforward consequence as a domain (discipline) restriction. However, that would mean ignoring EMMO's reductionist framework: given the pertinent background ontologico-metaphysical assumption, the most appropriate alignment is that of class-equivalence. It is worth noting that all the other traits are preserved, and -given the distinction of different perspective- the disambiguation of the concept of field is assured._ |
| **Semantic Relation Level:** | _rdfs:equivalentClass_ |
| **Mapping Axioms:** | _TBD_ |


|     |     |
| --- | --- |
| **Target Ontology:** | Domain Mechanical Testing (EMMO-MECH-TEST): <http://emmo.info/emmo/domain/mechanical-testing>_ |
| **Related Ontology Entities:** | _Field: <http://emmo.info/emmo#EMMO\_70dac51e\_bddd\_48c2\_8a98\_7d8395e91fc2>_ |
| **Mapping Elucidation:** | _The Domain Mechanical Testing ontology EMMO-MECH-TEST is based on EMMO; as such what has been said above can be applied mutatis mutandis in this case. Given the proposed semantic link, the absence of better candidates should come as no surprise. However, it should be noted that EMMO-MECH-TEST is based on an outdated version of EMMO, and that partially shows in the relevant elucidation._ |
| **Semantic Relation Level:** | _rdfs:equivalentClass_ |
| **Mapping Axioms:** | _TBD_ |

## EXISTENT CONCEPT: IMMATERIAL ENTITY (BFO)

### General Concept Info:

| **IRI:** | _<http://purl.obolibrary.org/obo/BFO\_0000141>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | _A is an immaterial entity =Def a is an independent continuant which is such that there is no time t when it has a material entity as continuant part at t._ <br> _Site: b is a site means: b is a three-dimensional immaterial entity whose boundaries either (1) (partially or wholly) coincide with the boundaries of one or more material entities or (2) have locations determined in relation to some material entity._ <br> _Continuant Fiat Boundary: b is a continuant fiat boundary means: b is an immaterial entity that is of zero, one or two dimensions, which is such that there is no time t when b has a spatial region as continuant part at t, and whose location is determined in relation to some material entity._ <br> _Examples of Usage:_ As for fiat point, fiat line, fiat surface, site. <br> - Site: a hole in a portion of cheese, a rabbit hole, the Grand Canyon, the Piazza San Marco, the kangaroo-joey-containing hole of a kangaroo pouch, your left nostril (a fiat part - the opening - of your left nasal cavity), the lumen of your gut, the hold of a ship, the interior of the trunk of your car, hole in an engineered floor joist; An air traffic control region of type A is determined in terms of elevation above mean sea level of lower and upper boundaries. <br> - Fiat Point: the geographic North Pole; the quadripoint where the boundaries of Colorado, Utah, New Mexico and Arizona meet, the point of origin of some spatial coordinate system. <br> - Fiat Line: the Equator, all geopolitical boundaries, all lines of latitude and longitude, the median sulcus of your tongue, the line separating the outer surface of the mucosa of the lower lip from the outer surface of the skin of the chin. <br> - Fiat Surface: the surface of the Earth, the plane separating the smoking from the non-smoking zone in a restaurant|
| **Labels:** | _ImmaterialEntity_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _Building Ontologies with BFO:_ "Immaterial entity. An independent continuant that contains no material entities as parts. Immaterial entities divide into two major subgroups: (1) boundaries and sites, which bound, or are demarcated in relation to, material entities, and which can thus change location, shape, and size as their material hosts move or change shape or size; (2) spatial regions, which exist independently of material entities, and which thus do not change". |

## EXISTENT CONCEPT: FEATURE (DOLCE)

### General Concept Info:

| **IRI:** | _<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#Feature>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A Feature is a physical endurant which has a unity criterion and is existentially dependent on another physical endurant, its host (examples: a hole, a bump, an object's boundary, a stain on a t-shirt). |
| **Labels:** | _Feature_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _DOLCE D18:_ "Typical examples of features are "parasitic entities" such as holes, boundaries, surfaces, or stains, which are generically constantly dependent on physical objects (their hosts). All features are essential wholes, but, as in the case of objects, no common unity criterion may exist for all of them. However, typical features have a topological unity, as they are singular entities. Some features may be relevant parts of their host, like a bump or an edge, or places like a hole in a piece of cheese, the underneath of a table, the front of a house, which are not parts of their host. It may be interesting to note that we do not consider body parts like heads or hands as features: the reason is that we assume that a hand can be detached from its host (differently from a hole or a bump), and we assume that in this case it retains its identity. Should we reject this assumption, then body parts would be features". |

## EXISTENT CONCEPT: FIELD (EMMO)

### General Concept Info:

| **IRI:** | _<http://emmo.info/emmo#EMMO\_70dac51e\_bddd\_48c2\_8a98\_7d8395e91fc2>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A 'Physical' with 'Massless' parts that are mediators of interactions. |
| **Labels:** | _Field_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _European Materials Modelling Ontology v. 1.0.0 alpha 2: "the concepts of matter and field for classical physics, upon which we can categorize physical entities, are replaced in quantum physics by the more general concepts of quantum field"._ |

## EXISTENT CONCEPT: FIELD (EMMO-MECH-TEST)

### General Concept Info:

| **IRI:** | _<http://emmo.info/emmo#EMMO\_70dac51e\_bddd\_48c2\_8a98\_7d8395e91fc2>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A 'Physical' with 'Massless' parts that are mediators of interactions. The concepts of matter and field for classical physics, upon which we can categorize physical entities, are replaced in quantum physics by the more general concepts of quantum field. Here the class 'Field' refers to the quantum field of massless bosonic particles (i.e. photons, gluons), while the class 'Matter' refers to the quantum field of massive fermionic or bosonic particles (e.g. quarks, electrons). |
| **Labels:** | _Field_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _European Materials Modelling Ontology v. 1.0.0 alpha 2: "the concepts of matter and field for classical physics, upon which we can categorize physical entities, are replaced in quantum physics by the more general concepts of quantum field"._ |
