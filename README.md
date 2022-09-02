Agglomerative Model build in Sklearn for Clustering - Base problem category as per Ready Tensor specifications.

- sklearn
- python
- pandas
- numpy
- scikit-optimize
- docker
- clustering

This is a Clustering Model that uses agglomerative clustering implemented through Sklearn.

The algorithm starts by treating each object as a singleton cluster. Next, pairs of clusters are successively merged until all clusters have been merged into one big cluster containing all objects. The result is a tree-based representation of the objects.

The data preprocessing step includes:

- for numerical variables
  - Standard scale data

During the model development process, the algorithm was trained and evaluated on a variety of datasets such as car, iris, penguins, statlog, steel_plate_fault, and wine. Additionally, we also used various synthetically generated datasets such as two concentric (noisy) circles, four worms (four crescent-moon shaped clusters), and unequal variance gaussian blobs.

This Clustering Model is written using Python as its programming language. ScikitLearn is used to implement the main algorithm, evaluate the model, and preprocess the data. Numpy, pandas, and feature_engine are used for the data preprocessing steps. SciKit-Optimize was used to handle the HPT.
