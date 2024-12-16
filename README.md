# Clustering EII

## Code for the Paper
**Classification of Equatorial Ionospheric Irregularities Using Unsupervised Machine Learning Based on Spatiotemporal ROTI Keograms**

## Instructions:

1. Clone this repository to your local machine.
2. In the `Keograms` folder, extract the archives `dataset_old.rar` and `dataset_old_lat.rar`. Please place the extracted files in the `Keograms` folder.
3. To run the project, you can use Jupyter Notebook.
4. Using `pip`, install the libraries listed in the "Required Python packages" section.

## Required Python Packages:
- numpy
- scipy
- matplotlib
- sklearn
- opencv-python (cv2)
- Pillow (PIL)

## Brief Description of Files:

The project consists of three Python notebook files:

1. `Clustering_with_contours_extractor.ipynb` - Clustering program with contour feature extractor.
2. `Clustering_with_Statistical_extractor.ipynb` - Clustering program with statistical feature extractor.
3. `Clustering_with_PCA_extractor.ipynb` - Clustering program with PCA feature extractor.

## Data:

The data is located in the Keograms folder. Inside the folder there are data by year, 2021, 2022, 2023. Inside the folder for each year there is a folder with the day of the year (1-365). Thus, you can access pairs of ROTI keogram images (latitudinal and longitudinal).

We collected GNSS data (RINEX3) from two stations (Bangkok and Nakhon Ratchasima) over three years of 2021, 2022, and 2023 and then generated pairs of latitudinal and longitudinal keogram images. From three years of image data, there are 425 days with ionospheric irregularity events. It is important to note that we exclude the days without EII since the keogram plots are just broken if ROTI is below 0.3. We save these image files as input data for training and testing. 

## DOI:

https://doi.org/10.5281/zenodo.14498864

## Contact Information:

If you have any problems, questions, or suggestions, feel free to contact the author of this program, Gleb Mutasov or Lin Myint, via one of the following methods:

- Email: glebayva@gmail.com
- Email: linminmin.my@kmitl.ac.th

To check the license, please read the `LICENSE` file.
