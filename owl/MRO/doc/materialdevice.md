### **MATERIAL DEVICE**

## **General Concept Info:**

| **IRI:** | _Suggested entity new IRI._ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A Device is a physical entity which is engineered to the end of completing a specific type of tasks, or to have a particular set of properties which allows them to perform certain functions under a predetermined (generic, or non-generic yet well-defined) range of scenarios. Devices can be either disposable or meant for repeated/prolonged use, and they can either use a source of energy as one of the inputs for the completion of the relevant task or not. Infrastructures can be considered Devices only if the infrastructure itself is pivotal in the completion of the tasks/to perform certain functions, and the relevant tasks/functions are not bound to a specific location. <br><br> Domain: Industry and Manufacturing / Empirical Sciences - Materials Science. |
| **Labels:** | __skos:prefLabel: Device__ <br><br> __skos:altLabel: Tool (Broad)__ <br><br> __skos:hiddenLabel: Instrument__ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _-Wikipedia:_ "a device is usually a constructed tool"; "a tool is an object that can extend an individual's ability to modify features of the surrounding environment. Although many animals use simple tools, only human beings, whose use of stone tools dates back hundreds of millennia, have been observed using tools to make other tools. Early tools, made of such materials as stone, bone, and wood, were used for preparation of food, hunting, manufacture of weapons, and working of materials to produce clothing and useful artifacts"; "there is some debate on whether to consider protective gear items as tools, because they do not directly help perform work, just protect the worker like ordinary clothing. They do meet the general definition of tools and in many cases are necessary for the completion of the work. Personal protective equipment includes such items as gloves, safety glasses, ear defenders and biohazard suits"._-Encyclopedia Britannica:_ "tool: an instrument for making material changes on other objects, as by cutting, shearing, striking, rubbing, grinding, squeezing, measuring, or other processes. A hand tool is a small manual instrument traditionally operated by the muscular strength of the user, and a machine tool is a power-driven mechanism used to cut, shape, or form materials such as wood and metal. Tools are the primary means by which human beings control and manipulate their physical environment"._-WordNet 3.1__:_ "an instrumentality invented for a particular purpose"; "an instrumentality needed for an undertaking or to perform a service".-_WikiData:_ "all items that are required to exercise a certain activity" (Q10273457). |
| **Comments:** | _This engineered OntoCommons bridge-concept aims to provide a MLO-friendly umbrella concept for things which are employed by human beings to control and manipulate the (physical) environment, especially in the context of industry and manufacturing. The related family of terms and concepts actually appearing in vastly used and -arguably- successful MLOs is fairly broad, faceted and hard to pin down by means of a single bridge-concept: as such, it was necessary to make some decisions guided by pragmatic considerations, and it was decided to provide an ancillary sketch of taxonomy concerning other options. Given the general aims of the project, it was decided to focus on "physical" (whereas 'physical' should be understood broadly and not just as a disciplinary specification) devices; given the centrality of the targets' relation with human beings, and the pre-scientific nature of the underlying core ideas, it was decided to further restrict the conceptual boundaries to "material" devices. Focusing purely on the trait related to teleology, it might have been possible to define something along the lines of Equipment. However, the resulting bridge-concept might not have been discriminatory enough to be maximally informative, a problem which seemed to emerge in MLOs employing concepts revolving around said trait, despite the restricted domains of applications and, thus, instances to be categorised. Further traits were thus introduced, as per the elucidations, explicitly specifying also the "lower" limit, distinguishing the defined bridge-concepts, Device, from concepts which might arguably fall under the label of 'tool' or ' machine'. The distinctive trait separating the proposed bridge-concept from an hypothetical Tool concept is the inclusion of functions beside tasks when it comes to the teleological aspects. The distinctive trait separating the proposed bridge-concept from an hypothetical Machine concept is the lack of commitments concerning the necessity of a necessary source of energy as input. As a result of this, the proposed bridge-concept retains the desired generality, further improved via the explicit inclusion of specific kinds of infrastructures, which might have otherwise represented limiting cases. Finally, it should be noted that there is a weak committal to Devices being constructed artefacts, since they can also be "re-adapted" entities. The resulting definition is in line with the ones provided by pervasive domain resources such as Wikipedia, Wikidata, Wordnet and the Encyclopedia Britannica. Regarding the first, it should be noted that the ambiguous cases have been pragmatically resolved. This will ensure immediateness and intuitiveness for domain experts and ontologists, while at the same time improving the usability for non-experts. The risk of meaning/conceptual shift, and thus, obsoleteness, is also reduced. More importantly, the proposed bridge-concept should actually be a good compromise to meet the requests coming from MLOs' stakeholders emerged in OntoCommons' survey, and is also -arguably- clear enough to support well-motivated alignments with pre-existing MLO concepts/classes._ |

