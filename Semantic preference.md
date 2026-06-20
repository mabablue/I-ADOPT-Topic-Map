
- **What is expected:** In this section, you define the preferred ontologies and controlled vocabularies that will be used to generate the permanent identifiers (URIs) for your data components.
    

### A. Property Vocabulary Specification

- **Default:** `QUDT Quantity Kinds Ontology ([http://qudt.org/vocab/quantitykind/](http://qudt.org/vocab/quantitykind/))`
- **User Guide:** _"By default, we map all physical, chemical, and biological properties to the global **QUDT** standard to ensure international cross-domain interoperability. If your community strictly requires a different property vocabulary (e.g., PATO, CF Standard Names, or BODC P01), please select other."_
      

### B. Entity / Object of Interest Vocabulary Specification

- **What is expected:** Because entities span different scientific disciplines, you must select the vocabulary that best fits the domain of your variable.
- **User Guide:** _"Select the domain-specific vocabulary that best represents the 'things' or substances you are observing. If you cannot find your specific domain or vocabulary in our pre-defined list, you can manually register a new one by providing its name and its global identifier prefix."_

#### Custom Vocabulary Registration (If Domain/Vocabulary Not Found):

If the user selects **"Other / Not Listed"** from the drop-down menu, display two mandatory text fields:

1. **Vocabulary Name:** _(e.g., "Agrovoc", "Medical Subject Headings")_
    
2. **Vocabulary Base URI / Namespace Identifier:** The permanent URL or registry prefix used to resolve terms _(e.g., `[http://aims.fao.org/aos/agrovoc/](http://aims.fao.org/aos/agrovoc/)` or `mesh`)_.