
# Agent

### General Concept Info:

| **IRI:** | _Suggested entity new IRI._ |
| --- | --- |
| **OWL Type:** | Class |
| **Concept Elucidation:** | 1.	Agents possibly participate in a process to achieve something (Objective). <br><br> 2.	Show agency over its action (intentional action) / active and efficient cause of certain effect. <br><br> 3.	Some agents are Anti-rigid from the OntoClean perspective. <br><br> 4.	Some agents act on behalf of another agent or person. |
| **Labels:** | Labels used to address the concept, ordered as: <br><br> skos:prefLabel: Agent <br><br> skos:altLabel: Actor

### Knowledge Domain Resources:

|     |     |
| --- | --- |
| **Related Domain Resources:** | -WordNet 3.1: “an active and efficient cause, capable of producing a certain effect”; “a substance that exerts some force or effect”. <br><br> -WikiData: “individual and identifiable entity capable of performing actions” (Q24229398).|
| **Comments:** | Standard Theory of Action: According to this view, a being has the capacity to exercise agency just in case it has the capacity to act intentionally, and the exercise of agency consists in the performance of intentional actions and, in many cases, in the performance of unintentional actions (that derive from the performance of intentional actions).  <br><br> First claim: intentional action is more fundamental than action itself: action derives from and is dependent on intentional action.  <br><br>  Second claim: Following Aristotle, both Davidson and Anscombe held the view that to act intentionally is to act for a reason, and that to act for a reason is to act in a way that can be rationalized by the premises of a sound practical syllogism, which consists, typically, of a major premise that corresponds to the agent’s goal and a minor premise that corresponds to the agent’s take on how to attain the goal. Furthermore, Davidson held the view that having an intention consists in having a desire and a belief that correspond to the major and the minor premise of the relevant syllogism. Many problems with standard theory of actions: Difficult to explain for non-human cases, e.g., lower order animals, collective, and artificial.  <br><br> Special note on artificial agency: If one presumes the standard theory, one faces the question of whether it is appropriate to attribute mental states to artificial systems. If one takes an instrumentalist stance (Dennett 1987: Ch. 2), there is no obvious obstacle to the attribution of mental states and intentional agency to artificial systems. According to realist positions, however, it is far from obvious whether or not this is justified, because it is far from obvious whether or not artificial systems have internal states that ground the ascription of representational mental states.   <br><br> Neo-classical explanations: event-causal approach, agency is to be explained in terms of event-causal relations between agent-involving states and events.  <br><br> agent-causal approach, agency is to be explained in terms of a kind of substance-causation: causation by the agent, construed as a persisting substance.  <br><br> According to a volitionist approach, agency is to be explained in terms of acts of the will, usually called “volitions”.  <br><br> Note: If we take event-causal approach seriously, agent does not deserve any special ontological treatment. “disappearing agent”, which is therefore weaker than agent-causal approach. |


## Alignments To Existing Ontologies:

|     |     |
| --- | --- |
| **Target Ontology:** | BFO: <http://purl.obolibrary.org/obo/bfo.owl> |
| **Related Ontology Entities:** |material entity http://purl.obolibrary.org/obo/BFO_0000040 <br><br> role http://purl.obolibrary.org/obo/BFO_0000023 |
| **Mapping Elucidation:** | Although material entities in BFO does not make any claim to have intentions or being anti-rigid, they participate in different processes. There is no restriction for some of them participating in a process to achieve something and such participation coming from their own volition, i.e., them showing agency. Being subclass of material entity however precludes agents being non-material e.g., dependent continuants or immaterial entities. Therefore, a conceptual agent e.g., some piece of software code labelled as agent cannot be classified under this bridge concept. The anti-rigidity of some agent points to them bearing a bfo:role.  |
| **Semantic Relation Level:** | rdfs:subClassOf |
| **Mapping Axioms:** | IRI rdfs:subClassOf <http://purl.obolibrary.org/obo/BFO_0000040> or (<http://purl.obolibrary.org/obo/BFO_0000040> and <http://purl.obolibrary.org/obo/BFO_0000196> some <http://purl.obolibrary.org/obo/BFO_0000023>) |

|     |     |
| --- | --- |
| **Target Ontology:** | DOLCE: <http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic> |
| **Related Ontology Entities:** |AgentiveSocialObject <http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#AgentiveSocialObject> <br><br> NonAgentiveSocialObject <http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#NonAgentiveSocialObject> 
 |
| **Mapping Elucidation:** | In DOLCE, AgentiveSocialObject (ASO) covers all entities to which intentionality can be ascribed. Therefore, some of them may participate in a process by their own volition to achieve something. However, ASO is a rigid concept. From the work of Masolo et al. [1], we can find the extension of DOLCE admitting the class Role under NonAgentiveSocialObject (NASO). dolce:Role is classified as anti-rigid (D3, D1, A2, A11 in [1]). <br><br> [1]	C. Masolo, L. Vieu, E. Bottazzi, and C. Catenacci, “Social Roles and their Descriptions,” 9th Int. Conf. Princ. Knowl. Represent. Reason., pp. 267–277, 2004, [Online]. Available: http://www.aaai.org/Papers/KR/2004/KR04-029.pdf.
  |
| **Semantic Relation Level:** | rdfs:subClassOf |
| **Mapping Axioms:** | IRI rdfs:subClassOf (<http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#AgentiveSocialObject> or <http://www.loa.istc.cnr.it/dolce/dolce-owl/DOLCEbasic#NonAgentiveSocialObject>) |

|     |     |
| --- | --- |
| **Target Ontology:** | EMMO: <http://emmo.info/emmo> |
| **Related Ontology Entities:** |Role: <> |
| **Mapping Elucidation:** |  |
| **Semantic Relation Level:** | rdfs:subClassOf |
| **Mapping Axioms:** | TBD |
