<h1 align="center">
  <br>
    Dose response curve (DRC) workflow
    <br>
</h1>

### Introduction

This workflow is aimed to generate curve fitting values and plots for each compound contained in the input table. It contains few user-defined parameters for the acceptance of the generated curve and relative IC50/EC50. It is based on a R script.

### Data file
The KNIME workflow starts with reading a KNIME binary file (*.table). An exemplary table can be seen in [ExampleData.table](ExampleData.table). 

In principle, modification of the *read_table* node to a *read_csv* or *Excel_read* node in the workflow can alter the input file to a CSV or and Excel sheet respectively.
