# Six-month infant brain tissue segmentation using three dimensional fully convolutional neural networks and pseudo-labelling
Implementation of the nic_vicorob team for addressing the MICCAI Grand Challenge on 6-month infant brain MRI segmentation [iSeg2017](http://iseg2017.web.unc.edu/results/).

## Requirements
### Folder structure
Once the repository has been clone/downloaded, there will be only the ```log``` and ```models``` folders and the iSeg2017.ipynb file. Add the folders ```datasets``` (folder containing the testing and training sets provided by the challenge organisers), ```results``` and ```refined-results```. The resulting tree should look as indicated below.

```
.
├── datasets
│   └── iSeg2017
│       ├── iSeg-2017-Testing
│       └── iSeg-2017-Training
├── iSeg2017.ipynb
├── log
│   └── iSeg2017
├── models
│   └── iSeg2017
├── refined-results
│   └── iSeg2017
│       └── iSeg-2017-Testing
└── results
    └── iSeg2017
        └── iSeg-2017-Testing 
```

### Libraries
The code has been tested with the following configuration

- h5py == 2.7.0
- ipython == 5.3.0
- jupyter == 1.0.0
- keras == 2.0.2
- nibabel == 2.1.0
- nipype == 0.12.1
- python == 2.7.12
- scipy == 0.19.0
- sckit-image == 0.13.0
- sckit-learn == 0.18.1
- tensorflow == 1.0.1
- tensorflow-gpu == 1.0.1

## How to run it
Once all the libraries above have been installed, the following step is to run the jupyter notebook on the folder containing the iSeg2017.ipynb file. 

```
jupyter notebook
```
