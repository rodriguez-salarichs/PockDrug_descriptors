# PockDrug_descriptors_calculations
This script calculates the PockDrug descriptors of a protein pocket. Also, it creates the matrix file used by PockDrug.R to solve the druggability of a portein pocket.

Ref: Borrel, A., Regad, L., Xhaard, H., Petitjean, M., & Camproux, A. C. (2015). PockDrug: a model for predicting pocket druggability that overcomes pocket estimation uncertainties. Journal of chemical information and modeling, 55(4), 882-895.



#########################################################################################
    IMPORTANT: This script uses RADI to calculate the geometric descriptors 
      (RADIUS_CYLINDER, SMALLEST_SIZE, VOLUME_HULL, RADIUS_HULL, DIAMETER_HULL and SURFACE_HULL) 
#########################################################################################
   
   script.sh [options] -i file.pdb -f RADI

    options:

      -i PDB file
      -f RADI executable
      -h Print this help

    version:

      version : 0.1
      author : Dr. Javier Rodriguez-Salarichs
      
      
