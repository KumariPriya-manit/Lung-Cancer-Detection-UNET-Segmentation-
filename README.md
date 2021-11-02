# Lung-Cancer-Detection-UNET-Segmentation
This repository is to predicting whether a CT scan is of a patient who either has or will develop lung cancer within the next 12 months or not.
The network is trained to segment out potentially cancerous nodules and then use the characteristics of that segmentation to make predictions about the diagnosis of the scanned patient within a 12 month time frame.


# Requirement

* numpy
* scikit-image
* scikit-learn
* keras 2 (tensorflow backend)
* matplotlib
* pydicom
* SimpleITK
