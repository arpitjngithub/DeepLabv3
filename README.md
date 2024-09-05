<h1>DeepLabV3 for Semantic Segmentation</h1>
This repository presents an implementation of the DeepLabV3 model for semantic segmentation. The training process incorporates image patching and selective removal of uninformative patches, enhancing segmentation accuracy.<br/>
<br/>
To optimize performance, images were padded to ensure dimensions divisible by 224 (e.g., 1024x1360 padded to 1024x1560). During training, patches containing only mask label 0 were removed, concentrating the model's focus on more relevant regions. This approach led to a significant accuracy improvement from 39% to 49%.<br/>
<br/>
Post-training, the DeepLabV3 model achieved a validation accuracy of 49% on the test dataset. Detailed visualizations of loss curves and other metrics can be found in the results/ directory.

