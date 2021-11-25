---
layout: page
title: Research Projects
permalink: /projects/
---
This is my portfolio of significant research projects. Feel free to reach out to me with any questions or comments. 


# Research at Indian Space Research Organization
As a scientist at National Remote Sensing Center, ISRO, my primary research interest includes deep learning, image processing, data analysis, and natural language processing.
## Deep Learning
1. RTC-GAN: A novel generative adversarial network design for infusing spectral information into the spatial features for real-time semantic LULC segmentation of satellite data [[**Published at IEEE International Geoscience and Remote Sensing Symposium (IGARSS'20)**]](https://ieeexplore.ieee.org/document/9323363)  <br />
Summary: This project aims to design a novel GAN architecture for the real-time classification of satellite images.   <br />
Technology Used: Python, Keras, Scipy, PIL, GDAL, RasterIO

2. DisMon-GAN: A 24x7, all-weather disaster monitoring tool for assisting ministries and rescue teams by providing seamless synthesized optical images from the information collected by microwave SAR data. [[**Under Review at Conference on Computer Vision and Pattern Recognition (CVPR)**]](https://cvpr2022.thecvf.com/)<br />
Technology Used: Python, Keras, Scipy, PIL, GDAL, RasterIO

3. Land Use Land Cover Classification of Satellite Images using Deep Learning: This work discusses how high-resolution satellite images are classified into various classes like cloud, vegetation, water, and miscellaneous, using a feed-forward neural network. [[**Source Code**]](https://github.com/RohitGandikota/Land-Use-Land-Cover-Classification-of-Satellite-Images-using-Deep-Learning) <br />
Technology Used: Python, Keras, Scipy, PIL, GDAL, RasterIO

4. Thematic layer generation from Sentinel Images using M2TGAN: In this work, we generate the thematic maps from satellite images. Here, we generate water bodies thematic and use both traditional Autoencoder and a Generative Adversarial Network (M2TGAN). [[**Source Code**]](https://github.com/RohitGandikota/Satellite-Images-to-thematic-maps-using-Generative-Adversarial-Networks.)<br />
Technology Used: Python, Keras, Scipy, PIL, GDAL, RasterIO

## Image Processing
1. Automatic Satellite Quality Data Evaluation Algorithms: Automatic Image Quality Analysis (AIQA) has become a crucial module in the remote sensing industry. With increasing competition and institutions that provide remote sensing images, the quality of images provided to the users has a huge impact. This work provides advanced quality parameters like noise density, histogram statistics, radiometry, geometry, and LULC thematic information. <br />
Technology Used: Python, Scipy, Sci-kit, Numba, PIL, GDAL, RasterIO

2. A Novel Approach for Pixel Dropouts Localization: Commonly known as salt and pepper noise in the image processing terminology, pixel dropouts can be detected with many existing algorithms that usually tend to detect edges as noise falsely. A novel 2-stage algorithm has been designed to detect salt and pepper noise in raw satellite imagery to overcome this common problem. [[**Under Review at IEEE International Geoscience and Remote Sensing Symposium (IGARSS'22)**]](https://www.igarss2022.org/)<br />
Technology Used: Python, Sci-kit, Numba, Scipy, PIL, GDAL, RasterIO

## Data Analysis
1. Data Mining of ISRO's production history and analyzing the data for identifying gaps to improve efficiency. I formulated an optimization problem to improve production efficiency by considering dynamic resource allocation problems in a stochastic environment.  A 2.4 folds improvement in production time was observed. <br />
Tools used: Python, Seaborn, Plotly, Matplotlib, Pandas, Oracle. 

2. Analysis and Visualization of radiometry parameters automatically calculated for ~2000 images(512GB) per day to assess the quality and monitor the products delivered to users. <br />
Tools used: Python, Seaborn, Plotly, Matplotlib, Pandas, Postgres. 

## Natural Language Processing 
1. NLP solutions for automatic satellite ordering using voice search commands for [ISRO's open data website, Bhoondihi](https://bhoonidhi.nrsc.gov.in/bhoonidhi/index.html) and provided an [API package for the same on PyPI](https://pypi.org/project/bhoonidhi/) [[**Source Code**]](https://github.com/RohitGandikota/NLP-based-Smart-Search-for-Satellite-Data-Ordering)

2. Developing speech recognition extension for satellite-specific lingo. We are using open-sourced pre-trained LSTM networks to fine-tune satellite data-specific jargon. 

3. API for bhoonidhi, ISRO's open data dissemination portal. [[**Source Code**]](https://github.com/RohitGandikota/BhoonidhiAPI)

# Research at Indian Institute of Space Science and Technology
This is where my passion for machine learning was shaped into research. My work here mainly focused on the fundamental understanding of deep learning architectures, their computer vision applications (data hiding, image detection, autonomous vehicle vision, and face recognition), and a little bit of text processing and NLP. I will divide my research into a summer internship, course projects, final year thesis, and AIML club projects.

## Summer Internship
1. Understanding and developing Q-value-based Reinforcement learning algorithms. Developing a deep-reinforcement learning network for image detection.<br />
Technology Used: Python, Keras, PIL, openCV<br />

2. Understanding Convolutional Neural Networks through a novel approach. The input pixels responsible for classification are identified by back-tracking the activations of neurons at each layer. [[**Published at IEEE Region 10 International Conference (TENCON'19)**]](https://ieeexplore.ieee.org/document/8929603)  <br />
Technology Used: Python, Tensorflow, Keras, Matplotlib, Numba<br />
## Course Projects
1. Developing image processing algorithms for autonomous vehicle vision systems. This work focuses on developing basic image processing algorithms and fine-tuning them for usage in vision systems. [[**Report published in Arxiv**]](https://arxiv.org/abs/1812.02542)<br />
Technology Used: Python, OpenCV, PIL, Sci-kit, Numpy<br />

2. Worked on infusing the InceptionNet concept in Res Modules. This work was on architectural design to see if inception module advantages can help Res modules bottlenecks. <br />
Technology Used: Python, Tensorflow<br />

3. Comprehensive Study on WiFi protocols such as IEEE 802.11ac, 802.11ad, and 802.11ax and summarize a few of the works that discuss the abovementioned protocol standards of WiFi that brought a significant improvement in WiFi's performance. [[**Report published in Arxiv**]](https://arxiv.org/abs/1811.09391)<br />

4. Worked on job-shop scheduling optimization protocols and developed a scheduling protocol for the xv6 operating system.<br />

## Final year thesis
1. Designed VoI-GAN, the first end-to-end trainable model of Generative Adversarial Networks (GAN) engineered to hide audio data in images [[**Published at Springer's International Conference on Pattern Recognition and Machine Intelligence (PReMI'19)**]](https://link.springer.com/chapter/10.1007/978-3-030-34872-4_43) [[**Source Code**]](https://github.com/RohitGandikota/Hiding-Audio-in-Images-using-Deep-Generative-Network-with-Adversarial-Training) <br />
Technology Used: Python, Keras, Tensorflow, PIL<br />

2. Introduced the first models to hide video data inside images that can also be recognized as compression techniques: Vid-in-Img-3D-GAN and Vid-in-Img-RAN using 3D CNNs and bi-directional LSTMs [[**Source Code**]](https://github.com/RohitGandikota/Hiding-Video-in-Images-using-Deep-Generative-Adversarial-Networks)<br />
Technology Used: Python, Keras, Tensorflow, PIL<br />

3. Designed WM-GAN for watermarking images using GAN and VAE architectures [[**Source Code**]](https://github.com/RohitGandikota/Hiding-Images-using-VAE-Genarative-Adversarial-Networks)<br />
Technology Used: Python, Keras, Tensorflow, PIL<br />

## AIML club (Advised and Guided Students)
1. Built a device with Intel's Neural Compute Stick and a camera module, using the Siamese network for one-shot learning to perform automatic facial recognition to mark students' attendance inside classrooms.<br />
Technology Used: Python, Keras, Tensorflow, PIL, Intel Openvino<br />

2. Extended computer vision work on autonomous vehicles for IIST's mail delivery robot.<br />
Technology Used: Python, OpenCV, PIL<br />

3. Developed NLP solutions for campus enquiry chatbot. <br />
Technology Used: Python, NLTK, Numpy<br />
