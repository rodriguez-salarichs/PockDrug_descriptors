# PockDrug descriptors (druggability)
This script calculates the necessary descriptors for calculating the druggability of a protein pocket using the PockDrug function. Also, it creates the matrix file used in PockDrug.R* to solve the druggability of a portein pocket.

*PockDrug druggability function was published in "A., Regad, L., Xhaard, H., Petitjean, M., & Camproux, A. C. (2015). PockDrug: a model for predicting pocket druggability that overcomes pocket estimation uncertainties. Journal of chemical information and modeling, 55(4), 882-895." and the software can be found in its Supporting information.


If you use this script, please cite the website https://github.com/rodriguez-salarichs/PockDrug_descriptors_calculations/

#########################################################################################
    IMPORTANT: This script uses RADI to calculate the geometric descriptors 
      (RADIUS_CYLINDER, SMALLEST_SIZE, VOLUME_HULL, RADIUS_HULL, DIAMETER_HULL and SURFACE_HULL) 
#########################################################################################
   
   script.sh [options] -i file.pdb -f RADI -n  NAME

    options:

      -i Input file (FOrmat: PDB)
      -f address of RADI executable
      -n Name of pocket (Default: 1)
      -h Print this help

    version:

      version : 1.0
      author : Dr. Javier Rodriguez-Salarichs
      
      