## Alignments To Existing Ontologies:

|     |     |
| --- | --- |
| **Target Ontology:** | BFO: _<http://purl.obolibrary.org/obo/bfo.owl>_ |
| **Related Ontology Entities:** | _Material Entity: <http://purl.obolibrary.org/obo/BFO\_0000040>_ |
| **Mapping Elucidation:** | _Even just at a rapid recognition, there appear to be two radically different targets for an alignment of the proposed OntoCommons bridge-concept, Device, in BFO: the first being BFO:Material Entity, a subclass of BFO:Independent Continuant, and the second being BFO:Realizable Entity, a subclass of BFO:Specifically Dependent Continuant. In the first case, Devices would be full fledged concrete, non-derivative entities, BFO:Objects or BFO:Object Aggregates. In the second case, they are BFO:Roles or BFO:Dispositions, tropes inhering in non-derivative entities exhibited through certain characteristic (more, or less, conventional) processes of realization. However, on second thought, it might be argued that the second alleged option rests on a categorical mistake, and -even taking into account BFO's internal structure and the core ontologico-metaphysical background assumptions underlying its framework- the link should at most be with the class of entities in which the relevant BFO:Specifically Dependent Continuants Inhere in. In any case, the quasi-totality of the MLOs based on BFO and employing comparable concepts chooses the first option, having them be subclasses of BFO:Material Entity; thus, in this case, it seems only appropriate to follow the majority, also for the sake of promoting standardisation (accommodating, whenever possible, pre-existing standards) and interoperability. Moving on, should the alignment be with BFO:Object or BFO:Object Aggregate? The classes are not mutually disjoint (as the relevant BFO universals are not rigid) so the questions is, to a degree, meaningless, or, -at the very least- unconsequential. As for the semantic relationship, it is apparent from the proposed definition and the relevant documentation that the bridge-concept can only be narrower than the target concept, and there do not seem to be evidence against a strong superclass-subclass link._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | DOLCE: _<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic>_ |
| **Related Ontology Entities:** | _NonAgentivePhysicalObject: <http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#NonAgentivePhysicalObject>_ |
| **Mapping Elucidation:** | _When it comes to the proposed OntoCommons bridge-concept, Device, the connection with DOLCE is much less complex than the one with BFO, as there do not appear to be two prima facie appropriate options: the only target for an alignment seems to be a subclass of DOLCE:Physical Endurant, DOLCE:Non Agentive Physical Object. DOLCE's distinction between Dolce's Agentive and Non Agentive Physical Objects rests on intentionality and the possess of desires and beliefs;, and while Devices, as they have been defined, do involve teleological considerations, it is not by any means the things themselves which have intentions, or, even considering bizarre limiting cases, they do not have intentions qua Devices. Thus, the proposed bridge-concept Device is arguably a subclass of DOLCE:Non Agentive Physical Object; the connection seems informative and appropriate, and it is plausible given the examples of usage provided in the relevant documentation._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | EMMO: _<http://emmo.info/emmo>_ |
| **Related Ontology Entities:** | _Device: <http://emmo.info/emmo/middle/manufacturing#EMMO\_494b372c\_cfdf\_47d3\_a4de\_5e037c540de8>_ |
| **Mapping Elucidation:** | _Given EMMO's background ontologico-metaphysical framework, and the characteristics of the proposed OntoCommons bridge-concept, Device, it seems appropriate to look for a meaningful connection in the holistic perspective branch. Here, it is possible to find the class EMMO:Device, which, given its label, might seem the most appropriate target for an alignment. While that is arguably the case, the semantic relation does not ultimately seem to be one of class-equivalence, as the linguistic label might suggest: while most traits are explicitly endorsed, EMMO:Device has in fact more constraints than the proposed bridge-concept, coming closer to an hypothetical definition of Tool or even Machine. Nonetheless, the differences are not such as to suggest other alignments, or to make the connection uninformative._ |
| **Semantic Relation Level:** | _rdfs:superclassOf_ |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | Allotrope: <http://purl.allotrope.org/voc/afo/merged-OLS/REC/2019/05/10> |
| **Related Ontology Entities:** | _Device:_ <http://purl.allotrope.org/ontologies/equipment#AFE\_0000354> |
| **Mapping Elucidation:** | _Allotrope is based on BFO; as such it is pertinent to expect the alignment to target BFO/Allotrope:Material Entity or one of its subclasses. Notably there is a class labelled 'device' might appears to be a perfect candidate for an alignment, with no real contenders._ _Both the definitions and elucidations of Allotrope:__Device__ _and its subclasses seem pertinent, and in line with both the standard conception of device and, more importantly, the proposed OntoCommons bridge-concept, Device. However, it should be noted that an alternative label for the class is 'machine', which might suggest a different semantic relationship. Then again, one of the target's subclasses is Alltrope:Plumbing Equipment; as such, the target class seems Equivalent to that defined by the proposed bridge-concept. Arguably, the subclass Allotrope:Injection Device Component might raise some eyebrows, but we assume that its individuals are Devices themselves._ |
| **Semantic Relation Level:** | _rdfs:equivalentClass_ |
| **Mapping Axioms:** | _TBD_ |


