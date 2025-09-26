# epiQuaC
**epiQuaC** (<u>Epi</u>demiological Data <u>Qua</u>lity <u>C</u>ontrol) is a web-native application for epidemiological data quality control (QC).

epiQuaC assists with two kinds of data quality control: 1) syntactic validation against a data dictionary (JSON Schema), and 2) custom QC checks defined by the user (CSV). Custom QC checks can include semantic rules that go beyond simple syntactic schema validation offered by JSON Schema. Custom QC checks also allows you to modify data according to a rule condition.

_epiQuaC_ takes as input: 1) Data (JSON) to perform the QC checks against, 2) data dictionary (JSON Schema) specifying the expected syntactic structure, and 3) QC rules (CSV) that define the specific QC checks as conditional rules. There are two types of conditional rules supported: 1) "Correction" rules that modify data when the condition is met, and 2) "Warning" rules that warn records when the condition is met.

epiQuaC outputs a detailed QC report (Excel) that annotates the data with syntactic validation errors and custom QC check results. The QC report is human-readable and can be shared with data providers for feedback and correction.
