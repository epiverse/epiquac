# epiQuaC
**epiQuaC** (<u>Epi</u>demiological Data <u>Qua</u>lity <u>C</u>ontrol) is a web-native application for epidemiological data quality control (QC). 

_epiQuaC_ takes as input: 1) Data (JSON) to perform the QC checks against, 2) data dictionary (JSON Schema) specifying the expected data structure and constraints, and 3) QC rules (CSV) that define the specific QC checks to be performed. _epiQuaC_ then processes the data and generates a comprehensive human-readable QC report (XLSX) that highlights any discrepancies or issues found in the dataset according to the constraints specified in the input data dictionary and QC rules.
