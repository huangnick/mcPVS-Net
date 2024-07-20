# mcPVS-Net
The mcPVS-Net can segment perivascular spaces (PVS) from 3D T1-weighted images.

# Introduction
Perivascular spaces (PVS) visible on magnetic resonance imaging (MRI) are significant markers associated with various neurological diseases. Traditionally, clinicians have assessed PVS using visual scores, which involve counting PVS and converting these counts into a scoring system, typically ranging from 0 to 4. This method requires considerable experience from the observer, is time-consuming, and is subject to floor and ceiling effects. Studies have shown that quantitative analyses might provide more robust associations with clinical variables, highlighting the importance of advancing PVS assessment methods in neurological research and diagnosis.

The mcPVS-Net was trained based on the nnU-Net framework. We annotated PVS on multi-center 3D T1-weighted (T1w) images collected using scanners from three major vendors (Siemens, General Electric, and Philips). The training was performed in 40 subjects and the segmentation accuracy was tested in 15 subjects. The detailed information can be found in the related paper. Below is a demonstration of the segmentation result.
![image](https://github.com/user-attachments/assets/49442145-c5c8-45af-8e60-f138b81eac78)


# Usage
The mcPVS-Net can be easily used in the nnU-Net environment. Please check https://github.com/MIC-DKFZ/nnUNet for detailed instructions. The trained model could be downloaded from: [to be uploaded].
Several preprocessing steps are required, including brain extraction, bias field correction, and intensity normalization.

# Reference
Please cite the following paper if you use this model:
Huang et al. Development and validation of a perivascular space segmentation method in multi-center datasets. Under review.
