# SCMAC_templates
For any issues or questions, contact Shihui Xing at xingshih@mail.sysu.edu.cn.

# Description
The Sun Yat-sen University Cynomolgus Macaque (SCMAC) templates includes both T1w (referring as to SCMAC_MRI63) and DTI (referring as to SCMAC_DTI63) templates of the cynomolgus macaque brain. They were created based on a cohort of 63 young male cynomolgus monkeys using the freely available softwares ANTs (http://stnava.github.io/ANTs/) and DTI-TK (http://dti-tk.sourceforge.net) respectively. For more information on the template creation process, see our paper.

This README file provides an overview of the SCMAC_MRI63 templates combined with its associated tissue probabilistic maps, and SCMAC_DTI63 templates in both asymmetric and symmetric versions.

# Download

To download from the terminal, navigate to the directory where you want to store the SCMAC_templates repository. Then, copy and paste this command as below:

```bash
git clone http://github.com/xingshih/SCMAC_templates.git
```

Alternatively, on the [SCMAC_templates repository homepage](https://github.com/xingshih/SCMAC_templates), click the button "clone or download"...


# SCMAC_templates Files

All volume files are stored in the nifti (.nii.gz) format.

- SCMAC_MRI63 volumes
	+ SCMAC_MRI volumes
		- T1w template asymmetric- **SCMAC-MRI63_Asymmetric.Template.nii.gz**
		- T1w template symmertic - **SCMAC-MRI63_Symmetric.Template.nii.gz**
	+ Probabilisitic Tissue Segmentation Maps
		- Gray matter asymmetric- **SCMAC-MRI63-grey_Asymmetric.nii.gz**
	    - Gray matter symmetric- **SCMAC-MRI63-grey_Symmetric.nii.gz**
		- White matter asymmetric- **SCMAC-MRI63-white_Asymmetric.nii.gz**
		- White matter symmetric- **SCMAC-MRI63-white_Symmetric.nii.gz**
		- Cerebral spinal fluid asymmetric- **SCMAC-MRI63-csf_Asymmetric.nii.gz**
		- Cerebral spinal fluid symmetric- **SCMAC-MRI63-csf_Asymmetric.nii.gz**
	    
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
	    
	    
