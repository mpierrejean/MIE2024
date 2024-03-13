## MIE 2024

Example of dashboard for monitoring variability of lab results in a clinical data warehouse. 

**Abstract**

Hospital laboratory results are a significant source of data for Clinical Data Warehouses (CDW). To ensure comparability between healthcare organizations and for use in research studies, the results must be interoperable. The LOINC (Logical Observation Identifiers, Names, and Codes) terminology provides a unique identification for local codes for lab tests, enabling interoperability. However, in real-world data, events occur over time and that can disrupt the distribution of lab result values. For example, equipment may be added to the analysis pipeline, a machine may be replaced, formulas may evolve due to new scientific knowledge, and legacy terminologies may be adopted. 
This article proposes a pipeline for creating an automated dashboard to monitor these events and data quality. To detect events in lab result signals, we used automatic changepoint detection methods such as PELT. 
For a given LOINC code, we can create a dashboard that summarizes the number of local codes mapped to it, and the number of patients (by sex, age, and hospital service) associated with the code, and visualize any events that disrupt the signal distribution. 
Some changes are clearly explained by biologists. 

Dashboard can be vizualised here : https://mpierrejean.github.io/MIE2024/
