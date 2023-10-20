# The YTU3D dataset for urban point cloud classification

Semantically enriched 3D point clouds play a significant role in urban planning, documentation, and management.
Semantic segmentation of large-scale point clouds is the process to assign each point a semantic label, such as road, tree, roof, sidewalk, etc. Machine and deep learning algorithms offer crucial methodologies for understanding 3D point clouds at various scales. However, the semantic enrichment of large-scale point clouds remains an open research challenge. Available urban datasets generally lack class diversity, impeding the representation and understanding of detailed urban areas. Consequently, imbalanced classes are often present in the available datasets/benchmarks, and most learning methods struggle to accurately predict such imbalanced classes.

<p align="center"><img src="https://github.com/3DOM-FBK/YTU3D/blob/master/images/datasets.png"></p>

3D semantic segmentation still faces major challenges such as:
- low accuracy
- dealing with imbalanced classes
- misclassifications
- generalization
- upscaling
- 
<p align="center"><img src="https://github.com/3DOM-FBK/YTU3D/blob/master/images/YTU3D.png"></p>

To address these challenges, we propose and offer the YTU3D dataset:
- it covers an area of approximately 2 km2 over the Davutpasa Campus of Yildiz Technical University (YTU), Turkey
- images were acquired with a DJI Matrice 300 RTK using nadiral images with 75-75 along/across-track overlap
- the point cloud was derived using Pix4D, it has ca 1700 mil points and an average point density of ca 1000 points/m2
- there are 45 classes to represent the complex structures of the urban area and increase 3D scene understanding
- the entire point cloud is tiled in 43 regions of ca 210 x 210 sqm 

<p align="center"><img src="https://github.com/3DOM-FBK/YTU3D/blob/master/images/classes.png"></p>

## Provided data - coming soon

<p align="center"><img src="https://github.com/3DOM-FBK/YTU3D/blob/master/images/MLMR.png"></p>

_________________________________________________________________________
## Related Paper
O. C. Bayrak, F. Remondino, and M. Uzar, 2023: <a href="https://isprs-archives.copernicus.org/articles/XLVIII-1-W3-2023/1/2023/" target=page>A NEW DATASET AND METHODOLOGY FOR URBAN-SCALE 3D POINT CLOUD CLASSIFICATION</a>. Int. Arch. Photogramm. Remote Sens. Spatial Inf. Sci., XLVIII-1/W3-2023, 1–8
The psprt proposes also a multi-level multi-resolution (MLMR) methodology based on a hierarchical approach to classify 3D data based on diverse geometric resolutions, thereby enhancing the learning process and optimizing classification outcomes.

<p align="center"><img src="https://github.com/3DOM-FBK/YTU3D/blob/master/images/paper.png"></p>

_________________________________________________________________________
### Credits
This dataset is publicly available for research purposes. The realization of the dataset was supported by The Scientific and Technological Research Council of Türkiye (TUBITAK) [2214-A]
If you use this dataset for your research, please cite this repository and the related paper.

_________________________________________________________________________
### License
The data provided here is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

