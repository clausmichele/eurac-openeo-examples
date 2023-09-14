# 13th ESA Training Course on Earth Observation 2023

## Land Cover and SAR processing exercises

This folder contains material prepared for the [13th ESA Training Course
on Earth Observation 2023](https://esat.ferit.hr/).

It consist in multiple notebooks. If you run them in the following order with no changes everything should work out of the box, gievn that you have an account for the Eurac back-end (not necessary in notebook 01).

1. [01_Land_Cover_Classification_first_part.ipynb](https://gitlab.inf.unibz.it/earth_observation_public/eurac-openeo-examples/-/blob/main/python/land_cover_exercise/01_Land_Cover_Classification_first_part.ipynb)
    - Manual sample points selection
    - Sample points read and process
    - Satellite data retrieval using STAC and openEO
    - Features extraction
    - Random Forest training and prediction
    - Prediction visual evaluation

2. [02_SAR2Cube_data_preparation.ipynb](https://gitlab.inf.unibz.it/earth_observation_public/eurac-openeo-examples/-/blob/main/python/land_cover_exercise/02_SAR2Cube_data_preparation.ipynb)
    - Connect to Eurac openEO back-end
    - Compute intensity
    - Apply Multi-Look
    - Convert the data from linear to dB
    - Geocode the data
    - Start and execute an openEO batch job
    - Download and visualize the result

3. [../SAR2Cube_openEO_examples_radar_mask.ipynb](https://gitlab.inf.unibz.it/earth_observation_public/eurac-openeo-examples/-/blob/main/python/SAR2Cube_openEO_examples_radar_mask.ipynb)
    - Generation of radar mask for Sentinel-1

4. [03_Land_Cover_Classification_second_part.ipynb](https://gitlab.inf.unibz.it/earth_observation_public/eurac-openeo-examples/-/blob/main/python/land_cover_exercise/03_Land_Cover_Classification_second_part.ipynb)
    - Corine Land Cover data via openEO
    - Dataset projection alignment and merge
    - Random sampling points generation
    - Sampling points filtering, given a priori knowledge
    - Random Forest training and prediction
    - Confusion Matrix computation and visualization