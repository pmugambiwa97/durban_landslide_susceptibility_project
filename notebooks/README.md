### Model Development & Core Code Pipelines

This directory contains the Python notebooks (.ipynb) developed in Google Colab utilizing the Google Earth Engine (GEE) Python API and Scikit-Learn. 

### Core Workflow Engines:
- **01_radar_terrain_processing.ipynb**: Cloud-based processing pipelines executing multi-temporal Sentinel-1 GRD SAR backscatter amplitude differencing alongside SRTM topographic parameter extraction (slope, aspect).
- **02_machine_learning_pipeline.ipynb**: Statistical model evaluation using Random Forest and XGBoost architectures, incorporating ensemble standard deviation calculations for local model uncertainty quantification.
