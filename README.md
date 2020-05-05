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


Please see the aforementioned paper for further details.




		
