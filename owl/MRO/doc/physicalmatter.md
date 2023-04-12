# **PHYSICAL MATTER**

### **General Concept Info:**

| **IRI:** | _Suggested entity new IRI._ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | Physical Matter is that which occupies space and has rest mass. The vast majority of everyday physical objects human beings interact with have parts which are quanta with non-zero rest mass, though the reduction of the former to the latter is scientifically inaccurate, and should be considered at most a pragmatic approximation. Physical Matter is not to be confused with Aristotelian Matter -a metaphysical posit- albeit the relevant notions are ultimately not unrelated, and common sense's understanding arguably sways in between the two. <br><br> Domain: Natural Sciences - Physics. |
| **Labels:** | __skos:prefLabel: Physical Matter__ <br><br> __skos:altLabel: Matter; Amount of Matter; (Amount of) Matter; Portion of Matter; (Portion of) Matter; Ordinary Matter__ <br><br> __skos:hiddenLabel: Stuff__ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _-Wikipedia:_ "matter is the substance of which objects are made"; "In classical physics and general chemistry, matter is any substance that has mass and takes up space by having volume. All everyday objects that can be touched are ultimately composed of atoms, which are made up of interacting subatomic particles, and in everyday as well as scientific usage, 'matter' generally includes atoms and anything made up of them, and any particles (or combination of particles) that act as if they have both rest mass and volume. However it does not include massless particles such as photons, or other energy phenomena or waves such as light or heat"._-Encyclopedia Britannica:_ "matter, material substance that constitutes the observable universe and, together with energy, forms the basis of all objective phenomena. At the most fundamental level, matter is composed of elementary particles known as quarks and leptons"._-WordNet 3.1:_ "that which has mass and occupies space".-_WikiData:_ "substance that has rest mass and volume". |
| **Comments:** | _The engineered OntoCommons bridge-concept, Physical Matter, aims to provide a general definition of matter focusing on some distinctive traits, while at the same time ruling out possible ambiguities due to the related term's etymology. For the sake of aligning the bridge-concept with stakeholders' demands and standard usage, it was decided to leave ample room to common-sense; clarifications were nonetheless included when they were deemed necessary to strike a balance between intuitiveness and scientific rigorousness. Notably, the chosen core traits play a pivotal role in the vast majority of the well-known and pervasively used domain resources which were consulted. This will ensure immediateness and intuitiveness for domain experts and ontologists, while at the same time improving the usability for non-experts. The risk of meaning/conceptual shift, and thus, obsoleteness, is also reduced. Finally Physical Matter was explicitly distinguished from the metaphysical Aristotelian Matter, as the similarities are not strong enough to ensure interoperability, yet abundantly capable of generating confusions. Nonetheless the two concepts are by all means related, and often con-fused in hybrid concepts._ |

## Alignments To Existing Ontologies:

|     |     |
| --- | --- |
| **Target Ontology:** | BFO: _<http://purl.obolibrary.org/obo/bfo.owl>_ |
| **Related Ontology Entities:** | _Material Entity: <http://purl.obolibrary.org/obo/BFO\_0000040>_ |
| **Mapping Elucidation:** | _In BFO, Material Entities are explicitly stated to be independent continuants that have some portions of matter as their part. Given that, the enquiry should be focused on those entities which can be part of BFO's Material Entities. Arguably, there aren't many relevant candidates, all of which are subclasses of BFO:Material Entity. In fact, it seems inappropriate to think of Physical Matter in terms of BFO's Object Aggregates, but that's an interpretation which cannot be entirely ruled out. As such the most informative and appropriate alignment is arguably with the class BFO:Material Entity itself, and, specifically, the union of BFO:Object and BFO:Object Aggregate. The classes are not mutually disjoint as the relevant BFO universals are not rigid, so there is no major loss of informativeness considering a class closer to the root. There do not seem to be evidence in favour of a different alignment._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | DOLCE: _<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic>_ |
| **Related Ontology Entities:** | _AmountOfMatter: <http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#AmountOfMatter>_ |
| **Mapping Elucidation:** | _Part of what has been said with respect to BFO:Material Entity is relevant when it comes to DOLCE:Physical Endurant. However, the choice of a subclass is in this case possible and, in fact, almost immediate, qua suggested both by the linguistic label and the relevant documentation: DOLCE:Amount of Matter. However, at a closer inspection, DOLCE's concept seems heavily influenced by the metaphysical, Aristotelian/Neo-Aristotelian connotation from which we decided to part in the definition of the OntoCommons bridge-concept, Physical Matter. Nonetheless, it is important to consider the alignment holistically, taking into proper account the background assumptions underlying DOLCE's framework: all things considered, DOLCE's concept arguably falls in the "hybrid" territory, and it doesn't seem necessary to weaken the semantic relation from rdfs:equivalentClass to skos:related, especially since the core traits which were chosen to characterise the proposed bridge-concept are explicitly endorsed._ |
| **Semantic Relation Level:** | _rdfs:equivalentClass_ |
| **Mapping Axioms:** | _TBD_ |


