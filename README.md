# Awesome Mapping Agency Repositories

A collection of GEO/ML GitHub repositories from different mapping agencies.


## Denmark

**Danish KDS**

- [ML_geo_production](https://github.com/SDFIdk/ML_geo_production): Using ensambles of semantic segmentation models in production. (used for building change detection)
- [laz-superpoint_transformer](https://github.com/SDFIdk/laz-superpoint_transformer): Training and inference for LiDAR point cloud(.laz) (proof of concept stage but works very well) 
- [ML_sdfi_fastai2](https://github.com/SDFIdk/ML_sdfi_fastai2): Training and validation of semantic segmetnation models with fastai2 (used for training all semantic segmetnation models at KDS)
- [multi_channel_dataset-example](https://github.com/SDFIdk/multi_channel_dataset_creation): Example data used by the examples in the some other repos. Also contains code for label creation, dataset splits etc
- [ML_object_detection](https://github.com/SDFIdk/ML_object_detection): training and inference with yolo models for object detection. The detection code can produce huge images and creates labelme ready .json files. 
- [permeable surfaces](https://dataforsyningen.dk/labs/2259)   : using resent34 unets with multichannel images made up of rgb-Nir-ortofoto, DSM, DTM and obliqe rgb-nir-images. This is an interactive map you can explore 


## Spain

**ICGC**

- [ICGC homepage](https://marionacaros.github.io/): (More info about ICGC)
- [terlidar](https://github.com/marionacaros/terlidar): Power wires LiDAR dataset.

**IGN-RT**

- [IGN-RT GitHub](https://github.com/IGN-RT): (Institutional Repositories)

## France

🔧 Code – [IGNF on Github](https://github.com/IGNF) 

- [FLAIR-HUB](https://github.com/IGNF/FLAIR-HUB): Code for land-cover map (CoSIA) and crop-type mapping generation. Sandbox with monomodal / multimodal TIFF inputs (aerial images, historical images, SPOT, Sentinel-1 & 2, elevation). See some CoSIA results [here](https://ignf.github.io/cosia-viewer/).
- [FLAIR-1](https://github.com/IGNF/FLAIR-1): land-cover segmentic segmentation training, inference over large areas with pre-trained models.
- [myria3d](https://github.com/IGNF/myria3d): Training and inference on LiDAR point-cloud LAZ files (with RGB-NIR color).
- [MAESTRO](https://github.com/IGNF/MAESTRO): Adaptation of the SSL Masked Autoencoder (MAE) framework for multimodal, multitemporal, multispectral EO data.

📚 Datasets – [IGNF on HugginFace]( https://huggingface.co/IGNF)

- [FLAIR-HUB](https://huggingface.co/datasets/IGNF/FLAIR-HUB): 19 land-cover classes + 46 crop classes over >2500 km² in France at 20 cm resolution, manually photo-interpreted.
- [PASTIS-HD](https://huggingface.co/datasets/IGNF/PASTIS-HD): 2,433 patches with Sentinel-1, Sentinel-2, and SPOT imagery, with panoptic agricultural cover annotations.
- [TreeSatAI-TS](https://huggingface.co/datasets/IGNF/TreeSatAI-Time-Series): Extension of TreeSatAI with yearly Sentinel time-series for tree-species classification over Germany.
- [PureForest](https://huggingface.co/datasets/IGNF/PureForest): 449 forest sites in France with LiDAR and aerial imagery for tree-species classification.


## Norway
https://github.com/ivaroveland

## Poland

- [WalidatorPlikowGML](https://github.com/MarcinLebiecki/WalidatorPlikowGML): QGIS plugin for validating GML files.

---

If you know more repositories or have details for missing items (e.g., 'maestro', 'lastig'), please consider submitting a pull request or opening an issue!


## Other links

https://github.com/satellite-image-deep-learning/techniques
