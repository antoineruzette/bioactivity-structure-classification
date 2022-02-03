# Integrated Bioinformatics Project
<i> <b> Integrated Bioinformatics Project </b>, MSc in Bioinformatics, KU Leuven, 2021, Antoine Ruzette, Taofeng Bu, Kevin Francis Menezes and Guoshuo Ye </i>

In the present project, we investigate the molecular structure - activity relationship of molecules binding to AMPK alpha 1 sub-unit to discriminate the active from the non-active ones. We developed two classification pipeline using, respectively, an Artificial Neural Network and a Random Forest Classifier. As our models learn in a high-dimensional context, both pipelines were enhanced with a LASSO method to reduce the variable space. Thus, the overfitting risk can be drastically reduced.  


Content: 

- ETL of publicly available data from ChEMBL and PubChem: accession, missing and duplicates molecules removal, molecular descriptors generation from the SMILES (using the **PaDEL** package)
- Exploratory analysis: data balance, multi-colinearity investigation, **PCA** and **tSNE** vizualisation
- Modeling the molecular structure - activity relationship: combination of **LASSO** dimension reduction with **Random Forest Classifier** and **Artificial Neural Network** using, respectively, **sklearn** and **TensorFlow** (with its Keras API) 
