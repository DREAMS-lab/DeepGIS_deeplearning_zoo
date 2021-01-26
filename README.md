# DeepGIS Deep Learning Models, Dataset and Notebooks

This repository contains a collection of deep learning notebooks for training image annotations from DeepGIS.

For Lunar and Mars crater annotations, please visit this [wiki](https://github.com/DREAMS-lab/deepgis/wiki/Wiki-for-Crater-Annotation-in-DeepGIS)

Here are the annotation files,
  - LROC NAC Annotations (350x350 images)
    - https://github.com/DREAMS-lab/DeepGIS_deeplearning_zoo/blob/master/lroc_nac_all.zip  (36k craters)
    - https://github.com/DREAMS-lab/DeepGIS_deeplearning_zoo/blob/master/lroc_nac_corrected.zip (22k craters)
  - Mars CTX Annotations (1024x1024 images)
    - https://github.com/DREAMS-lab/DeepGIS_deeplearning_zoo/blob/master/mars_corrected.tar.xz (20k craters)
    - https://github.com/DREAMS-lab/DeepGIS_deeplearning_zoo/blob/master/mars_all.tar.gz (29k craters)
    
    
[This](https://github.com/DREAMS-lab/DeepGIS_deeplearning_zoo/blob/master/Mask_RCNN_Colab_notebook_LROC_NAC.ipynb) Google Colab notebook provides an introduction on how to run PyTorch based MaskRCNN on this dataset. 

Visit mars.deepgis.org or lroc-nac.deepgis.org, if you wish to make corrections to the dataset or have any other suggestions.

Inference and training for STTR, was done through [developmentseed/divdet](https://github.com/developmentseed/divdet) codebase.
