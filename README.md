# vTSN_Subnets
Brain structural sub-networks parcellated based on the vTSN-coexpression correlation profiles

![alt text](https://github.com/BrainWanderLab/vTSN_Subnets/vTSN_pipeline.jpg?raw=true)
The vTSN_Subnets are identified based on the following steps:

1. Construction voxel-based Texture Similarity Network (vTSN)

2. Identifing the gene coxepression modules using WGCNA

3. Calculate partial correlation coeffients between vTSN and each module's eigengene nodal-by-nodal

4. Parcellation of the brain regions based on the 246 × 13 vTSN-eigengene correlation matrix using hierarchical agglomerative clustering

5. Refined parcellation of the sub-networks into more small ones

Detailed information on the parcellation was described in the article "Voxel-based texture similarity networks reveal individual variability and correlate with biological ontologies, Neuroimage, 2024"

