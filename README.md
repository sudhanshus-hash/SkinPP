# SkinPP: In Silico Prediction and Design of Skin Penetrating Peptides

SkinPP is a computational web server developed for predicting and designing efficient skin penetrating peptides, also known as SPPs.

Skin penetrating peptides are short peptide sequences that can cross the skin barrier and may be useful as therapeutic agents or as delivery vehicles for drugs, peptides, proteins, and other bioactive molecules. SkinPP helps researchers identify, design, mutate, and analyze peptides with potential skin penetration ability.

Web Server: https://webs.iiitd.edu.in/raghava/skinpp/



## Citation

This tool and dataset is also available on Zenodo at https://doi.org/10.5281/zenodo.20284775


## About the Research

Skin is one of the most important barriers for drug delivery. Although topical and transdermal delivery are attractive because they are non-invasive and patient-friendly, many therapeutic molecules cannot efficiently penetrate the skin barrier.

Skin penetrating peptides are useful because they can help transport therapeutic agents across the skin. These peptides may improve the delivery of drugs, peptides, proteins, and other therapeutic molecules.

SkinPP was developed as an in silico method to predict and design skin penetrating peptides. The tool allows users to analyze peptide sequences, generate mutant analogues, scan full-length proteins, identify skin penetrating peptide motifs, and calculate physicochemical properties.

Data Compilation: The dataset section of the server states that the dataset will be made available after publication.

Methodology: SkinPP uses computational prediction approaches to classify peptides as skin penetrating or non-skin penetrating. The server also supports peptide design, mutation-based analogue generation, protein scanning, motif scanning, and physicochemical property calculation.



## Key Features

### 1. Skin Penetrating Peptide Prediction

Predictive Modeling: Allows users to submit peptide sequences and predict whether they are likely to be skin penetrating peptides.

Multiple Peptides: Users can submit a list of peptides in bulk and predict skin penetration potential for multiple sequences at once.

Application: This module is useful for screening peptide libraries and selecting promising SPP candidates for experimental validation.



### 2. Design Peptide Module

Single-Mutant Analogue Generation: This module generates all possible single-mutant analogues of a user-submitted peptide.

Analogue Prediction: Each generated analogue is predicted as skin penetrating or non-skin penetrating.

Motif-Based Option: Users can also use motif information for prediction by choosing the SVM plus motif-based method.

Physicochemical Properties: The server calculates physicochemical properties for each mutant peptide analogue.

Sorting Option: Peptide analogues can be displayed in sorted order based on desired physicochemical properties.

Application: This module helps users design improved peptide analogues with better predicted skin penetration ability.



### 3. Protein Scanning Module

Protein Fragment Generation: This module generates all possible overlapping peptide fragments from a user-submitted protein sequence.

SPP Prediction: Each overlapping peptide fragment is predicted as skin penetrating or non-skin penetrating.

Mutant Analogue Generation: The module can also generate single-mutant analogues of overlapping peptide fragments.

Physicochemical Analysis: The server calculates properties for overlapping peptides and their analogues.

Application: This module is useful for discovering potential skin penetrating regions within larger proteins.



### 4. Motif Scan Module

SPP Motif Identification: Allows users to identify skin penetrating peptide motifs in protein or peptide sequences.

Sequence Pattern Search: The motif scan module helps locate sequence regions that may be associated with skin penetration ability.

Application: This module can support mechanistic analysis and peptide optimization by identifying important motif-like regions.



### 5. Integrated Web-Bench

SkinPP provides multiple user-friendly tools for SPP analysis and design:

- Design Peptide
- Multiple Peptides
- Protein Scanning
- Motif Scan
- Physicochemical Property Calculation
- Dataset
- Help Page
- Team
- Contact

The server is designed to support researchers working in peptide-based delivery and skin penetration studies.



## Applications

Skin Penetrating Peptide Discovery: SkinPP can help identify peptide sequences with potential skin penetration ability.

Transdermal Drug Delivery: Predicted SPPs may be useful as carriers for therapeutic molecules across the skin barrier.

Peptide Therapeutics: The tool can support the design of peptide-based therapeutic agents with improved skin delivery potential.

Protein-Derived Peptide Screening: The protein scanning module can help identify SPP-like regions from larger protein sequences.

Peptide Optimization: The design peptide module can generate and rank mutant analogues based on predicted SPP activity and physicochemical properties.

Drug Delivery Research: SkinPP provides a computational framework for designing delivery peptides for topical and transdermal applications.



## Contact and Authors

Prof. Gajendra P. S. Raghava  
Professor and Head  
Department of Computational Biology  

Indraprastha Institute of Information Technology Delhi  
Okhla Phase III  
New Delhi, India  

Email: raghava@iiitd.ac.in  

Web Page: http://webs.iiitd.edu.in/raghava/



## Developers


Developers listed on the server:

Deepika Mathur  
Graduate Student  

Ayesha Mehta  
Project Fellow  
