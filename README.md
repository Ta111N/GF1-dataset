# GF1-cloud-and-cloud-shadow-detection-dataset  
Dataset information on the paper "Cloud and Cloud Shadow Detection of GF-1 Images Based on the Swin-UNet Method".  
## Overview  
In our study, GF-1 WFV multispectral images were selected. Specifically, this paper will use the publicly available GF1_WHU cloud and cloud shadow detection datasets (published by Wuhan University, http://sendimage.whu.edu.cn/en/mfc-validation-data/) for related research. GF-1, the inaugural satellite of the civilian High-Definition Earth Observation Satellite (HDEOS) program, achieved successful launch aboard the Long March 2 carrier rocket on April 26, 2013. The GF-1 is equipped with the WFV camera, capable of capturing multispectral images at a spatial resolution of 16 meters. It comprises four spectral bands: blue (0.45-0.52 µm), green (0.52-0.59 µm), red (0.63-0.69 µm), and near-infrared (NIR) (0.77-0.89 µm). Furthermore, the satellite features four WFV sensors that concurrently cover a swath width of up to 800 kilometers. Impressively, it offers a revisit period of merely 4 days, facilitating large-scale, short-term surface observation, and monitoring capabilities.  

After processing, the dataset we provide is divided into images and labels, and the naming of the two corresponds to each other. It should be noted that the first digit after the image name is the corresponding number of rows in the original image, and the second digit is the number of columns. We discarded the part of the data set that contained background values (NoValue). Concurrently, although we have manually filtered out data containing erroneous judgment information as much as possible, we still cannot guarantee the absolute accuracy of the data. Finally, 58267 slices of data were provided, each with a size of 512 * 512.  

The pixel values of the images are Top of Atmosphere Reflectance (TOA), and the labels in which each DN value denotes:  
 **Value** | **Class**    
 |:----------:|:-------------:|
 0  |  Clear
 1  |  Cloud Shadow
 2  |  Cloud
 
Specifically, the global distribution of the dataset is as follows：  
![Image text](https://github.com/Ta111N/GF1-dataset/blob/main/image.png)  
## Dataset Access  
The data is provided in .zip format.  
Dataset is available in BaiduDisk : [BaiduDisk](https://pan.baidu.com/s/1kTZTUO4aNGuLq5V5goINRA) (extracting code：bh1y)
