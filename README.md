Objective : 
Identify surface defects in industrial materials using transfer learning with convolutional neural networks.
Use a pre-trained deep learning model and adapt it to classify surface defects from image data by appropriately 
loading the model, configuring a freezing strategy, and retraining it on the target dataset.


Business Value :
In industrial manufacturing, surface defects directly affect product quality, safety, and customer satisfaction. 
Manual inspection is time-consuming, expensive, and prone to human error, especially at scale. 
Computer vision–based defect identification systems enable:
• faster inspection pipelines
• consistent quality control
• early detection of production issues

Automatically classify surface defects in steel materials using real-world industrial image data and a 
transfer learning approach.
Surface defects such as cracks, scratches, inclusions, and pits commonly occur during manufacturing processes 
and can significantly affect product quality. Manual inspection of these defects is time-consuming, inconsistent, 
and difficult to scale.

Dataset:
The dataset consists of images representing different types of surface defects commonly observed in industrial materials. 
Each image belongs to exactly one defect category.

• The dataset contains multiple defect classes - crazing, inclusion, patches, pitted surfaces, rolled-in scale, 
and scratches
• Images are grayscale
• The training and validation sets are already split into two subfolders in the data
• Both the training and validation data contain an "image" folder and an "annotations" folder
• The "images" folder has subdirectories, each containing images for a specific defect class
• The dataset is pre-cleaned and does not contain missing labels