|     |     |
| --- | --- |
| **Target Ontology:** | BWMD: <https://gitlab.cc-asp.fraunhofer.de/EMI\_datamanagement/bwmd\_ontology/-/blob/master/docs/create\_new\_domain\_ontology\_using\_BWMD\_mid.md> |
| **Related Ontology Entities:** | _Equipment:_ <https://www.materials.fraunhofer.de/ontologies/BWMD\_ontology/mid#BWMD\_00070> |
| **Mapping Elucidation:** | _BWMD, like Allotrope, is based on BFO. The vast majority of the considerations regarding Allotrope:Device can be applied, mutatis mutandis, to BWMD:Equipment, though in this case there seem to be other candidates for an informative alignment with the proposed OntoCommons bridge-concept, Device, though not as appropriate. A further difference is that there is less (but still substantial) evidence from the taxonomical tree and the relevant documentation, and BWMD:Equipment arguably appears to be broader;_ _as such, the target class seems a Superclass of the one which is defined by the proposed bridge-concept__._ |
| **Semantic Relation Level:** | _rdfs:subClassOf_ |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | IOF-Core: <https://github.com/NCOR-US/IOF-BFO> |
| **Related Ontology Entities:** | _Machine:_ \<https://www.industrialontologies.org/ontology/core/Core/Machine\> |
| **Mapping Elucidation:** | _IOF-Core, like some of the MLOs considered above, is based on BFO, hence -once again- some general considerations concerning where to start looking etc. apply. In this case, there do not seem to be candidates for a meaningful and informative connection beside IOF-Core:Machine, yet the documentation, and holistic information which can be inferred from the taxonomical tree, is far from conclusive. Intuitively, the proposed OntoCommons bridge-concept is a subclass of IOF-Core:Material Artifact, and a superclass of IOF-Core:Machine, and its "closer" traits-wise to the latter compared to the former._ |
| **Semantic Relation Level:** | _rdfs:superClassOf_ |
| **Mapping Axioms:** | _TBD_ |

|     |     |
| --- | --- |
| **Target Ontology:** | Saref: <https://saref.etsi.org/core/v3.1.1/> |
| **Related Ontology Entities:** | _Device:_ <https://saref.etsi.org/core/Device> |
| **Mapping Elucidation:** | _Saref i__s arguably a straightforward ontology, and Saref:Device seems a good candidate for a connection with the proposed OntoCommons bridge-concept, Physical Quantity. Both the linguistic label and the relevant documentation are evidence in favour of the alleged connection, and there do not seem to be other appropriate candidates. The only point worth focusing on is the target's subclass Saref:Appliance; in order for the target to be equivalent to the proposed concept, Saref's Appliances mustn't be softwares, but physical systems: given the relevant subclass' elucidation, that seems to be the case._ |
| **Semantic Relation Level:** | _rdfs:equivalentClass_ |
| **Mapping Axioms:** | _TBD_ |

## EXISTENT CONCEPT: MATERIAL ENTITY (BFO)

### General Concept Info:

