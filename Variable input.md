To be provided by the user following the guideline below:

## 1. Description of the Variable

- **What is expected:** A clear, plain-language summary of what is being measured or observed. This helps contextualize the data point before breaking it down into semantic components.
    
- **User Guide:** _"Describe in one or two sentences what this data point actually represents in your study."_
    
- **Example:** _"The potential temperature of sea water brought adiabatically to the surface."_
    

## 2. Ultimate Object of Interest

- **What is expected:** The primary "thing" (phenomenon, entity, or substance) that the property belongs to. In I-ADOPT, this is the core entity you are looking at.
    
- **User Guide:** What is the main entity or substance you are analyzing?"
    
- **Example:** `Sea water` (or `Salt` if measuring absolute salinity mass fraction).
    

## 3. Property of the Object

- **What is expected:** The specific characteristic, quality, or trait of the Object of Interest that is being quantified or observed.
    
- **User Guide:** _"What specific physical, chemical, or biological trait of the object are you measuring? (e.g., height, temperature, mass fraction, presence, color)."_
    
- **Example:** Temperature.
    

## 4. Conditions (Constraints / Methods)

- **What is expected:** Any critical context, restrictions, dependencies, or baseline adjustments required to make the measurement meaningful.
    
- **User Guide:** _"Are there any specific conditions, reference points, or constraints under which this measurement is valid? (e.g., referenced to sea level, adjusted to 0 dbar, measured at a specific temperature scale)."_
    
- **Example:** `Adiabatically adjusted to a reference pressure of 0 dbar (sea surface)`.
    

## 5. Value Representation & Type

- **What is expected:** How the computer should interpret the actual data values in the dataset (e.g., data type layout).
    
- **User Guide:** _"How is this data stored in your file? Is it a number (Float, Integer) or a descriptive label (String/Text)?"_
    
- **Example:** `Float` (Decimal number).
    

## 6. Units of Measurement (If Applicable)

- **What is expected:** The standard unit scale used for numerical values, ideally mapping to a known vocabulary like QUDT or UDUNITS.
    
- **User Guide:** _"If the data is numerical, what unit is it measured in? Please specify even if it is dimensionless."_
    
- **Example:** `Degree Celsius (°C)` or `dimensionless (for PSU)`.
    

## 7. Range of Values (If Numerical)

- **What is expected:** The physical or mathematical boundaries (minimum and maximum expected values) of the data.
    
- **User Guide:** _"What are the minimum and maximum realistic boundaries for these numbers in your dataset? This helps us flag errors."_
    
- **Example:** `Min: -2.0`, `Max: 40.0`.
    

## 8. Controlled Vocabulary / Allowed Entries (If Qualitative)

- **What is expected:** If the data is text-based (categorical), the exact list of acceptable terms or the standard code list the data complies with.
    
- **User Guide:** _"If your data uses descriptive text categories instead of numbers, what is the exact list of allowed terms? If you are using an existing vocabulary list, please provide its name or link."_
    
- **Example:** `['low', 'medium', 'high']` or `Mapping to the SeaDataNet Beaufort Scale vocabulary`.