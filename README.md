# Through the Looking Glass: <br> Neural 3D Reconstruction of Transparent Shapes <br> ([Project page](http://cseweb.ucsd.edu/~viscomp/projects/CVPR20Transparent/) )

## Useful links
* Project page: http://cseweb.ucsd.edu/~viscomp/projects/CVPR20Transparent/
* Dataset creation: https://github.com/lzqsd/TransparentShapeDatasetCreation
* Renderer: https://github.com/lzqsd/OptixRenderer
* Trained models: coming soon
* Real data: coming soon
* Real data processing: coming soon
* Synthetic dataset: coming soon

## Overview
This is the official code release of our paper [Through the Looking Glass: Neural 3D Reconstruction of Transparent Shapes, CVPR 2020](https://arxiv.org/abs/2004.10904). Please consider citing this paper if you find this code useful in your project. Please contact us if you have any questions or issues. 

## Prerequisite
In order to run the code, please install
* Pytorch: versions later than 1.0 might be enough
* Colmap: Please install Colmap from this [link](https://colmap.github.io/). We use Colmap to reconstruct mesh from point cloud prediction. 
* Meshlab: Please install Meshlab from this [link](https://www.meshlab.net/). We use the subdivision algorithm in Meshlab to smooth the surface so that there is no artifacts when rendering transparent shape. This is important when the BRDF is a delta function. 

## Instructions
The code have 2 parts. The normal prediction part is included in `Normal` directory
