# Find Proteins in cryoET with CNN

This repo contains the object detection tools for finding specific proteins from cryo-electron tomography (cryoET) datasets.

Cryo-electron tomography (cryoET) generates 3D images of biological samples at a range of resolutions, from whole cells to molecules at near atomic resolution. 

CryoET data analysis can be difficult and time consuming. Therefore, the development of software and machine learning (ML) methods that can speed up data processing is essential to propel advances in the cryoET field. The schematic below highlights the time it takes to process images to obtain molecular structures.

<img src="Figures/workflow_timeline.png" width = "700">

CryoET image processing workflow ([cryoet-data-portal](https://github.com/chanzuckerberg/cryoet-data-portal/blob/main/docs/cryoet_workflow.md)) showing the time it takes to get through each step.

This portfolio focus using deep learning to automate the object detection and annotation step, including codes to accomplish: 
* Model training 
* Inference
* Evaluation 
