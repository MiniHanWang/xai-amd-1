# xai-amd-1
# Skip-attention

## Project Overview 
This project is based on the common CNN network structure VGG16. According to the visualization structure, the model structure is optimized in a targeted manner to improve the accuracy of the model. 
## Project Structure Analysis
data: Stores the training and testing data of the model. The training data is divided into FAF, oct, oct-sem, RCPF, roi, and uwf. Each type of data is divided into positive and negative samples. 

dataCam: Stores the CAM activation map 

Model: Saves the trained weight of the model 

CAM_layer.py: Generates Cam activation maps layer by layer 

run.py: Modify the relevant paths in this script to start model training 

SkipStructure.py: Stores the structure of the model



