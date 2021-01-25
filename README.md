# About Me

I am a HFSP Postdoctoral Fellow in Peter Sorger's group in the Laboratory of Systems Pharmacology at Harvard Medical School. I am developing methods to construct, calibrate and understand large kinetic models with hundreds to thousands of state variables and parameters. I apply these methods to study adaptive resistance in melanoma where I integrate structural, molecular and omics data to build detailed mechanistic models for precision medicine applications.

# Estimation Pipeline

Over the years, I have developed and contributed to several toolboxes that permit the efficient formulation, simulation and calibration of kinetic models of cellular signaling. All toolboxes are modular and interoperable, allowing the flexible definition of customizable analysis pipelines.

- Formulate your model using https://github.com/pysb/pysb
- Define your estimation problem using https://github.com/PEtab-dev/PEtab
- Solve your estimation problem using https://github.com/ICB-DCM/pyPESTO
  - To solve the optimization problem, use an efficient optimizer https://github.com/fides-dev/fides
  - To efficiently simulate and compute sensitivies for the model use https://github.com/AMICI-dev/AMICI
