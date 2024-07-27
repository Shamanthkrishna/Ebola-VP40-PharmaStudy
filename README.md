# Computational Research Using Phytochemicals from the Acacia Caven Plant to Combat the VP40-Functionalized Ebola Virus Illness

**Published Paper:** [Link to Published Paper]([https://example.com/your-paper-url](https://journals.innovareacademics.in/index.php/ijms/article/view/46620))

## Overview
This project aims to explore the potential of phytochemicals from the Acacia caven plant as therapeutic agents against the VP40 protein of the Ebola virus. The study involves several key steps:

1. Phytochemical Identification: Identification and retrieval of 10 phytochemicals from Acacia caven.
2. ADME and Toxicity Analysis: Evaluating the pharmacological properties of the phytochemicals using various computational tools.
3. Homology Modeling: Modeling the VP40 protein structure using homology modeling techniques.
4. Protein-Ligand Docking: Performing molecular docking to predict the binding affinity of phytochemicals with the VP40 protein.



## Data Used
Phytochemicals: Data on phytochemicals was collected from the IMPPAT database and PubChem.
Protein Data: The VP40 protein sequence was obtained from the NCBI database, and the model was retrieved from the PDB.
Computational Tools: The following tools were utilized for analysis:
1. IMPPAT: For phytochemical data retrieval.
2. PubChem: For obtaining chemical identifiers and canonical smiles.
3. SWISS-ADME, ADMETLAB, ChemAGG, and ProTox: For ADME and toxicity analysis.
4. Biovia Discovery Studio: For protein purification and docking studies.
5. PyRx: For molecular docking.

## Process
**1. Phytochemical Data Collection:**
- Collected 10 phytochemicals from Acacia caven using IMPPAT.
- Retrieved canonical smiles and PubChem IDs from PubChem.
- Compiled data into an Excel file.

**2. ADME and Toxicity Analysis:**
Used SWISS-ADME, ADMETLAB, and ProTox to assess drug-likeness, absorption, distribution, metabolism, excretion, and toxicity.
Downloaded results and incorporated them into the Excel file.

**3. Homology Modeling:**
Retrieved VP40 protein sequence from NCBI and modeled the structure using SwissModel.
Purified the homology model using Biovia Discovery Studio.

**4. Molecular Docking:**
Prepared protein and ligand files for docking studies.
Performed docking using PyRx, analyzed binding affinities, and visualized interactions with Biovia Discovery Studio.

## Folders and Their Contents

1. **`/Protein Structures/`**  
   Contains protein structure files in PDB format. These files describe the 3D structure of proteins.
   - `4ldd.pdb`
   - `pu_4ldd.pdb`
   - `pu_4ldd,pdb.pdb`

2. **`/Result of Docking/`**  
   Contains CSV files with results from docking simulations, showing how ligands bind to the protein.
   - `docking complete.csv`
   - `docking table.csv`

3. **`/Visualization of Resultant Ligands/`**  
   Contains visualizations of the ligand interactions with the protein. Subfolders for each ligand type include 2D and 3D representations, as well as interaction diagrams.
   - **`Geranylacetone/`**
     - `2D Geranyl.png`
     - `3d geranyl.png`
     - `interaction.png`
   - **`Heptacosane/`**
     - `2d heptacosane.png`
     - `3d heptacosane.png`
     - `interaction heptacosone.png`
   - **`Pimara/`**
     - `2d pimara.png`
     - `3d pimara.png`
     - `interaction pimara.png`

4. **`/Docked Ligands/`**  
   Contains PDB files of docked ligands.
   - `geranyl.pdb`
   - `heptacosane.pdb`
   - `pimara.pdb`

5. **`/Homology Modelling/`**  
   Contains PDB files for the homology models of the VP40 protein.
   - `(P)Vp40HomoModel.pdb`
   - `Vp40HomoModel.pdb`

6. **`/Ligand/`**  
   Contains SDF files for different ligands used in the study, including conformers and 2D structures.
   - Various SDF files (e.g., `11636.sdf`, `Conformer3D_CID_11635.sdf`)

7. **`/Pharmacological studies/`**  
   Contains an Excel file with pharmacological study data.
   - `Project.xlsx`

8. **`/Pictures for Research Paper/`**  
   Contains images and figures for inclusion in the research paper, such as protein properties, ligand structures, and various plots.
   - Examples: `acacia caven.jpg`, `admesar.png`, `boiled egg.png`, `secondary structure.gif`

### Individual Files

- **`admetlab2.0.csv`**  
  Contains data related to ADMET (Absorption, Distribution, Metabolism, Excretion, and Toxicity) properties of compounds.

- **`Boiled Egg.png`**  
  Image related to a visual representation or figure in the project.

- **`chemagg.csv`**  
  Contains data related to chemical aggregation or similar analysis.

- **`CSSDF.sdf`**  
  An SDF file, containing chemical structure data.

- **`Project_Observation.txt`**  
  Text file with observations or notes about the project.

- **`Published Paper.pdf`**  
  The published research paper related to the project.

- **`swissadme (1).csv`**  
  Contains ADME-related data from SwissADME, a tool for predicting drug-likeness properties.

## Conclusion
The study identified several bioactive compounds from Acacia caven with potential inhibitory effects on the VP40 protein of the Ebola virus. Notably, Pimara-8(14),15-diene, Heptacosane, and Geranylacetone exhibited high binding affinities. These findings suggest that these phytochemicals could be explored further as potential treatments for Ebola Virus Disease (EVD). Future research should include in vitro and in vivo studies to validate these findings and explore the full therapeutic potential of these compounds.

## Acknowledgments
I thank Ms. Susha D and Mr. Sameer Sharma for their guidance on the research paper and BioNome Pvt. Ltd. for providing computational facilities and assistance.

## Conflicts of Interest
The author declares no conflict of interest.

## Funding
The research received no external funding
