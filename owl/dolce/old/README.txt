________________________________________________________________________________
Copyright (C) 2005 ISTC-CNR, Laboratory for Applied Ontology

This library is free software; you can redistribute it and/or
modify it under the terms of the GNU Lesser General Public
License as published by the Free Software Foundation; either
version 2.1 of the License, or (at your option) any later version.

This library is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU
Lesser General Public License for more details.
________________________________________________________________________________

This directory contains the first version of the newly factorized version of DOLCE-Lite-Plus. A thorough description of the library is contained in the comment to "DLP" module, which imports from all other modules.

In order to load the ontologies locally, you need to change the import pathname in order to reflect the position of the files in your own directories.

For example, the current import pathname of DO+DnS in the files that use that module is:

    <owl:imports rdf:resource="http://www.loa-cnr.it/ontologies/DO+DnS_397.owl"/>

You should change it as follows:

    <owl:imports rdf:resource="file:/YOURDIR1/YOURDIR2/YOURDIRn/DO+DnS_397.owl"/>
/>


Currently, the module hierarchy (for version 3971) is as follows:


									_______>DOLCE-Lite<___________
									|		 	|				|
					    	TemporalRel<_____ExtDnS_________>SpatialRel
    							  	 		 |	  |				
    			   	Information______________|  Modal	    	
    					|			 	 	 |	  |				
    				  Social	FunctPart<___|_   |				
    				  	|			|		  |___|				
    				  	|		  Plans		  Common			
						|			|			|				
						|_________ DLP__________|


Current state (for 397) of the DLP library:

DL Expressivity (for the complete library): SHION(D) [within OWL-DL]
S == ALCR+ 
AL - Attribute Logic: Conjunction, Universal Value Restriction, Limited Existential Quantification 
C - Complement (together with AL allows Disjunction, Full Existential Quantification) 
R+ - Role Transitivity 
H - Role Hierarchy 
I - Role Inverse 
O - Nominal 
N - Unqualified Number Restrictions 
(D) - Datatypes  

Total Number of Classes: 205 
Total Number of Datatype Properties: 4 
Total Number of Object Properties: 311 
Total Number of Annotation Properties: 2 
Total Number of Individuals: 39

______________________________________________________________________________
DOLCE ontology and its extensions are copyright of the Laboratory for Applied Ontology, Institute of Cognitive Sciences and Technology of the Italian National Research Council.
They are released under LGPL (Lesser GNU Public License): http://www.gnu.org/copyleft/lesser.html.
______________________________________________________________________________

For any help, license information, bugs, etc., joint initiatives, please contact Aldo Gangemi, mailto://aldo.gangemi@istc.cnr.it