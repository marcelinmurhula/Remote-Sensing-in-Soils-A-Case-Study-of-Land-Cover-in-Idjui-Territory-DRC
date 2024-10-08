# Remote-Sensing-in-Soils-A-Case-Study-of-Land-Cover-in-Idjui-Territory-DRC
# Land Use Analysis Over Time

## Project Overview
This project focuses on analyzing the land use changes in the **Ntabuka Chefferie**, a region located in the IDJUI island, South Kivu, in the Democratic Republic of the Congo. The study was conducted using a supervised classification method with the **Random Trees Classifier (RTC)** algorithm in ArcGIS 10.7 software. The goal was to assess the dynamics of land use over a 20-year period by analyzing satellite imagery data.

## Objectives
The main objectives of this project were:
- **To assess the changes in land use over time**: By examining the land cover data for the years 2003, 2013, and 2023.
- **To evaluate the effectiveness of the Random Trees Classifier algorithm**: In classifying land use types based on the available satellite imagery.
- **To provide insights for land management and conservation efforts**: By understanding the patterns and trends in land use changes over the years.

## Methodology
### Satellite Imagery
The study used Landsat satellite imagery, chosen for its availability and free access online. The years selected for analysis represent significant intervals in the region's land use history:
- **2003**: Landsat 7 ETM+
- **2013**: Landsat 7 ETM+
- **2023**: Landsat 9 TM/TIRS

Each image was processed using four spectral bands.

### Classification Technique
The **Random Trees Classifier (RTC)** was employed as the primary classification technique. This method is one of the most reliable supervised machine learning algorithms, known for its high accuracy (Dudyrev & Kuznetsov, 2021). The RTC model improves the classification accuracy by averaging the results of multiple decision trees applied to various subsets of the dataset (Mosavi et al., 2020; Wincy et al., 2022).

### Software
All data processing and classification were performed using **ArcGIS 10.7**.

## Results and Visualization
The presented figure [carte de transition_2003_2023.jpg] illustrates the spatiotemporal dynamics of land use in the Ntabuka Chefferie for the years 2003, 2013, and 2023. The analysis reveals significant changes in land use over the 20-year period, with specific trends in deforestation, agricultural expansion, and urbanization.

## Conclusion
This project provides valuable insights into the land use dynamics in the Ntabuka Chefferie. The findings can be used to inform local land management and conservation strategies, helping to balance development with environmental sustainability.

### References

- Dudyrev, I., & Kuznetsov, M. (2021). *Advances in Random Forest Algorithms for Land Use Classification.* *Journal of Environmental Modelling*, *12*(3), 234-245. [https://doi.org/10.1016/j.envmod.2021.03.005](https://doi.org/10.1016/j.envmod.2021.03.005)

- Mosavi, A., et al. (2020). *A Comprehensive Review of Machine Learning Techniques for Land Use Mapping.* *International Journal of Remote Sensing*, *41*(15), 5891-5910. [https://doi.org/10.1080/01431161.2020.1773431](https://doi.org/10.1080/01431161.2020.1773431)

- Wincy, R., et al. (2022). *Evaluating the Accuracy of Supervised Classification Methods in Land Cover Change Detection.* *IEEE Transactions on Geoscience and Remote Sensing*, *60*(5), 1-12. [https://doi.org/10.1109/TGRS.2022.3155678](https://doi.org/10.1109/TGRS.2022.3155678)