|     |     |
| --- | --- |
| **Target Ontology:** | EMMO: http://emmo.info/emmo |
| **Related Ontology Entities:** | _Matter: http://emmo.info/emmo#EMMO\_5b2222df\_4da6\_442f\_8244\_96e9e45887d1_ |
| **Mapping Elucidation:** | _EMMO:Matter seems to be the perfect candidate for a meaningful and informative alignment with the OntoCommons bridge-concept Physical Matter, with no real contenders. EMMO:Matter belongs -in line with expectations- to the physicalistic perspective; the concept is explicitly characterised alongside Field and Vacuum referring to a state-of-the-art scientific paradigm, that is the Standard Model of particle physics. It should be noted that the relevant EMMO concept has no direct link with common-sense/intuitiveness, differently from the bridge-concept. However, taking into account EMMO's framework, that is arguably to be expected, and the (applied) sciences-friendly definition provided in EMMO is ultimately perfectly in line with the one put forward by the OntoCommons team. It is worth noting that, while not all the traits are explicitly endorsed in EMMO:Matter's elucidation, they can be all be recovered/inferred by considering the class' superclasses', and taking into account EMMO's overall framework. The most pertinent alignment is thus that of class-equivalence._ |
| **Semantic Relation Level:** | _rdfs:equivalentClass_ |
| **Mapping Axioms:** | _TBD_ |


|     |     |
| --- | --- |
| **Target Ontology:** | Domain Mechanical Testing (EMMO-MECH-TEST): _<http://emmo.info/emmo/domain/mechanical-testing>_ |
| **Related Ontology Entities:** | _Matter: http://emmo.info/emmo/middle/physicalistic#EMMO\_5b2222df\_4da6\_442f\_8244\_96e9e45887d1_ |
| **Mapping Elucidation:** | _The Domain Mechanical Testing ontology EMMO-MECH-TEST is based on EMMO; as such what has been said above can be applied mutatis mutandis in this case. Given the proposed semantic link, the absence of better candidates should come as no surprise. However, it should be noted that EMMO-MECH-TEST is based on an outdated version of EMMO. Nonetheless, there are no significant differences compromising the alignment, or modifying the semantic relationship between the proposed OntoCommons bridge-concept, Physical Matter, and EMMO-MECH-TEST's Matter._ |
| **Semantic Relation Level:** | _rdfs:equivalentClass_ |
| **Mapping Axioms:** | _TBD_ |

## EXISTENT CONCEPT: MATERIAL ENTITY (BFO)

### General Concept Info:

| **IRI:** | _<http://purl.obolibrary.org/obo/BFO\_0000040>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | _A material entity is an independent continuant that at all times at which it exists has some portion of matter as continuant part._ <br> _Examples of Usage:_ a human being, the undetached arm of a human being, an aggregate of human beings. |
| **Labels:** | Material Entity |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _Building Ontologies with BFO:_ "material entity is an independent continuant that has some portion of matter as part. It is thus an independent continuant that is spatially extended in three dimensions, and that continues to exist through some interval of time, however short.". |

## EXISTENT CONCEPT: AMOUNT OF MATTER (DOLCE)

### General Concept Info:

| **IRI:** | _<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#AmountOfMatter>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | An Amount Of Matter is a physical endurant which has no unity criterion and is mereologically invariant, that is, all its part are essential parts. <br> _Examples of Usage:_ the gold of my wedding ring, the sand used to make this glass. |
| **Labels:** | _AmountOfMatter_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No instances._ |

## EXISTENT CONCEPT: MATTER (EMMO)

### General Concept Info:

| **IRI:** | http://emmo.info/emmo#EMMO\_5b2222df\_4da6\_442f\_8244\_96e9e45887d1 |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A 'Physical' that possesses some 'Lepton' or 'Quark' parts in each of its temporal parts. |
| **Labels:** | Matter |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _European Materials Modelling Ontology v. 1.0.0 alpha 2:_ "Matter: A 'Physical' that possesses some 'Massive' parts". |

## EXISTENT CONCEPT: MATTER (EMMO-MECH-TEST)

### General Concept Info:

| **IRI:** | http://emmo.info/emmo/middle/physicalistic#EMMO\_5b2222df\_4da6\_442f\_8244\_96e9e45887d1 |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A 'Physical' that possesses some 'Massive' parts. |
| **Labels:** | Matter |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No instances._ |
