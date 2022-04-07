Dose response curve (DRC) workflow
Introduction
This workflow can be used to fit dose-response curves from normalised biochemical assay data (%Inhibition) using the HCS extension. This workflow needs R-Server to run in the back-end. 
IC50 values will not be extrapolated outside the tested concentration range
For activity classification the following criteria are applied:
- maximum (average % inhibion) >25 % and slope is >0 and IC50 > 5 �M or
- minimum (average % inhibion) >75 % 
Results are formatted for upload to the [European Chemical Biology Database](https://ecbd.eu/) (ECBD)

Data file
The KNIME workflow starts with reading a KNIME binary file (*.table). An exemplary table is contained in the workflow.

In principle, modification of the Table Reader node to a CSV Reader or Excel Reader node in the workflow can alter the input file to a CSV or and Excel sheet respectively.