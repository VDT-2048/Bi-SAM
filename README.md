# Bi-SAM
This repository contains a collection of research papers and benchmarking results for the task of Bimodal Few-shot Semantic Segmentation (Bi-FSS). Besides, to evaluate the applicability of SAM in real-world natural scenario, we created a new bimodal few-shot segmentation dataset called VT-840-5i for indoor environment to include challenging cases from diverse indoor environments. 
•	Paper link: waiting
•	This project is under construction. If you would like to contribute to this repository, please submit a pull request.

# FSS Background
Different from the general foundation models, which require huge data, few-shot segmentation (FSS) can quickly model and distinguish different categories with only a couple of samples. It can segment new categories from the background without fine-tuning, thus bridging the gap between human intelligence and AGI. This is very helpful for scenarios with insufficient data and expensive marking.
This paper makes three contributions:
1) To evaluate the applicability of SAM in real-world natural scenario, we created a new bimodal few-shot segmentation dataset called VT-840-5i for indoor environment to include challenging cases from diverse indoor environments. 
2) We analyze the bimodal SAM fusion methods under different datasets, and propose the gated prediction selection (GPS) module to assess the matching degree between the two modalities and prediction, yielding better segmentation output than from a single SAM predictor.
3) Our discussion delved into the current limitations, available prospects, and future research trends of SAM, with the aim of providing inspiration and assistance to future researchers.

# Qualitative Evaluation
The SAM test results on the indoor and outdoor datasets are shown in the two folders above[VT-840-5i test results] [Tokyo Multi-Spectral-4i test results] , and the following is only partially shown:
https://pan.baidu.com/s/1xL6RV7IgfZpZv2Gl-C2vmQ?pwd=znsk 

# A novel bimodal FSS benchmark --- VT-840-5i
It includes 840 pairs of aligned RGBT image pairs, with 390 pairs from VT821, VT1000, and VT5000, and the remaining 450 pairs from VI-RGBT1500. The dataset comprises 20 object categories, and the image size is standardized at 640×480. The dataset includes four different illumination conditions, including bright illumination, uneven illumination, weak illumination and dark illumination, to fully demonstrate the superiority of bimodal image fusion. Moreover, the dataset includes image clutter and defocus. Scenes cover as many indoor environments as possible, including schools, shopping malls and families (e.g., living room, bedroom, kitchen, bathroom and study, etc.) 
# 
