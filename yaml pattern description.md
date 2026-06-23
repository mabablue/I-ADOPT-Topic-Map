type: Variable Design Pattern
id: https://github.com/mabablue/I-ADOPT-patterns-playground/blob/main/pattern/VDP04.yaml
name: property (geometric ratio)
comment: It is a ratio comparing to geometric properties.  
design: Use single entity in the object of interest.
involved_components:
  - property
  - object of interest (simple)
constrained_component: ~
associated_patterns: 
associated_mapping: ~
example: angle of attack
gh_issue: https://github.com/mabablue/I-ADOPT-examples-playground/issues/104


type: Variable Design Pattern
id: https://github.com/mabablue/I-ADOPT-patterns-playground/blob/main/pattern/VDP10.yaml
name: property (fundamental)
comment: Fundamental properties are physical quantities that is conventionally accepted as functionally independent of all others. Length is excluded, see VDP16.
design: Do not further decompose these terms. Use single object of interest.
instances:
  - thermodynamic temperature
  - time 
  - mass
  - amount of substance
  - luminous intensity
  - electric current
involved_components:
  - property
constrained_component: ~
associated_patterns: 
  - https://github.com/mabablue/I-ADOPT-patterns-playground/blob/main/pattern/VDP28.yaml
associated_mapping: ~
example: thermodynamic temperature
gh_issue: https://github.com/mabablue/I-ADOPT-examples-playground/issues/142