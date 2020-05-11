
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3817045.svg)](https://doi.org/10.5281/zenodo.3817045)


# Indian brain templates (IBTs) and atlases (IBTAs)

ver = 1.0

----------------------------------------------------------------------

This dataset is described in detail in the following
study:

  A series of five population-specific Indian brain templates and
  atlases spanning ages 6 to 60 years

  by Bharath Holla, Paul A. Taylor, Daniel R. Glen, John A. Lee,
  Nilakshi Vaidya, Urvakhsh M. Mehta, Ganesan Venkatasubramanian,
  Pramod Pal, Jitender Saini, Naren P. Rao, Chirag Ahuja, Rebecca
  Kuriyan, Kumaran Kalyanram, Debashish Basu, Kartik Kalyanram, Amit
  Chakrabarti, Dimitri Papadopoulos Orfanos, Gareth J. Barker, Robert
  W. Cox, Gunter Schumann, Rose Dawn Bharath, Vivek Benegal

<p>
<a href="https://doi.org/10.1101/2020.05.08.077172">
   <img src="https://img.shields.io/badge/bioRxiv-preprint-67baea.svg" />
</a>
</p>

## This sample set was divided into 5 groups based on age: #
```
  C1 :  6-11 yrs
  C2 : 12-18 yrs
  C3 : 19-25 yrs
  C4 : 26-40 yrs
  C5 : 41-60 yrs
  ```
	
## Each age-group, the following IBTs and IBTAs are provided #
Example file structure for C1 group:
```
  IBT_DATASETS
            ├──ibt_C1_template_mean.nii.gz
            ├──ibt_C1_atlas_mpm_fs2000.nii.gz
            ├──ibt_C1_atlas_mpm_fs2009.nii.gz
            ├──ibt_C1_template_typ.nii.gz
            ├──ibt_C1_atlas_typ_fs2000.nii.gz
            └──ibt_C1_atlas_typ_fs2009.nii.gz
            
```
File Descriptions:

For a given age-group ${C}

| File Name                   | Descriptions |
| -------------------         | ------------- |
| ibt_${C}_template_mean      | population average for the ${C} age-group  |
| ibt_${C}_atlas_mpm_fs2000   | Indian MPM* version of the DK atlas (FreeSurfer's 2000 Atlas)  |
| ibt_${C}_atlas_mpm_fs2009   | Indian MPM version of the Destrieux atlas (FreeSurfer's 2009 Atlas)  |
| ibt_${C}_template_typ       | typical template for the ${C} age-group  |
| ibt_${C}_atlas_typ_fs2000   | Indian typical version of the DK atlas (FreeSurfer's 2000 Atlas) |
| ibt_${C}_atlas_typ_fs2009   | Indian typical version of the Destrieux atlas (FreeSurfer's 2009 Atlas)  |

\* MPM, maximum probability map


## To download the IBT dataset, run:
```
@Install_IBT_DATASETS
```
The install script is also available for download from [Zenodo](https://zenodo.org/record/3817045/files/hollabharath/IndiaBrainTemplates-v1.0.0.zip)

## Citing Us

The paper is now up at [bioRxiv](https://www.biorxiv.org/content/10.1101/2020.05.08.077172v1). It will be submitted to a journal in due course. It'd be wonderful if you would cite the paper if you use the methods or data set.
```
@article {Holla2020ibt,
	title = {A series of five population-specific Indian brain templates and atlases spanning ages 6 to 60 years},
	author = {Holla, Bharath and Taylor, Paul A and Glen, Daniel R and Lee, John A and Vaidya, Nilakshi and Mehta, Urvakhsh Meherwan and Venkatasubramanian, Ganesan and Pal, Pramod and Saini, Jitender and Rao, Naren P and Ahuja, Chirag and Kuriyan, Rebecca and Krishna, Murali and Basu, Debashish and Kalyanram, Kartik and Chakrabarti, Amit and Orfanos, Dimitri Papadopoulos and Barker, Gareth J. and Cox, Robert W and Schumann, Gunter and Bharath, Rose Dawn and Benegal, Vivek},
	year = {2020},
	doi = {10.1101/2020.05.08.077172},
	publisher = {Cold Spring Harbor Laboratory},
	URL = {https://www.biorxiv.org/content/10.1101/2020.05.08.077172v1},
	journal = {bioRxiv}
}
```


		
