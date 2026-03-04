# Awesome Mapping Agency Repositories

> A curated collection of GEO/ML GitHub repositories from national mapping agencies around the world.

---

## 🇩🇰 Denmark — KDS (Kortforsyningen / SDFI)

### 🔧 Code – [KDS on GitHub](https://github.com/SDFIdk)

- [ML_geo_production](https://github.com/SDFIdk/ML_geo_production): Ensemble semantic segmentation models in production, used for building change detection.
- [laz-superpoint_transformer](https://github.com/SDFIdk/laz-superpoint_transformer): Training and inference for LiDAR point clouds (`.laz`). Proof-of-concept stage but works very well.
- [ML_sdfi_fastai2](https://github.com/SDFIdk/ML_sdfi_fastai2): Training and validation of semantic segmentation models with fastai2. Used for all semantic segmentation models at KDS.
- [multi_channel_dataset_creation](https://github.com/SDFIdk/multi_channel_dataset_creation): Example data used across several repos. Includes code for label creation, dataset splits, and more.
- [ML_object_detection](https://github.com/SDFIdk/ML_object_detection): Training and inference with YOLO models for object detection. Supports large image outputs and generates LabelMe-ready `.json` files.
- [Permeable Surfaces (interactive map)](https://dataforsyningen.dk/labs/2259): ResNet34 U-Nets trained on multi-channel imagery (RGB-NIR orthophotos, DSM, DTM, and oblique RGB-NIR images).

### 📚 Datasets – [KDS on Hugging Face](https://huggingface.co/rasmuspjohansson)

- [example_dataset](https://huggingface.co/datasets/rasmuspjohansson/example_dataset): Buildings (binary) and permeable surfaces (9 classes). Matches the `multi_channel_dataset_creation` repo.
- [KDS_objects_in_oblique_images](https://huggingface.co/datasets/rasmuspjohansson/KDS_objects_in_oblique_images)
- [KDS_laz_dataset](https://huggingface.co/datasets/rasmuspjohansson/KDS_laz_dataset)

### 🤖 Models

- [KDS_buildings](https://huggingface.co/rasmuspjohansson/KDS_buildings)

### 🐳 Docker

- [kds_cuda_pytorch](https://hub.docker.com/repository/docker/rasmuspjohansson/kds_cuda_pytorch/general): CUDA + PyTorch environment for KDS workflows.

---

## 🇪🇸 Spain

### ICGC

- [ICGC Homepage / Research](https://marionacaros.github.io/)
- [terlidar](https://github.com/marionacaros/terlidar): Power wire LiDAR dataset.

### IGN-RT

- [IGN-RT on GitHub](https://github.com/IGN-RT): Institutional repositories.

---

## 🇫🇷 France — IGN (IGNF)

### 🔧 Code – [IGNF on GitHub](https://github.com/IGNF)

- [FLAIR-HUB](https://github.com/IGNF/FLAIR-HUB): End-to-end pipeline for land-cover (CoSIA) and crop-type mapping. Supports monomodal and multimodal TIFF inputs (aerial, historical, SPOT, Sentinel-1/2, elevation). [Explore CoSIA results →](https://ignf.github.io/cosia-viewer/)
- [FLAIR-1](https://github.com/IGNF/FLAIR-1): Land-cover semantic segmentation — training and large-area inference with pre-trained models.
- [myria3d](https://github.com/IGNF/myria3d): Training and inference on LiDAR `.laz` point-cloud files with RGB-NIR color support.
- [MAESTRO](https://github.com/IGNF/MAESTRO): Adaptation of the SSL Masked Autoencoder (MAE) framework for multimodal, multitemporal, multispectral Earth Observation data.

### 📚 Datasets – [IGNF on Hugging Face](https://huggingface.co/IGNF)

- [FLAIR-HUB](https://huggingface.co/datasets/IGNF/FLAIR-HUB): 19 land-cover classes + 46 crop classes over >2,500 km² in France at 20 cm resolution, manually photo-interpreted.
- [PASTIS-HD](https://huggingface.co/datasets/IGNF/PASTIS-HD): 2,433 patches with Sentinel-1, Sentinel-2, and SPOT imagery, with panoptic agricultural cover annotations.
- [TreeSatAI-TS](https://huggingface.co/datasets/IGNF/TreeSatAI-Time-Series): Extension of TreeSatAI with yearly Sentinel time-series for tree-species classification over Germany.
- [PureForest](https://huggingface.co/datasets/IGNF/PureForest): 449 forest sites in France with LiDAR and aerial imagery for tree-species classification.

---

## 🇳🇴 Norway

- [ivaroveland on GitHub](https://github.com/ivaroveland)

---

## 🇵🇱 Poland

- [WalidatorPlikowGML](https://github.com/MarcinLebiecki/WalidatorPlikowGML): QGIS plugin for validating GML files.

---

## 🌍 Other Resources

- [satellite-image-deep-learning/techniques](https://github.com/satellite-image-deep-learning/techniques): A broad reference for deep learning techniques applied to satellite imagery.

---

> 💡 Know a repository that belongs here? Please open an issue or submit a pull request!
