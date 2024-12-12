This repository includes files for making a GLMM (Generalized Linear Mixed Model) with ROSMAP data. 
The following files are regarding data parsing:
- Output data/dependent variables: rosmap read - out, active_e, enhancer_e, methylation_e, repressed_e, transcription_e
- rosmap read - out was used to read the columns and determine data categories as it was difficult to open the            unzipped file. 
- The other files following are column files where individual data was extracted from the datasets.

- Input data/independent variables: rosmap read -ind, rosmap transfer - ind
- File rosmap transfer - ind was required to process this file due to its size.

Other files: z - glmm active edited, z - glmm enhancer, z - glmm methylation, z - glmm repressed, z - glmm transcription.
- These code for the mixed models and use the seaborn package for visualization.
- File z - glmm active1 demonstrates the code for a mixed model with the statsmodels package.
        
        
      
