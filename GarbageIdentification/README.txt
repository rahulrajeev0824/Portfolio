Garbage image identification system using convolutional neural networks. My first project looking into multi-label image classification for images of garbage within five categories: Glass, Plastic, Metal, Clothes, and Paper. I went through several phases in determining the optimal method for data selection and model tuning, and ended up with a 30% accuracy. Results were significantly better than just using the plain images in the dataset linked below when using an AI background noise removal python library called rembg. That will also be linked below.

Downloading data:
https://www.kaggle.com/datasets/yashkangale20/garbage-classification

Images are in two folders split into train and test, followed by five categories for each folder.
To get cleaned versions and ai enhanced versions, follow the steps detailed in the notebook and report.

Implementation:
Cleaning data and modeling process are all done by the notebook, but to save time and effort, find a model with methodologies you would like to try and run that one only. The training epochs ran locally took about 11-15 minutes depending on parameters so keep that in mind. No early data analysis or visualizations were created apart from presenting the images in the dataset before and after transformation.

The finalized model I used will be provided in the directory, whether you choose to use it or not is up to you.

Additional documentation:
https://www.geeksforgeeks.org/how-to-remove-the-background-from-an-image-using-python/

The rembg package was remarkably useful for the entirety of the project and ideas regarding it's usage for other classification projects have already started appearing in my head.