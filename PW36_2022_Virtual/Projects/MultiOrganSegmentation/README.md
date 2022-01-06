Back to [Projects List](../../README.md#ProjectsList)

# Multi-organ Segmentation in Fetal Mice

## Key Investigators

- Murat Maga (Seattle Children's Research Institute, UW)
- Sara Rolfe (Seattle Children's Research Institute, UW)
- Andres Diaz-Pinto (Kings College, Nvidia)

# Project Description

<!-- Experiment and refine methods to segment multiple organs in contrast-enhanced microCT scans of fetal mice . -->

## Objective

<!-- Describe here WHAT you would like to achieve (what you will have as end result). -->

1. Use MONAILabel to implement an automated segementation pipeline in 3D Slicer
2. ...
3. ...

## Approach and Plan

<!-- Describe here HOW you would like to achieve the objectives stated above. -->

1. Dataset comes from International Mouse Phenotyping Consortium's Knockout Mouse Phenotyping project. Samples are E15 days old, fetal mice infused into iodine solution to increase soft tissue contrast during microCT imaging. Scans are publicly available at https://www.mousephenotype.org/.
2. We have used the existing atlas and a two-pass ANTs (SyNCC) registration to derive labels. We have manually reviewed the labels, and almost all of them were usable as is, without expert modification.  
3. Modify the multi-label version of the DeepEdit application to match our labels (52 labels in total).
4. Compare visually as well as quantitatively how similar the MonaiLabel estimates to previously segmented labels. 
5. ...

## Progress and Next Steps

<!-- Update this section as you make progress, describing of what you have ACTUALLY DONE. If there are specific steps that you could not complete then you can describe them here, too. -->

1. Initial model training for mouse embryo segmentation
2. ...
3. ...

# Illustrations

<!-- Add pictures and links to videos that demonstrate what has been accomplished.
![Description of picture](Example2.jpg)
![Some more images](Example2.jpg)
-->

# Background and References

<!-- If you developed any software, include link to the source code repository. If possible, also add links to sample data, and to any relevant publications. -->
