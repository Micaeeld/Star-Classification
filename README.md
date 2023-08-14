##### Use https://nbviewer.org to upload the file in case of errors
---

# Star rating

This notebook aims to classify stars using a data set that includes information such as temperature, luminosity, radius, absolute magnitude, star type, color and spectral class.

## Data set
The dataset used is available on Kaggle. It contains information on 240 stars of six different types: white dwarfs, main main sequence stars, giants, supergiants, hypergiants and binary stars. Columns include:

- Temperature (K)
- Luminosity (L/Lo)
- Radius (R/Ro)
- Absolute magnitude (Mv)
- Star type (OBAFGKM)
- star color
- Spectral Class


## Conclusion
The classification model with the best performance was Random Forest, which achieved an accuracy of 98.33% in cross-validation. This model was used to make predictions on a test dataset and achieved an accuracy of 95.83%. The model was able to correctly classify all types of stars present in the test dataset.

## References
Kaggle dataset: https://www.kaggle.com/datasets/deepu1109/star-dataset

## Contribution
Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue in the repository or submit a pull request. the pull request.
