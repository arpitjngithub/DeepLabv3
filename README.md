# DeepLabV3 for Semantic Segmentation
This repository implements the DeepLabV3 model for semantic segmentation, using a training approach involving image patching and selective patch removal based on mask content. This method has led to significant accuracy improvements.


## Training Approach
We padded images to ensure divisibility by 224 (e.g., from 1024x1360 to 1024x1560) and implemented a strategy to remove patches with masks labeled only 0 during training. This focused the model on more informative regions, resulting in a notable accuracy improvement from 39% to 49%.

## Results
After training, our DeepLabV3 model achieved a validation accuracy of 39% on the test dataset. Loss curves and other metrics are visualized in the results/ directory.

## Contact
For questions or collaborations, feel free to reach out at suraj.prasad@iitb.ac.i.

