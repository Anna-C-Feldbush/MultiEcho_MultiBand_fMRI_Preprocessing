# MultiEcho_MultiBand_fMRI_Preprocessing
#Working Preprocessing Steps Included:
Convert_to_NIFTI ->
    This script acesses all of the files in In_Dir (specified within the Convert_to_NIFTI script) and converts to NIFTI using the subject ID, arm ID, Scan ID and Run ID as specified in the main script
Slice_Time_Correction ->
    This script preforms slice time correction. Slice aquisition pattern is defined in the main script. 
