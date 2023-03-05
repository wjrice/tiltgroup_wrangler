# tiltgroup_wrangler
Purpose: Divide a dataset collected using Leginon into optics groups according to image shift.

Supports Relion 3/3.1/4 and Cryosparc 3/4.

Requires the following packages: numpy, scipy, scikit-learn, tkinter
For cryosparc export, requires pandas, dataset.py library from cryoSPARC.

Easiest install: Install eman2 2.91. Copy the dataset.py library from the cryosparc directory to the python site packages directory of the eman2 installation.

Input required: CTF star file with tiltgroups (downloaded from Leginon website)
For cryoSPARC, requires particles.cs and passthrough_particles.cs files from the refinemnt job.

Outputs star file in Relion 3.0 or 3.1/4 format, or cryosparc .cs file 
For cryosparc usage, replace the particles.cs or passthrough_particles.cs file with the output .cs file in the refinement directory.

Reference to cite:
Cheng A, Negro C, Bruhn JF, Rice WJ, Dallakyan S, Eng ET, Waterman DG, Potter CS, Carragher B. Leginon: New features and applications. Protein Sci. 2021 Jan;30(1):136-150. doi: 10.1002/pro.3967. Epub 2020 Nov 3. PMID: 33030237; PMCID: PMC7737759.
