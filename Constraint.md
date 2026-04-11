
#Status/DesignPhase 

Constraint needs to be minimally represented using blank nodes:

[
      a iop:Constraint ;
      rdfs:label "constraint label" ;
      iop:constrains ex:Entity
    ],

to reuse an existing concept it must be modelled as a type of this concept like this:

[
      a iop:Constraint , ex:ConceptURI ;
      rdfs:label "constraint label" ;
      iop:constrains ex:Entity
    ],

However, the constraint is for now only a black box; mostly they are observations themselves.