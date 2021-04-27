# SCMAC_MRI_templates
For any issues or questions, contact Shihui Xing at xingshih@mail.sysu.edu.cn.
## Description
The Sun Yat-sen university cynomolgus macaque (SCMAC) MRI templates includes both T1w (SMAC_MRI63) and DTI (SMAC_DTI63) templates of the cynomolgus macaque brain. They were created based on 63 young male cynomolgus monkeys using the freely available softwares ANTs (http://stnava.github.io/ANTs/) and DTI-TK (http://dti-tk.sourceforge.net)in a common spaces. For more information on the template creation process, see our paper.

This README file provides an overview of the SMAC_MRI template together with its associated tissue probabilistic maps, and DTI template.

# Citation
If you use this repository, please cite the paper below:

# Download

To download from the terminal, navigate to the directory where you want to store the SCMAC_MRI_templates repository. Then, copy and paste this command:
```bash
git clone http://github.com/xsh518/SCMAC_MRI_templates.git
```

Otherwise, on the [SCMAC_MRI_templates repository homepage](https://github.com/xsh518/SCMAC_MRI_templates), click the green button "clone or download"...


# SCMAC_MRI_template Files

All volume files are stored in the nifti (.nii.gz) format.

- SCMAC_MRI63 volumes
	+ SCMAC_MRI volumes
		- SMAC T1w template - **SCMAC-MRI63_Asymmetric.Template.nii.gz**
		- SMAC T1w template - **SCMAC-MRI63_Symmetric.Template.nii.gz**
	+ Probabilisitic Tissue Segmentation Maps
		- Gray matter - **SCMAC-MRI63-grey_Asymmetric.nii.gz**
	    - Gray matter - **SCMAC-MRI63-grey_Symmetric.nii.gz**
		- White matter - **SCMAC-MRI63-white_Asymmetric.nii.gz**
		- White matter - **SCMAC-MRI63-white_Symmetric.nii.gz**
		- Cerebral spinal fluid - **SCMAC-MRI63-csf_Asymmetric.nii.gz**
		- Cerebral spinal fluid - **SCMAC-MRI63-csf_Asymmetric.nii.gz**
	    
- SCMAC_DTI63 volumes
	+ SCMAC_DTI volumes (asymmetric)
	    - FA.asymmetric - **SCMAC-DTI63-Fa_Asymmetric.nii.gz**
	    - Tr.asymmetric - **SCMAC-DTI63-Tr_Asymmetric.nii.gz**
	    - AD.asymmetric - **SCMAC-DTI63-Ad_Asymmetric.nii.gz**
	    - RD.asymmetric - **SCMAC-DTI63-Rd_Asymmetric.nii.gz**
	+ SCMAC_DTI volumes (symmetric)
	    - FA.symmetric - **SCMAC-DTI63-Fa_Symmetric.nii.gz**
	    - Tr.symmetric - **SCMAC-DTI63-Tr_Symmetric.nii.gz**
	    - AD.symmetric - **SCMAC-DTI63-Ad_Symmetric.nii.gz**
	    - RD.symmetric - **SCMAC-DTI63-Rd_Symmetric.nii.gz**
	    
	    
