# Anomaly Detection in Radio Galaxy Images (FRGADB)

This repository contains an unsupervised anomaly detection pipeline
applied to radio galaxy images from the FRGADB dataset.

## Dataset
The project uses the **FRGADB (Fast Radio Galaxy Anomaly Detection Benchmark)** dataset.

- **FRI, FRII**: Normal radio galaxies
- **RRG, XRG**: Anomalous radio galaxies

⚠️ The dataset is **not included** in this repository.
Please download it from the official Zenodo source.

## Methodology
- FITS image preprocessing
- Normal-only training strategy
- Convolutional Autoencoder
- Reconstruction error–based anomaly detection

## Results
The trained autoencoder successfully learns normal radio galaxy morphology
and exhibits reconstruction failures on anomalous samples, enabling
threshold-based anomaly detection.

## Tools & Libraries
- Python
- NumPy
- Astropy
- OpenCV
- TensorFlow / Keras
- Matplotlib

## Notes
This project is intended for academic and research purposes.
