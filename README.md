## First steps

1. Instal python 3.9

2. Download and install Tensorflow (and other libraries)

3. Install opencv-python.

- if you are in python3.

```
!pip3 install opencv-python
```

**Note:** This allow you to change to the _btgraham-300_ dataset

3. Download the dataset and follow the instructions.

```
This dataset requires you to download the source data manually into download_config.manual_dir (defaults to ~/tensorflow_datasets/downloads/manual/):
You have to download this dataset from Kaggle.
https://www.kaggle.com/c/diabetic-retinopathy-detection/data
After downloading, unpack the test.zip file into test/ directory in manual_dir
and sample.zip to sample/. Also unpack the sampleSubmissions.csv and
trainLabels.csv.
```

## Instructions for downloading the dataset

1. Download the training data set from [Kaggle](https://www.kaggle.com/c/diabetic-retinopathy-detection/data). Each file will be named _train.zip.001.zip, train.zip.002.zip ..._

2. Move the files to your download_config.manual_dir (defaults to ~/tensorflow_datasets/downloads/manual/).

3. Extract each file with zip compressor. After this step you will have two files for each file. Example: _train.zip.001.zip and train.zip.001_ . If you want to save storage remove the _train.zip.001.zip_

4. Select all the numbered files and extract its with 7zip (if you have windows) or keka (if you have mac)

5. Remove the numbered files.

6. In this step you will have a folder named train with the images.
