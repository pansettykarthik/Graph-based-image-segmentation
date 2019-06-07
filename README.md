# Graph Based Image Segmentation
## Summer Research Internship Program (SRIP) 2017 - Indian Institute of Technology Gandhinagar (IITGN)

Here, we address the problem of segmenting image into different regions. We first convert the image into a graph based representation by first constructing the superpixels by using Simple Linear Iterative Clustering (SLIC) based on the spatial proximity and the color proximity and
then giving edge weights by setting a specific threshold. To segment this
image, we then cluster the graph into multiple clusters using Graph Cut algorithms. Different clusters
form different segments of the image.

Used the dataset from The PASCAL Visual Object Classes Challenge 2012 (VOC2012).
