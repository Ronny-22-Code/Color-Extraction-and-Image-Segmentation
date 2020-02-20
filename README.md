# Image-Segmentation

This repository introduces to my personal project, which explains and demonstrates the concept of segmentation of feature vectors according to the "Dominant Characteristic Feature" persistent in the image. The demonstration of the project was achieved by the application of "K-Means" Clustering algorithm, which is an unsupervised machine learning algorithm typically used for vector quantization and signal processing with data mining. This algorithm follows an iterative approach to segment or partition the dataset effectively, into K pre-defined clusters or overlapping sub-groups. The output obtained is the dominant color schemes demonstrated through graphical representation persistent in the image given as input.

# Introduction

In color image processing and its applications the great importance is attached to the techniques used forimage segmentation. The quality of segmentation results have a big impact on the next steps of imageprocessing, for example on the object recognition and tracking, the retrieval in image databases etc. Thegoal of image segmentation is partitioning of the image into homogeneous and connected regions withoutusing an additional knowledge about objects in the image. The homogeneity of regions in color imagesegmentation involves in natural way colors and sometimes color textures. In the segmented image theregions have, in contrast to single pixels, many interesting features like shape, texture etc. The human beingrecognizes objects in the environment using his visual system and by the way he or she segments color images.

If an image after segmentation contains many small regions corresponding to homogeneous objects inthe original image, then we can use a new term: the oversegmentation. On the other hand, if an image aftersegmentation contains few large regions and each region corresponds to several objects in the original image,then this case can be named the undersegmentation.

# Clustering Process

Clustering is the process of partitioning a set of objects (pattern vectors) into subsets of similar objectscalled clusters. Pixel clustering in three-dimensional color space on the basis of their color similarity is oneof popular approaches in the ﬁeld of color image segmentation. Clustering is often seen as an unsupervisedclassiﬁcation of pixels. Generally, the a priori knowledge about the image is not used during a clusteringprocess. Colors, dominated in the image, create dense clusters in the color space in natural way.  Many different clustering tech-niques, proposed in the pattern recognition literature, can be applied to color image segmentation. Oneof the most popular and fastest clustering techniques is the k-means technique.

The results of segmentation by k-means depend on the position of initial cluster centers. In the case ofsemiautomated version of k-means the input data can be deﬁned by human operator. In the case of automatedversion of k-means the initial centers can be choose randomly from all colors of the image. There exist alsoother possibilities for the choice of centers: k colors from the ﬁrst pixels in the image, k gray levels fromthe gray line uniformly partitioned into k segments. 

# Significance of the Project 

The process of partitioning a digital image into multiple segments is defined as image segmentation. Segmentation aims to divide an image into regions that can be more representative and easier to analyze. Such regions may correspond to individual surfaces, objects, or natural parts of objects. Typically image segmentation is the process used to locate objects and boundaries (e.g., lines or curves) in images. Furthermore, it can be defined as the process of labeling every pixel in an image, where all pixels having the same label share certain visual characteristics. Usually segmentation uses local information in the digital image to compute the best segmentation, such as color information used to create histograms or information indicating edges, boundaries, or texture information.

Color image segmentation that is based on the color feature of image pixels assumes that homogeneous colors in the image correspond to separate clusters and hence meaningful objects in the image. In other words, each cluster defines a class of pixels that share similar color properties. As the segmentation results depend on the used color space, there is no single color space that can provide acceptable results for all kinds of images. For this reason, many authors tried to determine the color space that will suit their specific color image segmentation problem . In this work, a segmentation of color images is tested with RGB classical color space.

# Screenshots 

![Screenshot (74)](https://user-images.githubusercontent.com/46643368/74839681-b0acf900-534b-11ea-911c-9b62847bc027.png)

![Screenshot (75)](https://user-images.githubusercontent.com/46643368/74839711-bdc9e800-534b-11ea-8d87-794f83a10197.png)

![Screenshot (78)](https://user-images.githubusercontent.com/46643368/74839732-c7535000-534b-11ea-9321-0c5e34a53421.png)

![Screenshot (79)](https://user-images.githubusercontent.com/46643368/74839757-cfab8b00-534b-11ea-80a8-9c86a5d4e0c6.png)

# Output 

![Screenshot (80)](https://user-images.githubusercontent.com/46643368/74839928-19947100-534c-11ea-80da-774914afb808.png)

![Screenshot (81)](https://user-images.githubusercontent.com/46643368/74839938-1dc08e80-534c-11ea-9b50-75997667f953.png)

![Screenshot (82)](https://user-images.githubusercontent.com/46643368/74839898-0f727280-534c-11ea-81fc-c887cce4650d.png)

# Conlcusion 

In this project work most of the attention has been concentrated on relatively simple image segmentation techniques(k-means clustering technique, region growing technique), that are a natural ﬁt to incorporate into applica-tions. The inﬂuences of location of initial cluster centers and the number of iterations on the segmentationresults obtained from k-means technique have been investigated experimentally. Two versions of regiongrowing technique i.e. semiautomated seeded version and automated unseeded version have been describedin detail. It can be concluded that exist many possibilities of reasonable choice of seeds for seeded version.
