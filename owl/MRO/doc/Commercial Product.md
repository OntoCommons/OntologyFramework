
# Commercial Product

### General Concept Info:

| **IRI:** | _Suggested entity new IRI._ |
| --- | --- |
| **OWL Type:** | Class |
| **Concept Elucidation:** | A Commercial Product is something which is explicitly offered on the market for purchase or barter. Commercial Products can consist in the outcome of some kind of practical and/or intellectual activity, or in the access to some benefits. <br><br> In the first scenario, the activity needn’t necessarily have been performed, directly, or indirectly, by the organization or individual offering the Commercial Product on the market, and the activity itself needn’t involve a transformation of the item which is then offered for purchase. In the second case, the benefit has to be made directly, or indirectly, available by the organization or individual offering the Commercial Product on the market, and the access to the relevant benefit can be temporary (be the duration predetermined or not) or permanent. <br><br> Commercial Products can either belong to the purchaser for an indefinite period of time after the completion of a transaction, or the transference of their ownership might not figure as a condition for the completion of the transaction. They can indifferently be either tangible or intangible, artefacts or not artefacts. Likewise, they can indifferently be e.g., raw materials, processed materials, goods, intellectual properties, and services. <br><br> Domain: Economics - Business – Marketing|
| **Labels:** | Labels used to address the concept, ordered as: <br><br> skos:prefLabel: Commercial Product <br><br> skos:altLabel: Product; Product (Economic) <br><br> skos:hiddenLabel: Good; Service; Article; Purchasable; Transactable Entity; Merchandise; Commodity; Ware|

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | Wikipedia: “in marketing, a product is an object, or system, or service made available for consumer use as of the consumer demand; it is anything that can be offered to a market to satisfy the desire or need of a customer”; “In retailing, products are often referred to as merchandise, and in manufacturing, products are bought as raw materials and then sold as finished goods. A service is also regarded as a type of product”. <br><br> WordNet 3.1: “commodities offered for sale”; “an artifact that has been created by someone or some process”. <br><br> WikiData: “result of work that can be offered to a market” (Q2424752). <br><br> ISO 9000: “output of an organization that can be produced without any transaction taking place between the organization and the customer”; “production of a product is achieved without any transaction necessarily taking place between provider and customer, but can often involve this service element upon its delivery to the customer”; “the dominant element of a product is that it is generally tangible”; “Hardware is tangible and its amount is a countable characteristic (e.g. tyres). Processed materials are tangible and their amount is a continuous characteristic (e.g. fuel and soft drinks). Hardware and processed materials are often referred to as goods”; “software consists of information regardless of delivery medium (e.g. computer programme, mobile phone app, instruction manual, dictionary content, musical composition copyright, driver's license)”. <br><br> ISO 14040: “any goods or service”; “the product can be categorized as follows: — services (e.g. transport); — software (e.g. computer program, dictionary); — hardware (e.g. engine mechanical part); — processed materials (e.g. lubricant)”; “services have tangible and intangible elements. Provision of a service can involve, for example, the following: — an activity performed on a customer-supplied tangible product (e.g. automobile to be repaired); — an activity performed on a customer-supplied intangible product (e.g. the income statement needed to prepare a tax return); — the delivery of an intangible product (e.g. the delivery of information in the context of knowledge transmission); — the creation of ambience for the customer (e.g. in hotels and restaurants). Software consists of information and is generally intangible and can be in the form of approaches, transactions or procedures. Hardware is generally tangible and its amount is a countable characteristic. Processed materials are generally tangible and their amount is a continuous characteristic”; “adapted from ISO 14021:1999 and ISO 9000:2005”.|
| **Comments:** | This engineered OntoCommons bridge-concept aims to provide an extremely general umbrella notion focused on a few defining traits for a family of concepts which are pivotal in business practice, from the perspective of industrial stakeholders. The decision to follow this strategy was made in accordance with the requests coming from MLOs’ stakeholders given OntoCommons’ survey.  <br><br> The defining trait grouping up the relevant individuals was identified in their being actually, and explicitly, offered for purchase or barter on the market; the choice to include the two specifications above (actuality and explicitness) being due to the fact that, in principle, almost anything can be sold, and implicit availability for purchase or barter seemed inadequate given the aims of the project, and harder to rein in.  <br><br> The focus is on the economic aspects; though the term is also associated with manufacturing/transformative ones, which can arguably be the basis for a different bridge-concept. A composite characterisation of the concept, possibly closer to the term’s use, would have run the risk of being vague and, thus, incapable of capturing in a formal way any of the underlying ideas. Again, a manufacturing-related characterisation also risked collapsing on quite different notions, related to the concepts of (generic) Output (of a process) or Equipment, as they are commonly characterised and understood. It was decided to focus specifically on one direction of the transaction to address and avoid ambiguities which might arise, in practice, in ontologies built specifically for industrial usage.  <br><br> Given the incompatibility of golden standards (ISO 9000 and ISO 14040, inter alia and significantly), on the notion of product, a choice had to be made: in line with what has been said above, it was decided to follow more closely ISO 14040, explicitly addressing all the divergences which might have otherwise resulted in ambiguities. The choice was also influenced by the fact that ISO 14040’ definition is closer to the ones put forward in other well-known resources. That said, ISO 9000 is extensively referenced in the definition of the OntoCommons bridge-concept Article (Commercial), and the standard is also directly taken into account in the definition of two other OntoCommons bridge-concepts: Good (Commercial) and Service (Commercial), whereas all these concepts belong to the OntoCommons concept cluster hinged on Commercial Product.  <br><br> It should be added that, while an analysis of a selected sample of ontologies showed that a narrower concept might have avoided issues pertaining to alignment arising from trans-categoricity, the preemptive investigation also made patent an implicit preference (if not a need) of stakeholders for a broad concept of product (closer to ISO 14040), at least when MLOs were concerned.  <br><br> Other possibly problematic points were addressed by making traits’ values/value gaps explicit, value gaps being prevalent due to the organisation of the concept cluster and the broadness of the bridge-concept Commercial Product; a more in-depth explanation of some of the relevant traits/values can be found in the comments to the elucidations of other bridge-concepts belonging to the cluster: Commercial Product. It was also decided not to list “paradigmatic  (yet not strictly necessary) characteristics” in order to avoid introducing biases which might have affected domain experts, ontologists, and generic users alike. |

## Concept's cluster:
|     |     |
| --- | --- |
| **Cluster:** | Commercial Product |
| **Cluster relations:** | The Engineered OntoCommons bridge-concept Commercial Product is the core of the Cluster: Commercial Product.  <br><br> Article (Commercial) and Service (Commercial) are engineered in a way such that they jointly exhaust Commercial Product’s logical space; as a result of that, Article (Commercial) and Service (Commercial) are rdfs:subClassOf Commercial Product, and Commercial Product is rdfs:equivalentClass the union of Article (Commercial) and Service (Commercial). Likewise, Good (Commercial) and Intellectual Article (Commercial) are engineered in a way such that they jointly exhaust Article (Commercial)’s logical space; as a result of that, Good (Commercial) and Intellectual Article (Commercial) are rdfs:subClassOf Article (Commercial), and Article (Commercial) is rdfs:equivalentClass the union of Intellectual Article (Commercial) and Good (Commercial).  <br><br> The bridge-concepts belonging to the cluster are organized hierarchically focusing on core traits and traits-values, to the end of engineering strong semantic links capable of supporting mediated alignments. The traits are chosen in a way which maximizes coherence with existing standards and ease of alignment with ontologies, given commonly employed ontological theoretical choices/background assumptions.  <br><br> Specifically, the first partition of Commercial Product’s logical space -by means of the bridge-concepts Article (Commercial) and Service (Commercial)- attempts to capture the common-sense-friendly distinction between services and other things that can be purchased, often identified by means of labels such as ‘goods’ and ‘merchandise’. The trait chosen to distinguish the two pertains to economics, in line with the concepts’ domain: ownership transference upon purchase. An Article’s ownership is transferred to the purchaser as a necessary condition for the completion of a transaction, while Services needn’t involve ownership transferences not pertaining to legal rights. As a result of that, Articles can e.g., be fully returned to the seller, and can be separated from the latter, while that does not hold for Services. Yet these further traits/trait-values are to be considered derivative and indicative: not such as to characterise the distinction. It is often common to distinguish between Services and Products which are not Services by means of another trait: tangibility. Services are said to be intangible, while Products which are not Services are said to be tangible. While, as a rule of thumb, this might appear prima facie correct, the characterisation is problematic when it comes to certain Articles, and the trait is not overall neutral given different possible ontological background assumptions. As such, tangibility has not been deemed a trait capable of providing a rigorous and neutral partition. Again, it is worth pointing out that Services and other Products are actually often paired in practical cases of transactions: for instance, a transaction involving a typical good, such as an household appliance, often encompasses delivery and is affected by considerations related to availability, which pertain to services; likewise, a typical service, such as a high end restaurant consumption, de facto involves food/beverage ownership-transferences, though they might not be the focus of the transaction. It is thus important not to assume that products cannot be “internally composite”, and/or need to stand in a 1:1 relation with transactions. Ultimately the ancillary element, when present, is decided by the focus of the transaction.  <br><br> The second partition of the logical space (of Article (Commercial)) -by means of the bridge-concepts Good (Commercial) and Intellectual Article (Commercial)- attempts to capture the common-sense-friendly distinction between intellectual and material assets (“properties”, in the economic sense). The trait chosen to distinguish the two partitions is quite complex, in order to avoid counter-examples while preserving neutrality:  association with a specific material entity which doesn’t merely act as a legal placeholder or as a contingent medium to the end of completing a transaction. Goods are associated, and often appear entirely reducible, to material entities which do not merely act as legal placeholders or as contingent mediums to the end of completing transactions, while Intellectual Articles aren’t. As a result of that, the OntoCommons bridge-concept, Intellectual Article (Commercial) arguably covers all the so-called intellectual properties (which are explicitly offered on the market for purchase and whose ownership is transferred to the purchaser upon completion of a transaction). As a general note, while pertaining to economics and related to jurisprudence, the particular bridge-concepts, and the cluster overall, do not aim at capturing neutral and hypothetically universally valid legal notions, and lack well-known specifications in the relevant domains; the level of detail of the proposed definitions was deemed appropriate given the aims of the project, and the synchronic and diachronic heterogeneity of legislations. <br><br> The resulting engineered cluster of bridge-concepts, hinged on the OntoCommons bridge-concept Commercial Product -covering and organising the logical space of core concepts in business practice- is arguably de facto aligned with golden standards (as explicitly argued for in the comments to the knowledge domain resources for each of the particular bridge-concepts), and -at the same time- respectful of possible discrepancies in ontological representation given background assumptions which do not strictly pertain to the economic domain the concept cluster belongs to. The partitions should be conductive to conceptual clarity while at the same time facilitating alignments which would have otherwise been hardly possible, at least in some cases, as argued for in (some of) the mapping elucidations for the bridge-concepts belonging to the concept cluster, and Commercial Product & Article (Commercial) in particular: in fact, the bridge-concept Commercial Product, much like many broad concepts belonging to the business/legal areas, is trans-categorical given partitions of the logical space commonly employed by most Top Level Ontologies, and some of the ontologies belonging to the OntoCommons EcoSystem for what concerns us here (BFO and DOLCE). The conceptual cluster has thus the further benefit of ensuring more precise and informative mappings, automatically connecting single ontologies to a well-defined conceptual architecture. |

## Alignments To Existing Ontologies:

|     |     |
| --- | --- |
| **Target Ontology:** | BFO: <http://purl.obolibrary.org/obo/bfo.owl> |
| **Related Ontology Entities:** | Material Entity: <http://purl.obolibrary.org/obo/BFO_0000040> |
| **Mapping Elucidation:** | Given BFO’s internal organization, there do not seem to be many options beside BFO:Material Entity for an alignment. In general, as far as BFO’s distinctions are concerned, Atoms do not seem to be vastly different from moderate-sized specimens of dry goods such as tables and bricks. Arguably, the real question concerns whether the proposed OntoCommons bridge-concept, Atom, is a subclass of BFO:Object, BFO:Object Aggregate, or BFO:Fiat Object (which is arguably the rightful categorisation for a restriction of Atom via the bonded trait); however the classes are not mutually disjoint as the relevant BFO universals are not rigid, so the questions is, to a degree, meaningless. In fact, the possibility of the relevant individuals of migrating among the classes seems especially appropriate in this specific scenario. There do not seem to be reasons to consider a different alignment, and the examples of usage appear to be pertinent. Despite the intuitive gap between Material Entities and Atoms, the connection seems informative and appropriate: in fact, it is pivotal to be wary of intuitions which might derive from unrelated considerations pertaining to concepts’ prototypes and scale. Finally, it is worth considering whether such an alignment is conductive to an appropriate representation of electron clouds, but -it could be argued- that would be putting the cart before the horse. |
| **Semantic Relation Level:** | rdfs:subClassOf |
| **Mapping Axioms:** | TBD |

|     |     |
| --- | --- |
| **Target Ontology:** | DOLCE: <http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic> |
| **Related Ontology Entities:** | NonAgentivePhysicalObject: <http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#NonAgentivePhysicalObject> |
| **Mapping Elucidation:** | The vast majority of what has been said with respect to BFO:Material Entity is relevant when it comes to DOLCE:Physical Endurant. However, the choice of a subclass, or, more specifically, of a tree of subclasses is in this case possible and informative. In DOLCE there is no distinction analogous to the one between BFO:Objects and BFO:Objects Aggregates; DOLCE:Arbitrary Sums plays a completely different role. As such, the proposed OntoCommons bridge-concept, Atom, can be seen as a subclass of DOLCE:Physical Object. Given the further distinction between Dolce’s Agentive and Non Agentive Physical Objects, based on intentionality and the possess of desires and beliefs, the choice seems straightforward, bizarre philosophical options contrary to common-sense notwithstanding. Thus, the proposed bridge-concept Atom is arguably a subclass of DOLCE:Non Agentive Physical Object; the connection seems informative and appropriate, and it is made even more plausible given the examples of usage provided in the relevant documentation. |
| **Semantic Relation Level:** | rdfs:subClassOf |
| **Mapping Axioms:** | TBD |

|     |     |
| --- | --- |
| **Target Ontology:** | EMMO: <http://emmo.info/emmo> |
| **Related Ontology Entities:** |Atom: <http://emmo.info/emmo#EMMO_eb77076b_a104_42ac_a065_798b2d2809ad> |
| **Mapping Elucidation:** | EMMO:Atom appears to be the perfect candidate for an alignment based on class equivalence with the proposed OntoCommons bridge-concept, Atom. The tentative connection is supported by the relevant documentation, which makes explicit relevant value gaps by means of subclasses. There do not seem to be reasons to consider other alignments, and, in this case, even the problems involving the eventual in-framework representation of electron clouds can be dismissed. |
| **Semantic Relation Level:** | rdfs:equivalentClass |
| **Mapping Axioms:** | TBD |

|     |     |
| --- | --- |
| **Target Ontology:** | BWMD-mid: <https://www.materials.fraunhofer.de/ontologies/BWMD_ontology/mid> |
| **Related Ontology Entities:** |Atom: <https://www.materials.fraunhofer.de/ontologies/BWMD_ontology/mid#BWMD_00131> |
| **Mapping Elucidation:** | The prima facie obvious candidate for a connection is BWMD:Atom. The alignment is based on the assumption that the relevant Wikipedia page (in German), and specifically the version which was consulted by BWMD’s developers, is consistent with its English analogue as of 24/04/22, given what has been said above in the comment to the elucidation of the OntoCommons bridge-concept, Atom. In support of this alignment, it should also be noted that BWMD is based on BFO, and BWMD:Atom is a subclass of BWMD/BFO:Object and of BWMD/BFO:Material Entity, consistently with the relative proposed alignment. Moreover, there do not seem to be other candidates worth considering, nor evidence against a semantic relationship of class equivalence. However there could, and should, be doubts concerning how literally “any kind of atom as described by https://de.wikipedia.org/wiki/Atom” should be interpreted. Due to the lack of alternatives, common-sense was chosen as a guide. |
| **Semantic Relation Level:** | rdfs:equivalentClass |
| **Mapping Axioms:** | TBD |

|     |     |
| --- | --- |
| **Target Ontology:** | EMMO-MECH-TEST: <http://emmo.info/emmo/domain/mechanical-testing> |
| **Related Ontology Entities:** |Atom: <http://emmo.info/emmo/middle/materials#EMMO_eb77076b_a104_42ac_a065_798b2d2809ad> |
| **Mapping Elucidation:** | The Domain Mechanical Testing ontology EMMO-MECH-TEST is based on EMMO; as such what has been said above can be applied mutatis mutandis in this case. Given the proposed semantic link, the absence of better candidates should come as no surprise. However, it should be noted that EMMO-MECH-TEST is based on an outdated version of EMMO. Nonetheless, there are no significant differences compromising the alignment, or modifying the semantic relationship between the proposed OntoCommons bridge-concept, Atom, and EMMO-MECH-TEST’s Atom. |
| **Semantic Relation Level:** | rdfs:equivalentClass |
| **Mapping Axioms:** | TBD |

## EXISTENT CONCEPT: MATERIAL ENTITY (BFO)

### General Concept Info:

| **IRI:** |<http://purl.obolibrary.org/obo/BFO_0000040> |
| --- | --- |
| **OWL Type:** | Class |
| **Concept Elucidation:** | A material entity is an independent continuant that at all times at which it exists has some portion of matter as continuant part. <br><br> Examples of Usage: a human being, the undetached arm of a human being, an aggregate of human beings. |
| **Labels:** | Material Entity |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | Building Ontologies with BFO: “material entity is an independent continuant that has some portion of matter as part. It is thus an independent continuant that is spatially extended in three dimensions, and that continues to exist through some interval of time, however short”. |
| **Comments:** |  |

## EXISTENT CONCEPT: NON AGENTIVE PHYSICAL OBJECT (DOLCE)

### General Concept Info:

| **IRI:** |<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#NonAgentivePhysicalObject> |
| --- | --- |
| **OWL Type:** | Class |
| **Concept Elucidation:** | A Non-Agentive Physical Object is a physical object to which intentions, believes and desires are not ascribed. <br><br> Examples of Usage: a pebble, a house, a computer, a human body. |
| **Labels:** | NonAgentivePhysicalObject |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | Dolce D18: “within Physical Objects, a special place have those those to which we ascribe intentions, beliefs, and desires. These are called Agentive, as opposite to Non-agentive. Intentionality is understood here as the capability of heading for/dealing with objects or states of the world. This is an important area of ontological investigation we haven’t properly explored yet, so our suggestions are really very preliminary”. |
| **Comments:** |  |

## EXISTENT CONCEPT: ATOM (EMMO)

### General Concept Info:

| **IRI:** |<http://emmo.info/emmo#EMMO_eb77076b_a104_42ac_a065_798b2d2809ad> |
| --- | --- |
| **OWL Type:** | Class |
| **Concept Elucidation:** | An 'atom' is a 'nucleus' surrounded by an 'electron_cloud', i.e. a quantum system made of one or more bounded electrons. |
| **Labels:** | Atom |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | European Materials Modelling Ontology v. 1.0.0 alpha 2: “Bonded Atom: an Atom that shares at least one electron to the atom-based entity of which is part of. A real bond between atoms is always something hybrid between covalent, metallic and ionic. In general, metallic and ionic bonds have atoms sharing electrons. The bond types that are covered by this definition are the strong electonic bonds: covalent, metallic and ionic. This class can be used to represent molecules as simplified quantum systems, in which outer molecule shared electrons are un-entangled with the inner shells of the atoms composing the molecule”; “Standalone Atom: an atom that does not share electrons with other atoms. A standalone atom can be bonded with other atoms by intermolecular forces (i.e. dipole–dipole, London dispersion force, hydrogen bonding), since this bonds does not involve electron sharing”; “Neutral Atom: A standalone atom that has no net charge”; “Ion Atom: standalone atom with an unbalanced number of electrons with respect to its atomic number”.  |
| **Comments:** |  |

## EXISTENT CONCEPT: ATOM (BWMD)

### General Concept Info:

| **IRI:** |<https://www.materials.fraunhofer.de/ontologies/BWMD_ontology/mid#BWMD_00131> |
| --- | --- |
| **OWL Type:** | Class |
| **Concept Elucidation:** | Any kind of atom as described by https://de.wikipedia.org/wiki/Atom |
| **Labels:** | Atom |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | <https://de.wikipedia.org/wiki/Atom>  |
| **Comments:** |  |

## EXISTENT CONCEPT: ATOM (EMMO-MECH-TEST)

### General Concept Info:

| **IRI:** |<http://emmo.info/emmo/middle/materials#EMMO_eb77076b_a104_42ac_a065_798b2d2809ad> |
| --- | --- |
| **OWL Type:** | Class |
| **Concept Elucidation:** | An 'atom' is a 'nucleus' surrounded by an 'electron_cloud', i.e. a quantum system made of one or more bounded electrons. A standalone atom has direct part one 'nucleus' and one 'electron_cloud'. An O 'atom' within an O2 'molecule' is an 'e-bonded_atom'. In this material branch, H atom is a particular case, with respect to higher atomic number atoms, since as soon as it shares its electron it has no nucleus entangled electron cloud. We cannot say that H2 molecule has direct part two H atoms, but has direct part two H nucleus. |
| **Labels:** | Atom |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | European Materials Modelling Ontology v. 1.0.0 alpha 2: “Bonded Atom: an Atom that shares at least one electron to the atom-based entity of which is part of. A real bond between atoms is always something hybrid between covalent, metallic and ionic. In general, metallic and ionic bonds have atoms sharing electrons. The bond types that are covered by this definition are the strong electronic bonds: covalent, metallic and ionic. This class can be used to represent molecules as simplified quantum systems, in which outer molecule shared electrons are un-entangled with the inner shells of the atoms composing the molecule”; “Standalone Atom: an atom that does not share electrons with other atoms. A standalone atom can be bonded with other atoms by intermolecular forces (i.e. dipole–dipole, London dispersion force, hydrogen bonding), since this bonds does not involve electron sharing”; “Neutral Atom: A standalone atom that has no net charge”; “Ion Atom: standalone atom with an unbalanced number of electrons with respect to its atomic number”.   |
| **Comments:** |  |
