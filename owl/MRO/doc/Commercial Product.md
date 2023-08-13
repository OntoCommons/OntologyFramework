
# Commercial Product

### General Concept Info:

| **IRI:** | _Suggested entity new IRI._ |
| --- | --- |
| **OWL Type:** | Class |
| **Concept Elucidation:** | A Commercial Product is something which is explicitly offered on the market for purchase or barter. Commercial Products can consist in the outcome of some kind of practical and/or intellectual activity, or in the access to some benefits. 
In the first scenario, the activity needn’t necessarily have been performed, directly, or indirectly, by the organization or individual offering the Commercial Product on the market, and the activity itself needn’t involve a transformation of the item which is then offered for purchase. In the second case, the benefit has to be made directly, or indirectly, available by the organization or individual offering the Commercial Product on the market, and the access to the relevant benefit can be temporary (be the duration predetermined or not) or permanent.
Commercial Products can either belong to the purchaser for an indefinite period of time after the completion of a transaction, or the transference of their ownership might not figure as a condition for the completion of the transaction. They can indifferently be either tangible or intangible, artefacts or not artefacts. Likewise, they can indifferently be e.g., raw materials, processed materials, goods, intellectual properties, and services.
Domain: Economics - Business – Marketing|
| **Labels:** | Labels used to address the concept, ordered as: 
skos:prefLabel: Commercial Product
skos:altLabel: Product; Product (Economic)
skos:hiddenLabel: Good; Service; Article; Purchasable; Transactable Entity; Merchandise; Commodity; Ware
 |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | Wikipedia: “an atom is the smallest unit of ordinary matter that forms a chemical element”; “an atom is a basic unit of matter consisting of a nucleus within a cloud of one or more electrons”. <br><br> Encyclopedia Britannica: “smallest unit into which matter can be divided without the release of electrically charged particles. It also is the smallest unit of matter that has the characteristic properties of a chemical element”. <br><br> WordNet 3.1: “the smallest component of an element having the chemical properties of the element” <br><br> WikiData: “smallest indivisible unit of a chemical substance” (Q9121). <br><br> IUPAC Goldbook: “Smallest particle still characterising a chemical element. It consists of a nucleus of a positive charge (Z is the proton number and e the elementary charge) carrying almost all its mass (more than 99.9%) and Z electrons determining its size”.|
| **Comments:** | This engineered OntoCommons bridge-concept aims to provide a general, up-to-date and ambiguity-free characterisation of one of the most employed and successful notions in physics and chemistry. In this case, the lack of a shared common ground might not have immediate consequence for stakeholders, but there is a serious risk of compromising some of the most notable advantages in data exchange via ontologies, and, specifically having to do with reusability and the overall network’s predictive potential. Ultimately, as a result of a survey of the related concepts appearing in MLOs, it was decided to put forward a very general Atom bridge-concept, and explicitly specify value gaps with respect to two characteristic traits: net charge and bonds. Thus, a neutral atom and a charged atom (ion) are joint into the concept Atom, and the same goes for Standalone Atoms and Bonded Atoms. It should be noted that this last point solves a serious representational issue whereas atoms are considered as mereological parts of molecules, as many resources (and even golden standards such as the IUPAC, do: <https://doi.org/10.1351/goldbook.M04002>. There was in fact an effort to ensure that the proposed bridge-concept would be aligned with said golden standard, even relatively to the definition/elucidation itself. The trait of “being the smallest particle still characterising a chemical element” was explicitly stated to be domain specific, for the sake of clarity: in line with that, it was decided not to include the trait “basic unit of matter”, even though it could point to a taxonomical, hierarchical, informative characteristic. Notably, the resulting definition is also not too far from the ones provided by well known and pervasively employed domain resources, such as Wikipedia, Wikidata, WordNet and the Encyclopedia Britannica. The trait of being “indivisible”, appearing in Wikidata’s has been deemed obsolete and potentially confusing qua too close too the notion of Mereological Atom, which cannot be ignored due to Mereology’s pervasiveness in formal ontologies. It is factually possible to split Atoms into their subatomic components, and Encyclopedia Britannica’s definition depicts a vastly more accurate picture.  |

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
