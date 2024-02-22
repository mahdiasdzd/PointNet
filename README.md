# Using ShapeNet Dataset in Point Cloud for training PointNet Model with Semantic Segmentation extend with Open Shape and OOD(Out-of-Distribution) and Instance IDs

The official code page in Kaggle ["Mahdi Asadzadeh"](https://www.kaggle.com/code/mahdiasdzd/pointnet).
The official Dataset for ["ShapeNet_Core"](https://www.kaggle.com/datasets/jeremy26/shapenet-core-seg).

# Shape Net:
dataset is a large and publicly available collection of 3D CAD models. It was created to facilitate research and development in the field of computer vision, particularly in tasks related to 3D object recognition, segmentation, and shape understanding.
ShapeNet provides a diverse set of 3D models spanning various object categories, and it has been widely used in the computer vision and machine learning communities.

# Point Cloud:
point cloud is a collection of data points defined in a three-dimensional coordinate system.
Each point in the cloud represents a position in 3D space and may include additional information such as color, intensity, or other attributes associated with that point.
Point clouds are commonly obtained through 3D scanning technologies like Lidar or structured light scanners, or they can be generated synthetically.

# Point Net:
PointNet's architecture is designed to be permutation invariant, meaning that the model's output should be the same regardless of the order of the input points. This is crucial for processing point clouds, as the order of the points may vary. The architecture employs a shared multi-layer perceptron (MLP) network to process each point independently, extracting local features. A symmetric function (max pooling) is then applied to aggregate information from all points into a global feature vector, capturing the overall structure of the point cloud.

# Instance IDs:
Instance IDs in 3D semantic segmentation typically refer to unique identifiers assigned to each individual object instance or region within a point cloud. These IDs help distinguish between different objects or instances in the scene.

Open Shape:
"OpenShape" is a research project aimed at advancing the representation and understanding of 3D shapes in a manner that facilitates scalability and applicability to diverse shapes encountered in the open world. The goal seems to be to move beyond limited predefined categories or datasets and enable more comprehensive understanding of 3D shapes.



## Updates
## Citation
```
@article{
  year={2024}
}
```
## How to use
first download models and save them in same directory with IPYNB file as jupyter notebooks then Run nootbooks.

### Model weights
Kaggle Drive Link:().

### Training and Testing
1) Download Dataset
2) Run IPYNB file with Jupyter or Google Colab


3) 2) Run the following code to install the Requirements.

    `pip install -r requirements.txt`

4) Run the  code to train 

5) Test trained model with this dataset in in IPYNB too.

# results
![](https://github.com/mahdiasdzd/mri/blob/main/Model-Results-2021.png)

# Future work
Using other model like PointNet++, KPConv (Kernel Point Convolution), DGCNN (Dynamic Graph Convolutional Neural Network), RSNet (Range Scan Network), PointCNN, PointSIFT, SpiderCNN, ShellNet, PU-Net (Point Cloud U-Net), PointASNL