| **IRI:** | _<http://purl.obolibrary.org/obo/BFO\_0000040>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | _A material entity is an independent continuant that at all times at which it exists has some portion of matter as continuant part._ <br>_Examples of Usage:_ a human being, the undetached arm of a human being, an aggregate of human beings. |
| **Labels:** | Material Entity |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _Building Ontologies with BFO:_ "material entity is an independent continuant that has some portion of matter as part. It is thus an independent continuant that is spatially extended in three dimensions, and that continues to exist through some interval of time, however short.". |

## EXISTENT CONCEPT: NON AGENTIVE PHYSICAL OBJECT (DOLCE)

### General Concept Info:

| **IRI:** | _<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#NonAgentivePhysicalObject>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A Non-Agentive Physical Object is a physical object to which intentions, believes and desires are not ascribed. <br> _Examples of Usage:_ a pebble, a house, a computer, a human body. |
| **Labels:** | _NonAgentivePhysicalObject_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _Dolce D18:_ "within Physical Objects, a special place have those those to which we ascribe intentions, beliefs, and desires. These are called Agentive, as opposite to Non-agentive. Intentionality is understood here as the capability of heading for/dealing with objects or states of the world26. This is an important area of ontological investigation we haven't properly explored yet, so our suggestions are really very preliminary". |

## EXISTENT CONCEPT: DEVICE (EMMO)

### General Concept Info:

| **IRI:** | _<http://emmo.info/emmo/middle/manufacturing#EMMO\_494b372c\_cfdf\_47d3\_a4de\_5e037c540de8>_ |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | An engineered object which is instrumental for reaching a particular purpose through its characteristic functioning process, with particular reference to mechanical or electronic equipment. <br> From Old French "deviser", meaning: arrange, plan, contrive. Literally "dispose in portions," from Vulgar Latin "divisare", frequentative of Latin dividere, meaning "to divide". |
| **Labels:** | _Device_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _European Materials Modelling Ontology v. 1.0.0 alpha 2_ |

## EXISTENT CONCEPT: DEVICE (Allotrope)

### General Concept Info:

| **IRI:** | <http://purl.allotrope.org/ontologies/equipment#AFE\_0000354> |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A device is an artifact that is designed to perform a function primarily by means of its mechanical or electrical nature. <br> A device has a designed form or physical structure. This distinguishes a device from a chemical and a biological artifact, that are typical bulk or portions of materials without a designed form. <br> http://purl.allotrope.org/voc/afo/REC/2021/03/aft <br> http://purl.allotrope.org/voc/afo/perspective/REC/2021/03/system <br> http://purl.allotrope.org/voc/afo/REC/2018/07/aft |
| **Labels:** | _Device; EngineeredArtifact; Machine_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No Instances._ |

## EXISTENT CONCEPT: EQUIPMENT (BWMD)

### General Concept Info:

| **IRI:** | <https://www.materials.fraunhofer.de/ontologies/BWMD\_ontology/mid#BWMD\_00070> |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | _Some kind of equipment, e.g. which is used in research or production systems._ |
| **Labels:** | _Equipment_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No instances._ |

## EXISTENT CONCEPT: MACHINE (IOF-Core)

### General Concept Info:

| **IRI:** | <https://www.industrialontologies.org/ontology/core/Core/Machine> |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | Man-made artifact containing a set of physically-connected components that work together as a unit with some designed function. <br> Other common definitions: <br> 1. ISO 22096:2007(en): Is a mechanical system designed expressly to perform a specific task, such as the forming of material or the transference and transformation of motion, force or energy. <br> 2. Is a mechanical structure that uses power to apply forces and control movement to perform an intended action. Machines can be driven by animals and people, by natural forces such as wind and water, and by chemical, thermal, or electrical power, and include a system of mechanisms that shape the actuator input to achieve a specific application of output forces and movement [Wikipedia]. <br> Material artifact that contains a number of physically connected components that work together to realize some function. <br> Machine x implies x is a Material Artifact that 'has continuant part at all times', a plurality of Material Components c (c\>1) that are 'material basis at all times' of the 'function' f that 'inheres in' x. |
| **Labels:** | _Machine_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No Instances._ |

## EXISTENT CONCEPT: DEVICE (Saref)

### General Concept Info:

| **IRI:** | <https://saref.etsi.org/core/Device> |
| --- | --- |
| **OWL Type:** | _Class_ |
| **Concept Elucidation:** | A tangible object designed to accomplish a particular task. In order to accomplish this task, the device performs one or more functions. For example, a washing machine is designed to wash (task) and to accomplish this task it performs a start and stop function. |
| **Labels:** | _Device_ |

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | _No instances._ |
