# Diploma_Major_Project_202 0 to 2021
# OCT Image Segmentation using U-nets
"This project, using 'Deep Learning-Based Segmentation of OCT Images for Alzheimer's Disease Diagnosis,' aimed to enhance the non-invasive diagnosis of Alzheimer's disease (AD), which affects 5.8 million people in the US, mostly seniors. This research is crucial for society as it proposes a less invasive, cost-effective diagnostic alternative to current methods like PET and MRI. I utilized deep learning with the U-Net architecture, alongside tools and technologies such as Python, TensorFlow, and high-resolution OCT imaging equipment. My role involved developing the model, preprocessing the dataset, and optimizing the hyperparameters to achieve high segmentation accuracy. One interesting fact is that the project demonstrated the potential of OCT imaging to detect AD, which is typically used for eye conditions. Challenges included dealing with noisy data and ensuring model generalization. Through this project, I learned the importance of data quality and the potential of interdisciplinary deep learning applications."

# Results:
Here are some results I obtained after using my trained model

<img src="https://github.com/MuttuVittal818/Diploma_Major_Project_2021/blob/main/Results/R1.png" alt="J" width="200"/>
<img src="https://github.com/MuttuVittal818/Diploma_Major_Project_2021/blob/main/Results/R2.png" alt="J" width="200"/>

# Conclusion:

U-Nets give better results than the sliding window segmentation model anyway. We also work on minimal data.

# Further Improvements

Note that we have used Conv2D operations on this dataset. Conv3D would work even better on 4-dimensional datasets, which is generally true in optical coherence tomography images because the 3-D spatial information would be retained.
