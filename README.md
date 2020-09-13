

# Indian brain templates (IBTs) and atlases (IBTAs)

----------------------------------------------------------------------

This dataset is described in detail in the following
study:

  A series of five population-specific Indian brain templates and
  atlases spanning ages 6 to 60 years

  by Bharath Holla, Paul A. Taylor, Daniel R. Glen, John A. Lee,
  Nilakshi Vaidya, Urvakhsh M. Mehta, Ganesan Venkatasubramanian,
  Pramod Pal, Jitender Saini, Naren P. Rao, Chirag Ahuja, Rebecca
  Kuriyan, Murali Krishna, Debashish Basu, Kartik Kalyanram, Amit
  Chakrabarti, Dimitri Papadopoulos Orfanos, Gareth J. Barker, Robert
  W. Cox, Gunter Schumann, Rose Dawn Bharath, Vivek Benegal

Published in the [Human Brain Mapping](https://onlinelibrary.wiley.com/doi/full/10.1002/hbm.25182) journal.

<p>
<a href="https://doi.org/10.1002/hbm.25182">
   <img src="https://img.shields.io/badge/DOI-10.1002%2Fhbm.25182-informational" />
</a>	
</p>

In this work we introduce five new India brain template (IBTs) spaces, spanning an
age range from 6-60 years. Additionally, corresponding atlases (IBTAs) from FreeSurfer-defined
atlases have been created for each space, along with tissue-specific
maps and segmentations. These should form useful reference templates
and region maps for brain imaging studies involving predominantly
Indian populations.


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
	    ├──ibt_C1_atlas_typ_fs2009.nii.gz
            └──supplementary_C1
            
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
| supplementary_${C}	      | a directory of supplementary datasets. 1) Tissue-based maps of subsets of each atlas: GM, GM ROIs (i.e., not including unspecified cortical GM, useful for tracking or correlation matrices), WM, CSF, Ventricles, “other” (such as “optic chiasm”), and “unknown”. 2) Segmentation maps: 1=GM, 2=WM, 3=CSF+Vent, 4=other+unknown. |


\* MPM, maximum probability map


## Download the IBT datasets:

Either run the following AFNI command:

```
@Install_IBT_DATASETS
```

(the plain Linux-y terminal way) copy+paste:

```
wget https://afni.nimh.nih.gov/pub/dist/tgz/IBT_DATASETS.tgz
tar -xvf IBT_DATASETS.tgz
```

(the mouseclick+ way) click on [this link](https://afni.nimh.nih.gov/pub/dist/tgz/IBT_DATASETS.tgz),
… and then unpack the zipped directory by either clicking on it or using the above tar command.

## Citation

The paper is now up at [Human Brain Mapping](https://onlinelibrary.wiley.com/doi/full/10.1002/hbm.25182) journal. It'd be wonderful if you would cite the paper if you use the methods or data set.

```
@article{Holla2020ibt,
  doi = {10.1002/hbm.25182},
  url = {https://doi.org/10.1002/hbm.25182},
  year = {2020},
  month = aug,
  publisher = {Wiley},
  author = {Bharath Holla and Paul A. Taylor and Daniel R. Glen and John A. Lee and Nilakshi Vaidya and Urvakhsh Meherwan Mehta and Ganesan Venkatasubramanian and Pramod Kumar Pal and Jitender Saini and Naren P. Rao and Chirag K. Ahuja and Rebecca Kuriyan and Murali Krishna and Debashish Basu and Kartik Kalyanram and Amit Chakrabarti and Dimitri Papadopoulos Orfanos and Gareth J. Barker and Robert W. Cox and Gunter Schumann and Rose Dawn Bharath and Vivek Benegal},
  title = {A series of five population-specific Indian brain templates and atlases spanning ages 6{\textendash}60{\hspace{0.167em}}years},
  journal = {Human Brain Mapping}
}
```


		
