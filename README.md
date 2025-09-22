# SEG and SR for NLSTSeg

This repository performs a conversion of the NLSTSeg tumor segmentations to DICOM Segmentation (SEG) format. Additionally, we extract shape and first-order features, and save them in DICOM Structured Reports (SR). 

1. We provide a [Google Colaboratory notebook](https://github.com/deepakri201/SEG_and_SR_for_NLSTSeg/blob/main/SEG_and_SR_for_NLSTSeg.ipynb) for the conversion to DICOM SEG and SR.
2. For technical validation of the tumor segmentations, we provide a [Google Colaboratory notebook](https://github.com/deepakri201/SEG_and_SR_for_NLSTSeg/blob/main/compare_to_ts/NLSTSeg_compare_SEG_to_TS.ipynb) that compares them to the TotalSegmentator lung lobe segmentation.

The ICD-03 codes used for the segmentations are provided [here](https://github.com/deepakri201/SEG_and_SR_for_NLSTSeg/blob/main/NLSTSeg_codes.csv). 

Deepa Krishnaswamy

Brigham and Women's Hospital 

September 2025
