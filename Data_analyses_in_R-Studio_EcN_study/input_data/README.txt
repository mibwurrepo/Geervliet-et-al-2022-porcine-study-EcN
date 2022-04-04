The biom1 files should be unzipped befor usage.

On Windows: use the free application 7Zip (https://www.7-zip.org/)

On Linux/MacOS:
The multifile zip should first be concatenated to support unzipping with unzip:
(note the quotes around the filenames ):

cat "Galaxy76-[NG-Tax__porcine_study_all_samples_eightrun_length120bp_no_annotation_0.005threshold_5may2020].biom1.z01" \
	"Galaxy76-[NG-Tax__porcine_study_all_samples_eightrun_length120bp_no_annotation_0.005threshold_5may2020].biom1.z02" 
	"Galaxy76-[NG-Tax__porcine_study_all_samples_eightrun_length120bp_no_annotation_0.005threshold_5may2020].biom1.zip" > \
	"Galaxy76-[NG-Tax__porcine_study_all_samples_eightrun_length120bp_no_annotation_0.005threshold_5may2020].biom1.concatenated.zip"

unzip "Galaxy76-[NG-Tax__porcine_study_all_samples_eightrun_length120bp_no_annotation_0.005threshold_5may2020].biom1.concatenated.zip"


