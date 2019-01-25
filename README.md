# Level3Validation_Phase1
Level 3 validation work performed by Georgia Tech - 2018

The Georgia Tech Digital Building Laboratory (DBL) was retained by gbXML.org to assist in the development of Level 3 software requirements with the ultimate goal of 
developing a certification program for BIM software supporting this level of sophistication of data exchange. 
As an initial step, the DBL has developed a series of tests of the BIM – gbXML – BEM data exchange pipeline in order to assess current software capabilities for 
Level 3 model processing and data export.

This first phase of the Level 3 testing program involved developing a series of specific tests for assessing specific aspects of automated model processing and gbXML export. 
Both unit tests – (assessing specific modeling and export criteria) and system tests (testing overall process performance in the context of realistic modelling scenarios) 
were created. The functionality of the modeling software was used to model and export gbXML files which then imported into an energy solver. 
Specific data content as well as geometric and modeling intent were reviewed and compared at each step of the exchange pipeline. 
Revit 2018 was utilized for model development and to export gbXML instance files and OpenStudio (version 2.5.0) was employed to 
import the gbXML instance files into EnergyPlus. If gbXML instance files had to be compared with the gbXML schema, gbXML schema version 6.01 was referred.
