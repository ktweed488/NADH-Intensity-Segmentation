Semantic Segmentation
1. Use ImageJ to run Macro to convert raw images to RGB images if they are not already
Need raw NADH intensity images as well as ground truth labels of cell area
2. Run Image_Segmentation_Train to train model - Dependent on HelperFunctions
3. Run Apply_CNN to use trained model to create masks for a group of images
4. Run Object_Recognition to perform watershed and segment individual cells


Image Classification
1. Use ImageJ to run Macro to convert raw images to RGB images if they are not already
2. Run imresizeFunction to convert images to needed 224x224 size
3. Run Image_Classifier to train multiclass SVM to deliniate cell types, Code at bottom of this script allows for batch classification of images